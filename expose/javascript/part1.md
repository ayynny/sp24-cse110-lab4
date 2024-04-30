1. values added:  20
2. final result:  20
3. values added:  20
4. The code returns an error because the 'let' keyword only allows the variable to be accessed in the block it was defined in. In this case the block is the if-statement from lines 3 to 9.
5. The code returns an error because 'const' does not allowed the variable to be reassigned a new value. In this case, 'result' is declared with the value 0, but attempts to reassign it with num1 + num2, and 'const' prevents this reassignment.
6. The code returns an error because we cannot access 'result' because result is defined in the block above it. 'const' acts similarly to 'let' where you can only access the variable in the same block where it was declared.