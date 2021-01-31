## Part1 Intro to Javascript
1. prints value of i which is price length
2. prints value of discountedPrice
3. prints value of finalPrice 
4. [50,100,150]
5. i is not defined, let is blocked scoped and i is in the for loop block
6. discountedPrice is not defined, let is block scoped and discountedPrice is in the for loop block
7. the value of finalPrice, let is block scoped and finalPrice is in the function block 
8. [50,100,150]
9. i is not defined, let is blocked scoped and i is in the for loop block
10. discountedPrice is not defined, const is block scoped and discountedPrice is in the for loop block
11. prints 0, value of const variables cannot be changed
12. []
13. A. student.name B. student['Grad Year'] C. student.greeting() D. student['Favorite Teacher'].name E. student.courseLoad[0]
14. A. 32 B. 1 C. 3 D. 3null E. 4 F. 0 G. 3undefined H.NaN
15. A. true B. true. C. true D. false E. false F.true
16. "===" compares the data type of two variables and "==" does not
17. "How are you" is printed 
18. part1-question18.js
19. "[6,8,10]" A callback function is a function pushed in another function as an arguement, the array [1,2,3] and the function do something are inputs to the modifyArray function, each individual element of the array [1,2,3] and the function function(x) {return x * 2;} are the inputs to the doSomethingfunction. 1 is input into doSomething which inputs (1+2) to function(x), which returns 3 * 2 = 6 to doSomething which is returned and pushed to newArr. The same process happens for 2 3 and thus we get the result.  
20. part1-question20.js
21. "1432" is the output. 1 is printed first as it is the first command and is not controled by a setTimeout function. 4 is printed before 3 and 2 because it is not controled by setTimeOut, the functions controlled by setTimeOut are queued to be executed after the interpreter has executed other functions.3 would be printed before 2 as 2 is set to print after 1000ms, while 3 is set to print at 0ms.
