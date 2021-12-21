#include<stdio.h>
int main()
{
    int a,b,i,j,x,y=1;
    scanf("%d%d",&a,&b);
    if((a>1&&a<20)&&a<b&&(b>a&&b<100000))
    {
        if(b%3!=0)
        {
            x=((b/3)+1);
        }
        else
        {
            x=(b/3);
        }
        for(i=1; i<=x; i++)
        {
            for(j=1; j<=a; j++)
            {
                if(y<=b)
                {
                    if(j<a)
                    {
                        printf("%d ",y);
                    }
                    else
                    {
                        printf("%d\n",y);
                    }
                    y++;
                }
                else
                {
                    break;
                }
            }
        }
    }
    return 0;
}
