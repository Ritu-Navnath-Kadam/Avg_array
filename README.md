# Avg_array
#include<stdio.h>
void main()
{

float avg,sum=0;
int n;
printf("Enter array size. ");
scanf("%d",&n);
int arr[n];
printf("Enter array element ");

for(int I=0;I<n;I++)
{
scanf("%d",&arr[I]);
}

printf("Array is given below\n\n");
for(int I=0;I<n;I++)
{
printf(" %d ",arr[I]);
sum=sum+arr[I];
}
avg=sum/n;
printf("\n\n Average = %f",avg);


}
