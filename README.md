#include<stdio.h>
#include<conio.h>
void main()
{ int number;
  clrscr();
  printf("Enter your number:");
  scanf("%d",&number);
  if(number>200)
  {
  printf("Oops!\nSorry housefull !");
  }
  else
  {
  printf("You are welcome !");
  }
  getch();
  }
