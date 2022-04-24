#include <stdio.h>
#include <math.h>
int main()
{
    float numb1, numb2;  
    
    printf("Enter 2 numbers seperated by space: ");
    scanf("%f %f", &numb1, &numb2);    
    float sum, sub, product, quotient;    
    sum = numb1 + numb2;
    sub = numb1 - numb2;
    product = numb1 * numb2;
    quotient = numb1 / numb2;
    
    int choice;
    
    printf("What do you want to do?\n1) Add\n2) Subtract\n3) Multiply\n4) Divide\n");
    
    scanf("%d", &choice);
    
    if (choice == 1) {
        printf("\nSum of %.2f and %.2f = %.2f", numb1, numb2, sum);
    }
    else if (choice == 2) {
        printf("\nDifference of %.2f and %.2f = %.2f", numb1, numb2, sub);
    }
    else if (choice == 3) {
        printf("\nProduct of %.2f and %.2f = %.2f", numb1, numb2, product);
    }
    else if (choice == 4) {
        printf("\nQuotient of %.2f divided by %.2f = %.2f", numb1, numb2, quotient);
    }
    else printf("Wrong Choice");
    
    return 0;
}	