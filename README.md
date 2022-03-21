# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (animal){
  const normalizedName = animal.toLowerCase() 

  if (normalizedName === "alligator"){
    return "small"
  } else {
    return "wide"
  }
}
```

| Input | Output |
| "Alligator" | "small" |
| "Lion"      |  "wide" | 
|  "Chicken"  |  "wide" | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This function returns the string "small" if a string with "alligator" inputted (no matter how it is capitalized). The function returns the string "wide" if the inputted string is anything else. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
