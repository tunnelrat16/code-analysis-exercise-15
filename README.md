# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

| Input              | Output              |
| -----              | ------              |
| 'Billy', 'Flipper' | return is undefined | 
| 'Marsha', 'Tiger'  | return is dog       | 
| 'Shaggy', 'Scooby' | return is dog       | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes the inputted person object and looks at each dog item in the array dogs that is connected to that object. If the value dog.name matches the inputted petName, it will return the value of dog.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
