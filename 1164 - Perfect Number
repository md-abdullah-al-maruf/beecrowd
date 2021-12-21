#include<stdio.h>
int main()
{
    int x,y,i,j,s=0;
    scanf("%d",&y);
    for(j=1; j<=y; j++) {
        scanf("%d",&x);
        for(i=1; i<x; i++) {
            if(x%i==0) {
                s=s+i;
            }
        }
        if(s==x) {
            printf("%d eh perfeito\n",x);
        }
        else {
            printf("%d nao eh perfeito\n",x);
        }
        s=0;
        x=0;
    }
    return 0;
}
