# Professional-C
My evolution through learning the C language in real time

#include <stdio.h>
#include <stdlib.h>
int main(void) {
 puts("hello, world!");
 return EXIT_SUCCESS;
}


2nd script in C

#include<stdio.h> //header files
#include<conio.h>
void main()
{   //initialize the local variables.
    int l =5, b=10, ar, pr;
    printf("Length & Breadth of the rectangle is: %d & %d",l, b);
    ar = l * b; // calculate perimeter of rectangle.
    pr = 2 * (l+b);// calculate perimeter of rectangle.
    printf("\n Area of Rectangle is: %d",ar);
    printf("\n Perimeter of Rectangle is: %d", pr);
}
