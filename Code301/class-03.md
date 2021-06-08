# Read: Class (03) Passing Functions as Props

---

**There is some important question we should ask us about State and Props:**

<br>

**What does .map() return?** he results after applying the given function to each item of a given iterable for example list.

**If I want to loop through an array and display each value in JSX, how do I do that in React?** we can put any valid JavaScript expression inside the curly braces in JSX for example:

`function NumberList(props) {`

 ` const numbers = props.numbers;`
 
  `const listItems = numbers.map((number) =>`
  ` <ListItem key={number.toString()}`
        `      value={number} />`
 ` );`
 ` return (`
    <ul>
 `     {listItems}`
    </ul>
 ` );`
`}`

---
<br>

---

**Each list item needs a unique.** key

<br>

**What is the purpose of a key?** Keys help React identify which items have changed.

<br>
---

**What is the spread operator?** is a new addition to the set of operators It takes in an iterable like an array.

<br>

**List 4 things that the spread operator can do.**

1-Concatenating or combining arrays.

2-Using Math functions.

3-Using an array as arguments.

4-Adding an item to a list

<br>

**Give an example of using the spread operator to combine two arrays.** merge two arrays using the spread operator.

**Give an example of using the spread operator to add a new item to an array.**

`let parts = ['shours', 'ksas'];`
`let lyrics = ['head', ...parts, 'and', `

`'toes']; `


<br>

**Give an example of using the spread operator to combine two objects into one.**

`const person = { name: 'David Walsh', `

`gender: 'Male' };`
`const tools = { computer: 'Mac', editor:`

`'Atom' }; `

`const summary = {...person, ...tools};`

---

**In the video, what is the first step that the developer does to pass functions between components?** create the function wherever the state is.

**In your own words, what does the increment function do?** it determines the next node at the same level.

**How can you pass a method from a parent component into a child component?** by Functional child component to Parent functional component in the instance create a variable and put the method inside the curly prices.

**How does the child component invoke a method that was passed to it from a parent component?** through extending after this import child page to parent page to send the properties of the method


<br>

<br>

<br>

**_In the end, I hope you enjoying reading, best wishes._**

References:
<https://stackoverflow.com/questions/37949981/call-child-method-from-parent>

<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax>