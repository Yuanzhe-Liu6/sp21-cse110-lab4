## Part 1A
1. value added: 20
2. final result: 20
3. value added: 20
4. error, it shows result is not yet defined. This is because the variable is defined with keyword let, so it does not exist after the scope it defined in.
5. error, we cannot assign new value to const defined variables.
6. error, same reason as line 9. we cannot assign new value to const defined variables.

## Part 1B
1. 3 is printed. we defined i using var keyword, so it is act like a global variable, so i still exist after the for loop. And we have 3 values in prices, so i is incremented to 3.
2. 150 is printed. The last value processed in the prices is 300, and the discount is 0.5, so we have last discountedPrice 150. Also discountedPrice is defined using var keyword, so it still exist after the loop.
3. 150 is printed. finalPrice is the round up value for discountedPrice, we round 150 to integer, we get 150.
4. the function reture a array with 3 values.[50, 100, 150]. This function calculate the discounted price with provided prices and discount. This case we have discount 0.5. which is the half prices as before, so we get a array with all values halved.
5. error, we defined i using keywork let, so it only exist in the for loop scope;
6. error, same reason as 5, discountedPrice is defined using let, and only exist in the for loop.
7. 150 is printed, finalPrice is defined at the beginning of the function, and it is the same scope with the print statement, so finalPrice is printed successfully.
8. this funtion return [50, 100, 150], same reason from question 4, chaning the variable defining keyword from var to let did not affect the funtionality of this function.
9. error, i is defined using let, so it only exist in for loop.
10. 3 is printed. The length of array prices is 3.
11. This function will return [50, 100, 150], even we changed the variable define keyword to const, but we never try to modify the const variables after initialize them, so there is no error happened.
12. 
    A. student.name\
    B. student['Grad Year']\
    C. student.greeting()\
    D. student['Favorite Teacher'].name\
    E. student.courseLoad[0]
13. 
    A. '32', since integers map to their exact string representation.\
    B 1, since string map to their exact integer representation.\
    C. 3, since null maps to 0\
    D. '3null', null is convert to string, and concanation is performed.\
    E. 4, since true maps to 1\
    F. 0, since both false and null maps to 1\
    G. '3undefined', undefined is convert to string ,and concanation is performed.\
    H. NaN, Since undefined maps to NaN
14. 
    A. true, since string map to their exact int representation.\
    B. false, when we compare two string, we start with the first character, and since 2 > 1, '2' < '12' is false.\
    C. true, since integers map to their exact string representaion.\
    D. false, '===' check both value and type, since 2 and '2' are different type, we get false.\
    E. false, true maps to 1, 1 != 2, so we get false.\
    F. true, Boolean always return true if the input is not 0, so Boolean(2) return true, and ture = true and they are same type, so we get true.
15. '==' checks for the value only, '===' check for both value and type. For example 2 == '2' is true since they have same value, but 2 === '2' is false because they are different type.
16. see this file [here](part1b-question16.js);
17. The function call will return [2, 4, 6]. In the function modifyArray we pass in an array and a function, then we simply modify the each value in the array using the function. In this case, we pass in function doSomething, which double the value. So after the function call modifyArray([1,2,3], doSomething), every value in the array is doubled. So we get [2, 4, 6] as the return array.
18. see this file [here](part1b-question18.js);
19. output: \
    1\
    4\
    3\
    2

