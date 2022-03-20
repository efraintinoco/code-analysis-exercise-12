# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| input       | output   |
| ----------- | -------- |
| green       | yellow   |
| yellow      | red      |
| red         | green    |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function is taking the current color , either green, yellow or red , and returning a color as "nextColor" based on what current
        color is. For example, if green is the current color then it would return yellow and since its true.
        But if current color is yellow then it would skip the first expression because it would be false and then go 
        on to the second expression, which would be true, so it would return color red. Same for the color red, since 
        first and second expression would be false it would continue to the final expression , which would be true so would return color green. </td>
  </tr>
</table>



## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
