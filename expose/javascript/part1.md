1. Line 9 prints the sum of `num1` and `num2`.
2. Line 13 prints the value of result (sum of `num1` and `num2`). 
3. You shouldn't use var because it is function scoped. This means it can't be accessed outside the function it's declared in. 
4. Line 9 prints the sum of `num1` and `num2`.
5. Line 13 returns an error because `result` is declared using `let`. The `let` keyword uses block-scoping, meaning its variable is only accessible within the code block it was declared in.
6. Line 9 returns an error because variable `result` is assigned using the keyword `const`, meaning the variable can't be reassigned.
7. Line 13 isn't reached, as this code errors before.