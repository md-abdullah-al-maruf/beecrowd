#include <stdio.h>
int main()
{
    int a,i,j;
    char b;
    float x[12][12],sum=0,avr=0;
    scanf("%d",&a);
    scanf(" %c",&b);
    for(i=0;i<12;i++){
        for(j=0;j<12;j++){
            scanf("%f",&x[i][j]);
        }
    }

    for(i=0;i<12;i++){
        sum=sum+x[i][a];
    }
    if(b=='S'){
        printf("%.1f\n",sum);
    }
    else if(b=='M'){
        avr=(sum/12);
        printf("%.1f\n",avr);
    }

    return 0;
}

