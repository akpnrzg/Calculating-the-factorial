//# Calculating-the-factorial
//Calculating the factorial of the entered number
#include <stdio.h>
#include <conio.h>

int main(void)
{
    int i,num;float fac=1;
    printf("Enter the number to be factored: ");
    scanf("%d",&num);
    for(i=1;i<=num;i++)
        fac*=i;
    printf("\nResult: %4.2f\n",fac);
    return 0;

}
