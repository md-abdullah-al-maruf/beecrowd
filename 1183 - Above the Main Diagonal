#include <stdio.h>
int main()
{
    int i,j,k=0;
    char b;
    float x[12][12],sum=0,avr=0;
    scanf("%c",&b);
    for(i=0;i<12;i++){
        for(j=0;j<12;j++){
            scanf("%f",&x[i][j]);
        }
    }
    for(i=0;i<12;i++){
        for(j=0;j<12;j++){
            if(j>i){
                sum=sum+x[i][j];
                k++;
            }
        }
    }
    if(b=='S'){
        printf("%.1f\n",sum);
    }
    else if(b=='M'){
        avr=(sum/k);
        printf("%.1f\n",avr);
    }

    return 0;
}


