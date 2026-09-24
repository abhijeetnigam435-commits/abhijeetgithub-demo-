#include<stdio.h>
#include<conio.h>
void main()
{
int i,a,b,x;
clrscr();
printf("enter any two number");
scanf(:%d%d",&a,&b);
printf("press 1 for sum press 2 for sub press 3 for product press 4 for divide");
scanf("%d",&i);
switch(i)
{
case 1:
x=a+b;
printf("sum of two number is %d",x);
break;
case 2:
x=a-b;
printf("sub of two number is %d",);
break;
case 3:
x=a*b;
printf("product of two number is %d",x);
break:
case 4:
x=a\b;
printf("divide of two number is %d",x);
break;
default:
printf("invalid input");
}
getch();
}
