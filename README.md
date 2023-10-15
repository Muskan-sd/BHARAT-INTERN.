# BHARAT-INTERN.
TASK FOR INTERNSHIP
Task-1 (CALCULATOR APP)

#include <stdio.h>

int main()
{
int multiplication,substraction,addition,division,choice,num1,num2,total,diff,product,quotient;

printf("enter a choice\n\n1.addition\n2.subtraction\n3.multiplication\n4.division\n");
scanf("%d",&choice);
if (choice ==1)
{
printf("Enter a number ");
scanf("%d",&num1); 
printf("Enter another number ");
scanf("%d",&num2);

total= num1+num2;
printf("The sum is %d", total);
}
else if(choice=2)
{
printf("Enter a number ");
scanf("%d", &num1);
printf("Enter another number ");
scanf("%d",&num2);

diff=num1-num2; 
printf("The difference is %d", diff);
}
else if(choice==3)
{

printf("Enter a number ");
scanf("%d", &num1);
printf("Enter another number ");
scanf("%d",&num2);

product=num1*num2; 
printf("The product is %d", product);
}
else if(choice=4)
{
printf("Enter a number ");
scanf("%d", &num1);
printf("Enter another number ");
scanf("%d",&num2);

remainder=num1/num2; 
printf("The remainder is %d", quotient);
}

return 0;
}


