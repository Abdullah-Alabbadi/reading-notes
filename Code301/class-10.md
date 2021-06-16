# Read: Class (08) memory storage

## There is some important question we should ask us about memory storage:

---
<br>

**What is a ‘call’?** You can write a method that can be used on different objects, also for function invocation so allows for a function/method belonging to one object.

<br>

**How many ‘calls’ can happen at once?** One at a time, from top to bottom.

<br>

**What does LIFO mean?** It's like the way that takes this design, Last in, first out (LIFO) is a method used to account for inventory that records the most recently produced items as sold first.

<br>

**Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

 `function add(value1, value2) {`
    `  return value1 + value2;`
    `}`
    `function average(value1, value2) {`
      `return add(value1, value2) / 2;`
    `}`
    `let x = average(10, 20);`

<br>

**What causes a Stack Overflow?** Occurs when there is a recursive function a function that calls itself without an exit point.

---

**What is a ‘refrence error’?** when you try to use a variable that is not yet declared.

<br>

**What is a ‘syntax error’?** you have something that cannot be parsed in terms of syntax

<br>

**What is a ‘range error’?**when you manipulate an object with some kind of length not valid this will appear

<br>

**What is a ‘tyep error’?**when you trying to use or access incompatible, like accessing a property in an undefined type of variable like a number, string.

<br>

**What is a breakpoint?** At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values

.<br>

**What does the word ‘debugger’ do in your code?** when running the code you can see the “history” before reaching that breakpoint, it's like a process of detecting and removing existing and potential errors.

<br>

_**In the end, I hope you enjoying reading, best wishes.**_

<br>

_**References:**_

<https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/>

<https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c>