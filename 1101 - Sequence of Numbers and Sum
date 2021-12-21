#include<stdio.h>
int main()
{
    int a,b,i,sum=0;
    while(1)
    {
        scanf("%d %d",&a,&b);
        if(a>0&&b>0)
        {
            if(a>b)
            {
                for(i=b; i<=a; i++)
                {
                    sum=sum+i;
                    printf("%d ",i);
                }
            }
            else if(a<b)
            {
                for(i=a; i<=b; i++)
                {
                    sum=sum+i;
                    printf("%d ",i);
                }
            }
            printf("Sum=%d\n",sum);
            sum=0;
        }
        else
        {
            break;
        }
    }
    return 0;
}
