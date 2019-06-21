# Basic
Find area and circumference of a circle.
#include<stdio.h>
#include<conio.h>
void main()
{
float r,area,circum;
clrscr();
printf("Enter the radius:");
scanf("%f",&r);
area=3.14*r*r;
circum=2*3.14*r;
printf("The area is %f",area);
printf("\nThe circumference is %f",circum);
getch();
}
