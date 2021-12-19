------------------------------
01-Homework
------------------------------

Code Refactoring
------------------------------
In this homework assignment, our given task was to refactor the provided html and css to the Horiseon website and apply refactoring.

Refactoring is the process of restructuring, and improving, pre-existing code without affecting its visual properties or core functionality.

I first attempted my assignment by heading straight into our style.css in order to scope out any patterns. My goal here was to condense any lines of code that repeated itself such as the styling of many class selectors of this application. Many selectors of this code came with identical styling; by locating these selectors I found was the simplest and quickest fixes to this refactoring assignment. 

An issue I ran into while working on this assignment was figuring out how to get our #search-engine-optimization hyperlink to auto-scroll to our desired term. Although I could have easily missed it, I was finally able to solve this issue by providing my own spacing and indentation to index.html, and locating the missing ID that I then provided to #search-engine-optimization for our broken anchor link.

After successfully solving the anchor link, I decided to implement my own elements to the application. My goal was to install a hyperlink into the "seo" of our "Horiseon" header while maintaining the pre-existing styling of the text. I found this was possible by going inside the <span> selectors of our header and insert my <a href> link within. 
------------------------------

![Screenshot of Application // All refactored code should still maintain these visual properties.](C:\Users\britt\bootcamp\code-refactoring\Develop\assets\images\01-html-css-git-homework-demo.png)

**To Do** 
- Finish Writing README✔️
- Double check for any missed refactoring✔️
- Clean up repo folder before submission✔️
- Launch app and retrieve url✔️