# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ----- | ------ |
| Sara, Ibarra, 32 | {firstName: Sara, lastName: Ibarra, age: 32}    | 
| Trisha, Calhoun, 35| {firstName: Trisha, lastName: Calhoun, age: 34} | 
| Abraham, Meza, 18| {firstName: Abraham, lastName: Meza, age: 18}    | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>It takes the key/value pairs for the person object and and returns the the key/values pairs when the function is called. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible

