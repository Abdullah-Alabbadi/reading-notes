# Read: Class (02) State and Props

---
**there is some important question we should ask us about State and Props:**

<br>

**First: Based on the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?** render come first and It's called once after the first render this process called: componentDidMount.

<br>

**What is the very first thing to happen in the lifecycle of React?** The first thing that is Derived from props this process called: getDerivedStateFromProps().

 <br>
**Put the following things in the order that they happen;** constructor, render, React Updates, componentDidMount, componentWillUnmount.

 <br>

**What does componentDidMount do?** every time we want to load anything using a network request or initialize the DOM will start.

<br>

**What types of things can you pass in the props?** The values can be any data type, from strings to functions, objects.

<br>

**What is the big difference between props and state?** two Props and state are related because the props of a child component also Props are passed to the child within the render method.

<br>

**When do we re-render our application?** just when a component's state has changed.

<br>

**What are some examples of things that we could store in the state?** we can store data for use in a component: static and this.

<br>

---

<br>

**_In the end, I hope you enjoying reading, best wishes._**

<br>

_**reference:**_
<https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093> 

<https://www.freecodecamp.org/news/where-do-i-belong-a-guide-to-saving-react-component-data-in-state-store-static-and-this-c49b335e2a00/ >