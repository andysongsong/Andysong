# [XinJian Song]'s Notes

# This is an H1 header (largest)

###### This is an H6 header (smallest)

## Summary

This repository contains all of the notes taken by [XinJian Song] for the Lighthouse Labs Web Development Bootcamp.
[Link Text](https://github.com/andysongsong/lighthouse-web-note.git)
Table of Contents

- Week 1
  - Day 1

### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry === true) {
    if (availableTime < 20) {
      console.log("Pick something up and eat");
    } else if (availableTime <= 30 && availableTime >= 20) {
      console.log("Try nearby restaurant");
    } else {
      console.log("Reconsider how much time we actually have to spare");
    }
  } else {
    console.log("Get back to work");
  }
};
```
