# 25331A05E8-simple-and-compound-interest
#include <stdio.h>
#include <math.h>   
 
int main()
{
    float principal, rate, time;
    float simpleInterest, compoundInterest;
    printf("25331A05E8");
    printf("Enter Principal amount: ");
    scanf("%f", &principal);
 
    printf("Enter Rate of Interest: ");
    scanf("%f", &rate);
 
    printf("Enter Time (in years): ");
    scanf("%f", &time);
 
    simpleInterest = (principal * rate * time) / 100;
 
    compoundInterest = principal * pow((1 + rate / 100), time) - principal;

    printf("\nSimple Interest = %.2f", simpleInterest);
    printf("\nCompound Interest = %.2f", compoundInterest);
 
    return 0;
}
 
