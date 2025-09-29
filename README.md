# Positive-and-Negative
Write a program in C to display positive or negative number?

#include <stdio.h>

int main() {

    int a;
    
    printf("enter your value:");
    
    scanf("%d",&a);
    
    if(a>0)
    
    {
        printf("your extended value is +ve");
    }
    
    else
    
    {
        printf("your extended value is -ve");
    }

    return 0;
}
