#include<stdio.h>
int main()
{
    int a,b,c,i,j,sum=0;
    scanf("%d",&c);
    for(j=0; j<c; j++)
    {
        scanf("%d %d",&a,&b);
        if(a<b)
        {
            for(i=a+1; i<b; i++)
            {
                if(i%2!=0)
                {
                    sum=sum+i;
                }
            }
        }
        else if(a>b)
        {
            for(i=a-1; i>b; i--)
            {
                if(i%2!=0)
                {
                    sum=sum+i;
                }
            }
        }
        printf("%d\n",sum);
        sum=0;
    }
    return 0;
}
