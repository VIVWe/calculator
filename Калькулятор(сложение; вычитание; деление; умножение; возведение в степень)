#include <stdio.h>
#include <math.h>
 
 
int main()
    {
    
        int checkvar;
        
        do
        {
            printf("What do you want to choose?\n\n 1 - Addition\n 2 - Subtraction\n 3 - Multiplication\n 4 - Division\n 5 - Exponentiation\n 0 - Exit\n\n");
            scanf("%d",&checkvar);
            printf("\n");
            
            if(checkvar==1)
            {
                float num1,num2,ans;
                printf("You have chosen: Addition.\n");
                printf("Enter first number: ");
                scanf("%g", &num1);
                printf("Enter second number: ");
                scanf("%g", &num2);
                ans = num1+num2;
                printf("\n%g + %g = %g \n\n", num1,num2,ans);
            }
            else
            {
                if(checkvar==2)
                {
                    float num1, num2, ans;
                    printf("You have chosen: Subtraction.\n");
                    printf("Enter first number: ");
                    scanf("%g", &num1);
                    printf("Enter second number: ");
                    scanf("%g", &num2);
                    ans = num1-num2;
                    printf("\n%g - %g = %g \n\n", num1,num2,ans);
                }
                else
                {
                    if(checkvar==3)
                    {
                        float num1, num2, ans;
                        printf("You have chosen: Multiplication.\n");
                        printf("Enter first number: ");
                        scanf("%g", &num1);
                        printf("Enter second number: ");
                        scanf("%g", &num2);
                        ans = num1*num2;
                        printf("\n%g * %g = %g \n\n", num1,num2,ans);
                    }
                    else
                    {
                        if(checkvar==4)
                        {
                            float num1, num2, ans;
                            printf("You have chosen: Division.\n");
                            printf("Enter first number: ");
                            scanf("%g", &num1);
                            printf("Enter second number: ");
                            scanf("%g", &num2);
                            if(num2==0)
                
                                printf("\nCannot divide by zero!\n\n");
                
                            else
                            {
                                ans = num1/num2;
                                printf("\n%g / %g = %g \n\n", num1,num2,ans);
                            }
                        }
                        else
                        {
                            if(checkvar==5)
                            {
                                float num1, num2, ans;
                                printf("You have chosen: Exponentiation.\n");
                                printf("Enter first number: ");
                                scanf("%g", &num1);
                                printf("Enter second number: ");
                                scanf("%g", &num2);
                                ans = pow(num1, num2);
                                printf("\n%g^%g = %g \n\n", num1,num2,ans);
 
                            }
                            else
                            {
                                if(checkvar!=0)
                                    printf("Wrong number!\n\n");
                            }
                        }
                    }
                }
            }
        }
        while(checkvar!=0);
        printf("Exiting...\n");
        
        return 0;
    }
