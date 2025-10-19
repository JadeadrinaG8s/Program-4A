# Program-4A
C module 4
EX NO-4)A) a C program to perform the basic left and right shift operation for 22 integer number.  
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C program to perform the basic left and right shift operation for 22 integer number.  
ALGORITHM:
1)define the datatype for the valuep.2)perform left shift and print the result.3)perform right shift and print the result.
PROGRAM:
```
#include <stdio.h>
int main() {
    unsigned int a=22 ;	/* 60 = 0011 1100 */  
      int c = 0; 
    c = a << 2;     /* 240 = 1111 0000 */
   printf("After Left Shift Operation value of a is:%d\n", c );
   c = a >> 2;     /* 15 = 0000 1111 */
   printf("After Right Shift Operation value of a is:%d\n", c );
}
```
OUTPUT:
<img width="1102" height="200" alt="Screenshot 2025-10-19 225457" src="https://github.com/user-attachments/assets/d96d1f1d-9359-4abd-adaf-1af4351c668e" />
RESULT:
Thus, a C program to perform the basic left and right shift operation for 22 integer number has been executed successfully.







