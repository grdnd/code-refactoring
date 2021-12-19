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

![Screenshot of Application // All refactored code should still maintain these visual properties.](C:\Users\britt\bootcamp\code-refactoring\Develop\assets\images\01-html-css-git-homework-demo.png?raw=true) "Screenshot of Horiseon Website"

------------------------------
**To Do** 
- Finish Writing README✔️
- Double check for any missed refactoring✔️
- Clean up repo folder before submission✔️
- Launch app and retrieve url✔️


------------------------------
HOMEWORK-01

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Grading Requirements

This homework is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the homework instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.
