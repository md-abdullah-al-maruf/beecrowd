#include <stdio.h>
#include <string.h>
int main()
{
    int a,b;
    long long int c,d,e;
    char p1[100],par[10],p2[100],impar[10];
    scanf("%d",&a);
    for(b=1; b<=a; b++)
    {
        scanf("%s %s %s %s",p1,par,p2,impar);
        scanf("%lld%lld",&c,&d);
        e=c+d;
        if(par[0]=='P')
        {
            if(e%2==0) printf("%s\n", p1);
            else printf("%s\n", p2);
        }
        else
        {
            if(e%2==0) printf("%s\n", p2);
            else printf("%s\n", p1);
        }
    }
    return 0;
}
