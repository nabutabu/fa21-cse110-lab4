1. At line 12 the final value of i, or the length of the prices array is printed. We will log how many items were discounted. **Result:** 3
2. Variable 'discountedPrice' was declared with the keyword var, hence it has function wide scope. On line 13 we see the discountedPrice of the last item in the prices list. **Result:** 150   
3. Variable 'finalPrice' has also been declared with the keyword var, hence it has a function wide scope. On line 14 we see the last value assigned to it, or the finalPrice ie after rounding, of the last item in the prices array. **Result:** 150
4. This function returns an array of prices which have been discounted (the 'discounted' array). It is the list of all prices discounted by the rate given in the second parameter 'discount'. **Result:** [50, 100, 150]
5. Reference Error.
   
   **Reason:** Variable i has been declared with the keyword let and thus only has scope in the code block it has been declared in. In this case that is the for loop. Since the console output is outside the scope of the for loop, an error is thrown.
6. Reference Error.
   
   **Reason:** Same as variable i. Because it has been declared with the let keyword variable discountedPrice has scope only till the for loop.
7. Even though the finalPrice variable has been declared with the let keyword the let keyword allows scope in the function block, hence no error is thrown. **Result:** 150
8. Same Result, no errors thrown. **Result:** [50, 100, 150]
9. Reference Error.
   
   **Reason:** Variable i has been declared with the keyword let and thus only has scope in the code block it has been declared in. In this case that is the for loop. Since the console output is outside the scope of the for loop, an error is thrown.
10. Program returns the length of the prices array which was stored in the 'length' variable. Since the value of the variable was not changed, no error was thrown. **Result:** 3
11. Same Result, no errors thrown. **Result:** [50, 100, 150]
12. 1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. 1. '32'
    2.  1
    3.  3
    4.  '3null'
    5.  4
    6.  0
    7.  '3undefined'
    8.  NaN
14. 1. true
    2. false
    3. true
    4. false
    5. false
    6. true
15. == is a non-strict check between two vairables and checks the values of the variables instead of their types. === is a strict check and also checks types of the two operands.
16. In JS file
17. **Result:** [2, 4, 6] The array [1,2,3] is passed in as the 'array' argument of the modifyArray function and the function doSomething is passed as the callback argument. In the for loop modifyArray calls the function callback (doSomething) on every element of the array and makes a newArr with the returned elements. Finally newArr is returned.
18. In JS file
19. ```
    1
    4
    3
    2
    ```