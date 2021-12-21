#include<stdio.h>

int main()
{
    float a,b,c,d,e,f;
    scanf("%f",&a);
    if(a>=0 && a<=2000) {
        printf("Isento\n");
    }
    else if(a>2000 && a<=3000) {
        b=a-2000;
        c=b*8/100;
        printf("R$ %0.2f\n",c);
    }
    else if(a>3000 && a<=4500) {
        b=a-2000;
        c=b-1000;
        d=((1000*8/100)+(c*18/100));
        printf("R$ %0.2f\n",d);
    }
    else if(a>4500) {
        b=a-2000;
        c=b-1000;
        d=a-4500;
        e=c-d;
        if(e<0) {
            e=e*-1;
            f=((1000*8/100)+(e*18/100)+(d*28/100));
            printf("R$ %0.2f\n",f);
        }
        else {
            f=((1000*8/100)+(e*18/100)+(d*28/100));
            printf("R$ %0.2f\n",f);
        }
    }
    return 0;
}
