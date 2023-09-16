---
layout: essay
type: essay
title: "JavaScript: Humble Beginnings v2.0"
# All dates must be YYYY-MM-DD format!
date: 2023-08-24
published: true
labels:
  - JavaScript
---

*It’s All Coming Back to Me…*

JavaScript was perhaps the first programming language I ever learned in my life. In my junior year of high school, I got my first experience in learning the language and applying it to small projects to witness the power and the beauty of lines of code in a file. 

Three years later, unfortunately the knowledge from my humble beginnings didn’t stick around. However, as I’m here today in ramping up my journey as a prospective software engineer, the past is here to visit. My job: to hopefully make it stay as I revisit the JavaScript programming language in my software engineering course.

## An Eye-opening Path to Greatness

With the ball rolling for my first week, my first coding task: learn JavaScript. Despite me learning the language in the past, I’ve forgotten a lot about it. Not to mention the introduction of ES6, which from what I understand is the newest “version” of JavaScript. I had no idea JavaScript even had “versions.” Getting into the coding bootcamp to learn JavaScript, I was already introduced to new syntax that was never covered in my previous learning, such as the let and const keywords used in declaring variables. Aside from the basic syntax which was very easy to get comfortable with due to prior knowledge, picking up the new concepts came in pretty swiftly. For instance, I figured that the const keyword in JavaScript would be similar or if not, almost the same, as the usage of the const keyword in C and C++. The majority of the fundamental relearning went smooth and seemed quite similar to things found in Java and Python.

Despite some comfort in the basics of JavaScript, the new concepts, primarily from ES6, laid out a new playing field for me. It took me some time to grasp the new syntax introduced. A lot of the new material was meant to provide much more flexibility in using the language for certain things, such as working with arrays and conveniently obtaining the values from JavaScript Objects. I’ve witnessed, as my former colleagues used to say, “Python magic,” before, but I’ve never seen great flexibility built into the syntax of a language like JavaScript. Prior to this, I’ve mainly been working with C and C++ which had very little flexibility in working with objects and arrays, making the switch to a language like JavaScript a bit uneasy. Despite that though, I’ve come to see the greatness of JavaScript given how flexible it is and how much it can accomplish. As a prospective software engineer, I think it’s a great language to have under one’s toolbelt especially with how heavily it is used in web page applications and working with APIs on the server side.

## Let's Get Physical! (with code)

After getting situated with JavaScript, it was time to put it to the test with the course’s athletic software engineering exercises commonly referred to as WODs (or the Workout of the Day). The practice WODs that I’ve gone through so far were quite helpful. Not only did I get a good sense of what I can expect for the real thing, but these practice WODs ensured that my learning continued even past the coding bootcamp. Despite the timed factor of these exercises which can be stressful sometimes especially when things don’t go smoothly, learning through doing WODs is benefitting me a lot. One thing that I hold in the back of my mind is that I tend to think that there is always a better way to do something. I know that despite how much I’ve learned about the fancy syntax, objects, or functions I can employ in my code to carry out tasks, my application of it isn’t quite caught up. By doing the WODs, I can put my ability to the test and create my own solution, which is at least for now, something that will work to accomplish the task at hand. Afterwards, I can view other solutions, all of which had different approaches in tackling the problem. Going through these other solutions, I picked up a lot of things that I can apply in the future such as ways to structure my code to help keep things organized and ways to help improve the efficiency of my code. One example would be one of the practice WODs I previously completed.

```
function isUnique(str) {
	const charArr = [];
  for (let idx = 0; idx < str.length; idx++) {
  	if (charArr.includes(str[idx])) {
    	return false;
    } else {
    	charArr.push(str[idx]);
    }
  }
  return true;
}
```

While my solution did work, it could have been made better. After viewing other solutions, a way that I’ve picked out that would make this more efficient would be to use a JavaScript Object to “map” the values in a string to check for repeat characters rather than the use of the .includes() method, as that method is essentially performing a linear search while nested inside another for loop in my solution, leading to a worst case runtime of O(n<sup>2</sup>).

## The Path Forward

Revisiting my humble beginnings surely was an enjoyable learning experience for me. With the combined practice of WODs and the learning of new concepts from ES6, I feel confident about being able to showcase this programming language under my toolbelt and apply it to future exercises and projects.