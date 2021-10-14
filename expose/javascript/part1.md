1. 20
2. 20
3. 20
4. ReferenceError. 
   
   **Reason:** The 'result' variable has been declared in the if{} blocks and line 13 is outside the scope of the variable becuase the let keyword restricts scope to the blocks in which the variable is declared.
5. TypeError. 
   
   **Reason:** The variable 'result' is declared as a const which means its value cannot be changed from the initially defined value, in this case 0. However in line 9 we are trying to change the value to the sum of num1 and num2, hence the error.
6. TypeError. 
   
   **Reason:** The runtime does not reach line 13 so technically nothing is printed. This is because the error is encountered on line 9.
7. 