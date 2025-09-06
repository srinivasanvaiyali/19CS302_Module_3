# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1. Start.
2. Declare a integer variable
3. Define a function named dectobin.
4. Return the integer.
5. Read the value using scanf.
6.Convert decimal to binary value. 
7. Print the dectobin 
8. End.  

## Program:
```
/*
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008
*/
```
```
#include<stdio.h>
Int dectobin(int d){
int bin =0,base=1,rem; 
while(d>0)
{
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10;
}
printf(" = %d in binary",bin); 
return 0;
}
int main()
{
int dec; 
scanf("%d",&dec);
printf("%d in decimal",dec); 
dectobin(dec);
return 0;
```

## Output:
<img width="769" height="282" alt="438846078-29f4d508-d225-4e40-a8be-16979da6610b" src="https://github.com/user-attachments/assets/5e6f719f-80d9-4154-ac00-a50652adda3c" />



## Result:
Thus the program was executed and the output was verified successfully.
