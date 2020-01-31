#include<stdio.h>
 
int main()
{
 	int i, j, rows, columns, a[10][10], Sum = 0;
  
 	printf("Enter Number of rows and columns:");
 	scanf("%d %d", &i, &j);
 
 	printf(" Enter the Matrix Elements");
 	for(rows = 0; rows < i; rows++)
  	{
   		for(columns = 0;columns < j;columns++)
    	{
      		scanf("%d", &a[rows][columns]);
    	}
  	}
   	  
 	for(rows = 0; rows < i; rows++)
  	{
   		Sum = Sum + a[rows][rows];
  	}
 
 	printf(" The Sum of Diagonal Elements of a Matrix =  %d", Sum );

 	return 0;
}
output//
Enter umber of rows and columns:3 3
Enter the matrix elements: 1 2 3
1 2 3
1 2 3
the sum of diagonal elements of the matrix=6
