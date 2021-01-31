## Part1 Intro to Javascript
1. prints value of i which is price length because var is global-scoped and not local to the loop
2. prints value of discountedPrice because var is global-scoped and not local to the loop
3. prints value of finalPrice because var is global-scoped
4. [50,100,150] the function executes normally and the variables are updated according to the input.
5. i is not defined, let is blocked scoped and i is in the for loop block
6. discountedPrice is not defined, let is block scoped and discountedPrice is in the for loop block
7. the value of finalPrice, let is block scoped and finalPrice is in the function block 
8. [50,100,150] the function executes normally and the variables are updated according to the input.
9. i is not defined, let is blocked scoped and i is in the for loop block
10. discountedPrice is not defined, const is block scoped and discountedPrice is in the for loop block
11. prints 0, value of const variables cannot be changed
12. [] the function executes normally and discounted cannot be updated as it has the type const.
13. A. student.name B. student['Grad Year'] C. student.greeting() D. student['Favorite Teacher'].name E. student.courseLoad[0]
14. A. 32 String conversion happens when we need the string form of a value.
    B. 1 when - is used nonnumbers are converted to numbers 
    C. 3 null has the value of 0 and numeric conversion happens in maths operations
    D. 3null String conversion happens when we need the string form of a value.
    E. 4 true has the value of 1 and numeric conversion happens in maths operations
    F. 0 null and false have the value of 0 and numeric conversion happens in maths operations
    G. 3undefined String conversion happens when we need the string form of a value.
    H. NaN error gives the value NaN
15. A. true using when comparing '2' is converted to 2 and 2>1 is true
    B. false alphabetically '2' is larger than '12'
    C. true using loose equals '2' is con
    D. false using strict equals 2 and '2' have different data types
    E. false true has the value 1 which is not equal to 2
    F. true Boolean(2) evaluates to true which is the same type and value as true 
16. "===" compares the data type of two variables and only returns true when the data types are the same, and "==" does not and would return true when values are the same
17. "How are you" is printed 2 == true is false, 2 is true, thus the second block is executed
18. part1-question18.js
19. "[6,8,10]" A callback function is a function pushed in another function as an arguement, the array [1,2,3] and the function do something are inputs to the modifyArray function, each individual element of the array [1,2,3] and the function function(x) {return x * 2;} are the inputs to the doSomethingfunction. 1 is input into doSomething which inputs (1+2) to function(x), which returns 3 * 2 = 6 to doSomething which is returned and pushed to newArr. The same process happens for 2 3 and thus we get the result.  
20. part1-question20.js
21. "1432" is the output. 1 is printed first as it is the first command and is not controled by a setTimeout function. 4 is printed before 3 and 2 because it is not controled by setTimeOut, the functions controlled by setTimeOut are queued to be executed after the interpreter has executed other functions.3 would be printed before 2 as 2 is set to print after 1000ms, while 3 is set to print at 0ms.
