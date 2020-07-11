


#include<stdio.h>
void main()
{
    int i;
    for(i=1;i<=100;i++)
    {
        if(i%3==0&&i%15!=0)
          {

            printf("fizz");
            printf(" ");
          }
           else if(i%5==0&&i%15!=0)
            {
                printf("buzz");
                printf(" ");
            }
              else if(i%15==0)
              {

                printf("fizz buzz");
                printf(" ");
              }
                 else
               {
                   printf("%d",i);
                   printf(" ");
               }


    }
}
