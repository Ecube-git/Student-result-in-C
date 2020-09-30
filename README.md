# Student-result-in-C


#include<stdio.h>
#include<conio.h>
void main()
{
clrscr();
int n,i,a,b,c,sum;
printf("\n Enter your Marks\n\n 1. Maths\t");
scanf("%d",&a);
printf(" 2. Physics\t");
scanf("%d",&b);
printf(" 3. Chemistry\t");
scanf("%d",&c);

sum = a+b+c;

if(sum >= 180)
{
printf("\n Student is eligible to get admission.");
}
else
{
printf("Student is not eligible to get admission.");
}
getch();
}

