#include<stdio.h>
int main()
{
    float a,b,avr;
    int x;
    a:
    scanf("%f",&a);
    if(a<0||a>10){
        printf("nota invalida\n");
        goto a;
    }
    else{
        b:
        scanf("%f",&b);
    if(b<0||b>10){
        printf("nota invalida\n");
        goto b;
    }
    else{
        avr=(a+b)/2;
        printf("media = %.2f\n",avr);
    }
    x:
    scanf("%d",&x);
    printf("novo calculo (1-sim 2-nao)\n");
    if(x==1){
        goto a;
    }
    else if(x==2){
        return 0;
    }
    else{
        goto x;
    }
    }
    return 0;
}
