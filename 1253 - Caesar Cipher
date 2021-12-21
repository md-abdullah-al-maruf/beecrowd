#include<stdio.h>
int main()
{
    int n,i,j,b,c,d,e;
    char a[1000];
    scanf("%d",&n);
    getchar();
    while(n--)
    {
        scanf("%s",&a);
        c=strlen(a);
        scanf("%d",&b);
        for(i=0; i<c; i++)
        {
            d=a[i]-b;
            if(d<65)
            {
                e=91-(65-d);
                a[i]=e;
            }
            else
            {
                a[i]=d;
            }
        }
        puts(a);
    }
    return 0;
}
