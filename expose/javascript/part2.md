# Part 2

1. Line 12 will print out the length of prices, which is 3 in this case, because i increases until it reaches the value of prices.length.
2. Line 13 will print out the discounted price of the last element in prices, since var made discountedPrice have a function scope, and it will store the last assignment to it which is in the last iteration of the for loop over prices. It specifically prints out 150, because the discount is 0.5 or 50% and the last price is 300.
3. Line 14 will print out the last discounted price rounded to 2 decimal places because finalPrice is in scope and that's how the math works out, but since 150 was the last discounted price and it doesn't have decimal places to round, line 14 just prints out 150.
4. This returns an array [50, 100, 150] of discounted prices rounded to 2 decimal places, in the order of the original prices array because that's the order the final prices were pushed to it.

5. The code causes an error because i has the scope of the inside of the for loop, but the code tries to access it outside of the scope.
6. The code causes an error because discountedPrice has the scope of the inside of the for loop, but the code tries to access it outside of the scope.
7. Line 14 will print out 150 because finalPrice is in the same scope as the line, so finalPrice's last assignment within the for loop is accessible.
8. This returns an array [50, 100, 150] of discounted prices rounded to 2 decimal places, in the order of the original prices array because that's the order the final prices were pushed to it.

9. The code causes an error because i has the scope of the inside of the for loop, but the code tries to access it outside of the scope.
10. Line 12 will print out the length of prices, 3, because that's what it was assigned and prices is in scope. 
11. This returns an array [50, 100, 150] of discounted prices rounded to 2 decimal places, in the order of the original prices array because that's the order the final prices were pushed to it. Because pushing values to an array doesn't reassign the variable of the array, the code doesn't cause an error.

12. a. student.name
    b. student["Grad Year"]
    c. student.greeting()
    d. student["Favorite Teacher].name
    e. student.courseLoad[0]

13. a. 32 because 2 maps to a string
    b. 1 because '3' maps to a number
    c. 3 because null maps to 0
    d. "3null" because null maps to a string
    e. 4 because true maps to 1
    f. 0 because both false and null map to 0
    g. "3undefined" because undefined maps to a string
    h. NaN because undefined maps to NaN

14. a. true because '2' maps to 2, which is greater than 1
    b. false because '2' is lexicographically greater than '1'
    c. true because '2' maps to 2
    d. false because they are different data types
    e. false because true maps to 1
    f. true because any input to Boolean() that isn't intuitively empty becomes true.

15. The == operator outputs true when the values in the comparison are of the same data type and have the same value, or if they are of different data types, when the values convert into the same number. Meanwhile === only outputs true when there's an exact match between values of the same data type.

17. The result that is returned is the array [2, 4, 6] because the function doSomething will return its argument doubled, so when doSomething is used as a callback with an argument of the ith value of the array [1, 2, 3], it returns that ith value doubled. This return value of the callback is pushed into the array newArr which is the return value.

19. The output is:
1
4
3
2