# Armin's Notes
## Summary 
This repository contains all of the notes taken by [Armin](https://github.com/parniaa) for the Lighthouse Labs Web Development Bootcamp.

## Table of contents
* [Week 1](/Week_1)
  * [Day 1](/Week_1/Day_1)

### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

### cheatsheet
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

```
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log("Get back to work");
  } else {
    if (availableTime < 20) {
      console.log("Pick something up and eat it in the lab");
    }
    if (20 <= availableTime && availableTime < 30) {
      console.log("Try a place nearby");
    }
    if (availableTime > 30) {
      console.log("You are in a bootcamp and you should reconsider how much time you actually have to spare");
    }
  }
};
```

convert the strings to numbers -> https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number#Convert_numeric_strings_to_numbers


The array slice method can be used on an array to remove some of initial elements that we do not need.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice

### A "library" is a collection of pre-written code. Libraries can be private, but many are packaged up nicely, branded and made publicly available for other developers to use i

n their own projects.

### * creating new repo in git.

    git init

    git remote add origin <URL>
    
* Template Literals on MDN:

  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals

  