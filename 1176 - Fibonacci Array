#include<stdio.h>
int main()
{
    long long int a=1,b=1,c;
    int d,x,i,j,k;
    scanf("%d",&x);
    int y[x];
    for(j=0; j<x; j++)
    {
        scanf("%d",&y[j]);
    }
    for(k=0; k<x; k++)
    {
        d=y[k];
        if(d==0)
        {
            c=0;
        }
        else if(d==1)
        {
            c=1;
        }
        else if(d==2)
        {
            c=1;
        }
        else if(d>1)
        {
            for(i=3; i<=d; i++)
            {
                c=a+b;
                a=b;
                b=c;
            }
        }
        printf("Fib(%d) = %lld\n",d,c);
        a=1;
        b=1;
        c=0;
    }
    return 0;
}
