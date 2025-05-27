Skip to content
Navigation Menu
anu-varshini11
DS_Module14

Type / to search
Code
Pull requests
Actions
Projects
Security
Insights
Files
Go to file
t
Ex10-Applications-of-Queue-FCFS.md
Ex6-Circular-queue..md
Ex7-Priority-Queue.md
Ex8-Deque.md
Ex9-Applications-of-Queue---SJF.md
DS_Module14
/Ex7-Priority-Queue.md
anu-varshini11
anu-varshini11
Update Ex7-Priority-Queue.md
abad084
 · 
last month
DS_Module14
/Ex7-Priority-Queue.md

Preview

Code

Blame
40 lines (35 loc) · 1022 Bytes
Ex7 Priority Queue
DATE:
AIM:
To formulate the C code to display the elements of the priority queue after insertion and deletion operation.

Algorithm
Start
Define a function printArray() that takes an array and its size as parameters.
Loop through the array from index 0 to size-1.
Print each element of the array during the loop.
After printing all elements, print a newline for formatting.
End
Program:
/*
Program to o display the elements of the priority queue after insertion and deletion operation
Developed by: HANUMANTH RAO 
RegisterNumber: 2122222240016
*/
/*#include <stdio.h> 
int size = 0; 
*/ 
void printArray(int array[], int size) 
{ 
int i; 
for(i=0;i<size;i++) 
{ 
printf("%d ",array[i]); 
} 
printf("\n"); 
}
Output:
image

Result:
Thus, the C program to display the elements of the priority queue after insertion and deletion operation is implemented successfully

DS_Module14/Ex7-Priority-Queue.md at main · anu-varshini11/DS_Module14
