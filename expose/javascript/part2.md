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
13. A. `'3' + 2 = '32'`
    Since `3` is a string, the `+` operator concatenates these two values as strings. The integer `2` maps to its exact string representation.
    B. `'3' - 2 = 1` 
    The `-` operator expects integers, so string `'3'` maps to its integer representation.
    C. `3 + null = 3` 
    As a number, `null` represents `0`, so  we get the sum of `3 + 0`.
    D. `'3' + null = '3null'` 
    Because `'3'` is a string, the `+` operator concatenates these two values both as strings. `null` maps to its exact string representation.
    E. `true + 3 = 4`
    Since `true` maps to the integer `1`, the `+` operator adds these values together as integers.
    F. `false + null = 0`
    The integer representation of both of these values is `0`, so `+` operator adds these values together as integers.
    G. `'3' + undefined = '3undefined`
    Since `3` is a string, so the `+` operator concatenates these values as strings. `undefined` maps to its exact string representation.
    H. `'3' - undefined = NaN`
    The `-` operator expects integers, so string `'3'` maps to its integer representation. `undefined` maps to `NaN`, and any subtraction with this value results in `NaN`.
14. A. `'2' > 1 = true`
    The `>` operator converts both values to integers, so `2` maps to its integer representation.
    B. `'2' < '12' = false`
    Because both values are strings, they are compared character-by-character. The first characters are compared (`'2' < '1'`), and this evaluates to `false`.
    C. `2 == '2' = true`
    Because the operator is `==`, string `'2'` maps to its integer representation and the two values are equal.
    D. `2 === '2' = false`
    `===` signifies strict equality, and these values are not equal without coversion.
    E. `true == 2 = false`
    Since `true` maps to the integer `1`, these integer values are not equal.
    F. `true === Boolean(2) = true`
    `Boolean(2)` returns `true`, causing these values to be strictly equal.
15. The `==` operator checks regular equality, meaning values that are equivalent but different types will be determined equal. The `===` checks for strict equality, meaning values must be the same type (equal without conversions).
16. 
