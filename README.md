C-Coding-Lab
============

One of the labs i did during C
#include <stdio.h>

int main(void)
{
	double sum=0.0, number=0, average=0, smallest=0, largest=0, range=0;
	int count=0, limit=0;
	
	printf("Please enter the number of data points going to be used: ");	/*Were the data points are entered*/
	scanf("%ld", &limit);

	

	printf("The number of data points entered was %d.\n", limit);	/*echo*/

	while (count <limit)
	{
		printf("Enter data point %d: ", count);	/*Were the values of each data point is entered*/
		scanf("%lf", &number);
		
		sum=sum + number;

		++count;
		printf("The sum of the numbers are %f.\n", sum);      /*Shows us the sum and average step by step as the numbers are added*/

		average = sum / count;

		printf("And the average of the entered numbers are %f.\n", average);

		if (count == 1)
		
			number = smallest;
			number = largest;
		
		else if (count != 1 && number < smallest) 
			number = smallest;
			number = largest;
			
			printf("smallest number was %d.", count==1);
