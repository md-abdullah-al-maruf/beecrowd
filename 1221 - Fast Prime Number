#include<stdio.h>
int main()
{
    int a,b,i,j=0;
    scanf("%d",&b);
    while(b--)
    {
        j=0;
        scanf("%d",&a);
        for(i=2; (i*i)<=a; i++)
        {
            if(a%i==0)
            {
                printf("Not Prime\n");
                j++;
                break;
            }
        }
        if(j==0)
        {
            printf("Prime\n");
        }
    }
    return 0;
}

