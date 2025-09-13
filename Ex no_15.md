# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start.
2. Declare a array size value of type int.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5.  Initialize array elements.
6.  Replace all even elements to E
7.  End. 

## Program:
```
/*
Program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
Developed by: SRINIVASAN V
RegisterNumber:  212222043008
*/
```
```
#include <stdio.h>
int main() {
 int arr[100], n;
 scanf("%d", &n);
 for (int i = 0; i < n; i++) {
 scanf("%d", &arr[i]);
 }
 for (int i = 0; i < n; i++) {
 if (arr[i] % 2 == 0)
 printf("E ");
 else
 printf("%d ", arr[i]);
 }
 printf("\n");
 return 0;
}
```

## Output:

<img width="464" height="177" alt="438851394-0f4f1510-feb6-40fd-bc20-6175195f8b00" src="https://github.com/user-attachments/assets/a9f44de8-af86-4a1f-8a05-eae8f0840c7f" />


## Result:
Thus the program was executed and the output was verified successfully.
