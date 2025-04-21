# college-codes
for the practice
#include <stdio.h>
#include <math.h>
int factorial(int num);
int Strong_Number(int num);
int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);

    if (Strong_Number(number)) 
    {
        printf("%d is a Strong Number\n", number);
    } 
    else 
    {
        printf("%d is not a Strong Number\n", number);
    }

    return 0;
}
