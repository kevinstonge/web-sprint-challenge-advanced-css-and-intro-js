# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. How would you describe preprocessing to someone new to CSS?

CSS is a way of putting into words and symbols information about how you want a website to look visually (colors, backgrounds, organization, whitespace, etc). a CSS preprocessor gives the developer more tools and strategies to make this process easier, more intuitive, and more powerful. 

2. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

Nesting in less was a game changer for me, it allowed me to focus more on styling and less on digging through my code to figure out where some style was overriding some other style due to specificty

The concept that gave me the most trouble with less was remembering to run less-watch-compiler and changing the code half a dozen times wondering why it's not working.

3. How would you explain the concept of a variable to someone new to programming?

In plain language, a variable is just something that can be changed, but in programming a variable is kind of like a label that points to some information. you can store just about anything inside a variable, from a single number to a deeply nested array of objects. Then when you want to work with that information in your code, you get to simply work with that 'label' instead of working with large clumps of data directly.

4. What is the purpose of using functions in code?

functions help break down your code into manageable chunks. Instead of doing everything you want your code to do one line at a time, you create functions to separate simple tasks, then call those functions in sequence to complete complex, multi-step tasks.

5. What is JSON data?

JavaScript Object Notation: a data format that converts javascript objects into plaintext strings. The syntax is almost identical to the syntax used for writing objects in javascript. One main exception is that key names are enclosed in quotes while this is optional in plain javascript.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

- [ ] Create a forked copy of this project.
- [ ] Add your Team Lead as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Add a viewport meta tag to the head of your index.html page.
* [ ] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

> Include stretch goals in this section. These are additional things the student can do go beyond basic proficiency, and push their scores on the challenge up to a 3. Be clear that these are *not* required. Completing all of the tasks in the required section must be sufficient to  demonstrate proficiency of all sprint objectives, and earn a score of '2. 

> Example stretch goals below:

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Use JavaScript to programmatically create HTML elements in the console and copy them to display all 20 artists on the page
* [ ] Create a function called `randomize` that takes a data array as an argument and returns a the same array in a randomized order.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example)
* [ ] Add responsive breakpoints to your code by using media queries
* [ ] Add CSS animations

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
