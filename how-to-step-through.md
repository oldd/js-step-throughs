# How to Step Through

PythonTutor is an outstanding tool that will help you learn JavaScript faster than you knew was possible. We recommend you use this tool to complement an existing tutorial (like [javascript.info](https://javascript.info), [Practical JavaScript](https://shawnr.gitbooks.io/practical-introduction-to-javascript/content/), or [w3schools](https://www.w3schools.com/js/default.asp)) by carefully studying each example.  

To help you get the most out of PythonTutor we've provided you with this guide, studied examples, a template you can use to study new examples, and a repository you can fork to store you own examples.  

___

## Interpreting PythonTutor

// prepare screen shots

Primitives:
* live directly in the PythonTutor Frames.
* undefined, number, string, ...
* things that don't hold other things
* each variable pointing to a primitive stores it's own copy

Objects:
* live in the Objects column of PythonTutor
* variables point to these. 
  * ie: modfying one variable's object will show up in others
* things that store other things
* functions, objects, arrays, ...

Frames: 
* called Execution Contexts outside of PyTut
* a new one is created each time a function is executed
* and closes when that function returns
* contain their own variables
* have access to variable in parent (higher) frames
* cannot access variables in lower frames

Arrows (pointers):
* these indicate what object a variable is referencing

___

## Resources:

PythonTutor:
* [Intro Video](https://www.youtube.com/watch?v=u0FbLpRDcxU)
* [Intro Article](http://pgbovine.net/python-tutor-live.htm)
* [GitHub Repo](https://github.com/pgbovine/OnlinePythonTutor)
* [About PythonTutor](https://www.youtube.com/watch?v=sVtXLdBRfyE)

[Examples to Study](./examples-to-study)

[Step-Through Template](./copy-this-for-each-step-through.md)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>