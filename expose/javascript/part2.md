1. The code outputs "3".
2. The code outputs "150".
3. The code outputs "150".
4. The function does not return anything because there is no line of code to print anything. 'console.log' is what prints.
5. There is an error at line 12 because the variable 'i' is out of scope, and is not declared outside of the for-loop so line 12 cannot access 'i'.
6. There is an error at line 13 because the variable 'discountedPrice' is out of scope, and is not declared outside of the for-loop so line 13 cannot access 'discountedPrice'.
7. The code outputs "150".
8. The function doesn't return anything because there is no code to print, similar to question 4.
9. There is an error because the variable 'i' is out of scope, and is not declared outside of the for-loop so line 11 cannot access 'i'.
10. The code outputs "3".
11. The function doesn't return anything because there is no code to print, similar to question 4 and 8.
12. A. student.name;
    B. student.["Grad Year"];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];
13. A. '32' was outputted because the '+' operator (when used with a string) converts a number to a string and concatenates them.
    B. 1 was outputted because the '-' operator does not concatenate, so the string '3' is converted to a number and the substraction is performed.
    C. 3 was outputted because in arithmetic operations, Javascript converts null to 0.
    D. '3null' was outputted because 'null' is convereted to a string, and then concatenated with the string '3'.
    E. 4 was outputted because true in Javascript is also the numeric value 1, and is converted for the arithmetic operation.
    F. 0 was outputted because false is converted to 0 and null is converted to 0 in numeric context.
    G. '3undefined' was outputted because undefined was converted into a string and converted with the string '3'.
    H. NaN was outputted because undefined cannot be converted to a number, so an arithmetic operation with undefined is NaN.
14. A. true was outputted because Javascript converts the string '2' into a number before comparison.
    B. false was outputted because Javascript uses lexicographic order when comparing strings, and '2' is lexicographically greater than '1'.
    C. true was outputted because the '==' operator converts both operands to the same type before the comparison is made. '2' is converetd to the numeric 2.
    D. false was outputted because '===' (strict equality) does not perform type conversion. Since both operands are of different types, the comparison is false.
    E. false was outputted because true is converted to numeric 1, and does not equal 2 so false is returned.
    F. true was outputted because 'Boolean(2)' is 'true', and '===' does not check without type conversion. Since both operands are true, the comparison is true.
15. '==' is equality, and can convert types. '===' is strict equality, and does not convert types.
17. There is no result because there is no console.log to output the results. However, if there was a 'console.log(newArr)' in the modifyArray function after the for loop and before the 'return newArr' line, the original array passed into modifyArray would be doubled.
19. The code outputs:
    1
    4
    3
    2
