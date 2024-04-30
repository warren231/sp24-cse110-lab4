# Part 1

1. Line 9 prints "values added: 20".
2. Line 13 prints "final result: 20".

3. Line 9 prints "values added: 20".
4. The code returns an error because the line `console.log('final result: ', result);` is outside of the block `result` is defined in, i.e. result is not in scope.

5. The code returns an error because `result` can't be reassigned to num1 + num2 since it was declared as `const`.
6. The code returns an error because of the previous reassignment error.