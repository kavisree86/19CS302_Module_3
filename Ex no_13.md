# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
Start.
Define a variables i,j,n,a.
Write program to find n x n matrix.
Read the value using scanf.
Ask the user to make an input
Print out the answer.
End.

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: 
RegisterNumber:  
*/
```
```

#include<stdio.h> 
int main()
{
int i,j,n,a[10][10];
scanf("%d",&n); 
for(i=0;i<n;i++)
{
for(j=0;j<n;j++)
{
scanf("%d",&a[i][j]);
}
}for(i=0;i<n;i++)
{
for(j=0;j<=n;j++)
{
if(a[i][j]%2==1)
{
printf("a[%d][%d] is %d \n",i,j,a[i][j]);
}
}
printf("\n");
}
return 0;
}
```

## output:
<img width="796" height="572" alt="image" src="https://github.com/user-attachments/assets/4539d964-1fd8-4b1d-8ac9-15018cdcc127" />


## Result:
Thus the program was executed and the output was verified successfully.
