| input       | output   |
| ----------- | -------- |
| green       | yellow   |
| yellow      | red      |
| red         | green    |



The function is taking the current color , either green, yellow or red , and returning a color as "nextColor" based on what current
color is. For example, if green is the current color then it would return yellow and since its true.
 But if current color is yellow then it would skip the first expression because it would be false and then go 
on to the second expression, which would be true, so it would return color red. Same for the color red, since 
first and second expression would be false it would continue to the final expression , which would be true so would return color green. 