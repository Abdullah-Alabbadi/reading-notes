# Read: Class (04) Readings: React and Forms

---

**What is a ‘Controlled Component’?** We use it if we want the function to access the data that the user entered into the form so it takes current value through props and notifies.

<br>

**Should we wait to store the user's responses from the form into a state when they submit the form OR should we update the state with their responses as soon as they enter them and Why?** we should update the state as soon as possible because React takes some time to update the state.

<br>

**How do we target what the user is entering if we have an event handler on an input field?** by add a name attribute to each element and let the handler function choose what to do based on the value of `event.target.name.`

<br>

**Why would we use a ternary operator?** it's to simplify our if-else statements that are used to assign values to variables.

<br>

**Rewrite the following statement using a ternary statement**

`if(x===y){`

`console.log(true);}`

`else{`

`console.log(false);}`

`x===y ? console.log(true) : console.log(false)`

<br>

---

<br>

**In the end, I hope you enjoying reading, best wishes.**

<br>

**_References:_**

`https://react-bootstrap.github.io/components/forms/`

`https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff`