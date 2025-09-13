# EX 14 C program to delete first element in an array.
## DATE:
## AIM:
To write a C program to delete first element in an array.

## Algorithm
1.Start.
2. Define a variables i,j,a.
3. Read the value using scanf.
4. Ask the user to make an input
5. Print out the answer
6. End.

## Program:
```
/*
Program to delete first element in an array.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008  
*/
```
```
#include<stdio.h> 
int main()
{
int i,n,a[10];
scanf("%d",&n); 
for(i=0;i<n;i++)
{
scanf("%d",&a[i]);
}
for(i=1;i<n;i++) 
printf("%d ",a[i]);
}
```
## Output:

<img width="780" height="191" alt="438849946-f6af2d03-16bb-4ede-bfe2-2c89d3e2b538" src="https://github.com/user-attachments/assets/8019d702-db5a-442c-b04c-4ede7ee78791" />


## Result:
Thus the program was executed and the output was verified successfully.
