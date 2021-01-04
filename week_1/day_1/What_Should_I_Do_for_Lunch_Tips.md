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