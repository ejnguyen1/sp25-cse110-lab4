1. Line 12 prints `3`, the number stored by `i`. This is the size of the `prices` array.
2. Line 13 prints `150`, the most recent value stored in `discountedPrice`.
3. Line 14 prints `150`, the most recent value stored in `finalPrice`.
4. This function will return `[50, 100, 150]`, the `discounted` array. This array contains the values from the `prices` array, but discounted by the `discount` amount.
5. Line 12 causes an error. Because `i` is declared using the `let` keyword, it is block-scoped and therefore undefined outside of the `for` block.
6. Line 13 causes an error. Because `discountedPrice` is declared using the `let` keyword, it is block-scoped and therefore undefined outside of the `for` block.
7. Line 14 returns `150`, the most recent value stored in `finalPrice`.
8. This function will return `[50, 100, 150]`, the `discounted` array. This array contains the values from the `prices` array, but discounted by the `discount` amount.
9. Line 11 causes an error. Because `i` is declared using the `let` keyword, it is block-scoped and therefore undefined outside of the `for` block.
10. Line 12 prints `3`, the value stored in `length`. This is the length of the prices array.
11. This function will return `[50, 100, 150]`, the `discounted` array. This array contains the values from the `prices` array, but discounted by the `discount` amount.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher']['name']
    E. student['courseLoad'][0]
13. A. `'3' + 2 = '32'` <br>
    Since `3` is a string, the `+` operator concatenates these two values as strings. The integer `2` maps to its exact string representation. <br>
    B. `'3' - 2 = 1` <br>
    The `-` operator expects integers, so string `'3'` maps to its integer representation. <br>
    C. `3 + null = 3` <br>
    As a number, `null` represents `0`, so  we get the sum of `3 + 0`. <br>
    D. `'3' + null = '3null'` <br>
    Because `'3'` is a string, the `+` operator concatenates these two values both as strings. `null` maps to its exact string representation. <br>
    E. `true + 3 = 4` <br>
    Since `true` maps to the integer `1`, the `+` operator adds these values together as integers. <br>
    F. `false + null = 0` <br>
    The integer representation of both of these values is `0`, so `+` operator adds these values together as integers. <br>
    G. `'3' + undefined = '3undefined` <br>
    Since `3` is a string, so the `+` operator concatenates these values as strings. `undefined` maps to its exact string representation. <br>
    H. `'3' - undefined = NaN` <br>
    The `-` operator expects int egers, so string `'3'` maps to its integer representation. `undefined` maps to `NaN`, and any subtraction with this value results in `NaN`. 
14. A. `'2' > 1 = true` <br>
    The `>` operator converts both values to integers, so `2` maps to its integer representation. <br>
    B. `'2' < '12' = false` <br>
    Because both values are strings, they are compared character-by-character. The first characters are compared (`'2' < '1'`), and this evaluates to `false`. <br>
    C. `2 == '2' = true` <br>
    Because the operator is `==`, string `'2'` maps to its integer representation and the two values are equal. <br>
    D. `2 === '2' = false` <br>
    `===` signifies strict equality, and these values are not equal without coversion. <br>
    E. `true == 2 = false` <br>
    Since `true` maps to the integer `1`, these integer values are not equal. <br>
    F. `true === Boolean(2) = true` <br>
    `Boolean(2)` returns `true`, causing these values to be strictly equal. <br>
15. The `==` operator checks regular equality, meaning values that are equivalent but different types will be determined equal. The `===` checks for strict equality, meaning values must be the same type (equal without conversions).
17. `modifyArray` iterates through the inputted array. For each value in the array, the function uses `callback` to perform another function on this individual number in the array. In this case, `callback` calls the function `doSomething`, which multiplies an inputted integer by 2. This causes each number in the inputted array to be doubled. 
19. When `printNums` is run, first it prints `1`. Next, line 3 executes, causing it to print `2` in 1 second. Next, line 4 executes, causing it to print `3` in 0 seconds. However, both of these timers do not start until the rest of the synchronous code executes. Therefore `4` is printed next, the `3` after 0 seconds, then `2` after 1 second.