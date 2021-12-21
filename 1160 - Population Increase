#include<stdio.h>
int main()
{
    int a,b,t,m=0;
    float c,d,e,f;
    scanf("%d",&t);
    while(t--)
    {
        a=0,b=0,m=0,e=0.0,f=0.0;
        scanf("%d%d%f%f",&a,&b,&c,&d);

            while(b>=a)
            {
                e=(a*(c/100));
                a=a+(int)e;
                f=(b*(d/100));
                b=b+(int)f;
                m++;
                if(m>100)
                {
                    break;
                }
            }
            if(m<101)
            {
                printf("%d anos.\n",m);
            }
            else
            {
                printf("Mais de 1 seculo.\n");
            }
    }
    return 0;
}
