#include<stdio.h>
int main(void)
{
int num;
printf("Enter your marks");
scanf("%d" , "&num);
printf("You entered %d" , num);
if (num>100)
printf("Wrong data given");
else if(num>=85)
{
printf("You got A grade");
}
else if(num>=70)
{
printf("You got B grade");
}
else if(num>=55)
{
printf("You got C grade");
}
else if(num>=40)
{
printf("You got D grade");
}
else if(num<40)
{
printf("You got F grade");
}
return 0;
}
