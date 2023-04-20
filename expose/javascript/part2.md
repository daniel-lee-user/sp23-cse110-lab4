# Part 2 Answers

1. Line 12 will return 3. This is because the for loop runs 3 times because there are three prices in the price list. The final value of i is three, and because i is declared using the var keyword it has no scope, so it is accessible outside the for loop.

2. Line 13 will return the last discounted price (the last price in the list, after it has been discounted). That is equivalent to 300*0.5, or 150.

3. Line 14 will return the final price of the last price in the list, which is the same as the discounted price after it has been multiplied by 100 and divided by 100. This is equal to 150.

4. This function will return a list containing the prices given after the discount given has been applied to them. In this case, the list returned is [50, 100, 150]

5. Line 12 will cause an error, because i is not defined in line 12's scope. 

6. Line 13 will cause an error, because discountedPrice is not defined in line 12's scope. 

7. Line 14 will return the final price of the last price in the list, which is the same as the discounted price after it has been multiplied by 100 and divided by 100. This is equal to 150.

8. This function will return a list containing the prices given after the discount given has been applied to them. In this case, the list returned is [50, 100, 150]

9. Line 11 will cause an error, because i is not defined in line 12's scope. 

10. Line 12 will return 3, because that is the length of the prices array, which has been set to the constant length variable. 

11. This function will return a list containing the prices given after the discount given has been applied to them. In this case, the list returned is [50, 100, 150]

12. Question 12
    1.  `student.name;`
    2.  `student['Grad Year'];`
    3.  `student.greeting();`
    4.  `student['Favorite Teacher'].name;`
    5.  `student.courseLoad[0];`

13. Question 13
    1. '32' is the output because integers map to their exact string representation and then the string 2 is concatenated to the string 3.
    2. 1 is the output because you cannot subtract two strings but you can subtract two integers, so 2 was subtracted from 3 and 3 was converted into an integer.
    3. 3 is the output because null is converted into 0 when added to a number
    4. 3null is the output because null is converted into a string 'null' and then concatenated to the string '3'.
    5. 4 is the output because true is converted into 1 when added to a number
    6. 0 is the output because false is converted to 0 when added to null, which is also converted to 0.
    7. 3undefined is the output because undefined maps to the string undefined.
    8. NaN is the output because undefined is converted to NaN as a number, and when NaN is involved in a mathematical operation usually the answer is NaN.

14. Question 14
    1. true is the output because when comparing two different types of variables using > or < js converts both values to integers, and 2 is greater than 1.
    2. false is the output because when comparing 2 strings, js compares them lexicographically. Since 2 is greater than 1 lexicographically, '2' < '12' is false.
    3. true is the output because when comparing two different types of variables using == js converts both values to integers, and 2 == 2
    4. false because === checks equality without type conversion, and 2 is not the same type as '2' (int vs string)
    5. false because after type conversion true turns into 1 but 1 does not equal 2.
    6. true because 2 is a number that is converted to true under the boolean conversion rules, and true === true.
15. == compares the two values after converting the types of the variables to the same types, while === checks for equality without converting types of the variables.

16. See part2-question16.js


17. The array [2, 4, 6] will be returned. First, the array [1, 2, 3] is passed in as the input array, while doSomething, which takes in a number and doubles and returns the number, is passed in as the callback function. Then, the callback function is run on each element of the input array, and the result of the callback function is pushed into a new array. Essentially, each element of the array is doubled and the the results are combined into an array and returned.

18. See part2-question18.js

19. The output is: 1 4 3 2