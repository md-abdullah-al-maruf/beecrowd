#include<stdio.h>
int main()
{
    int a,b,c=0,d,Inter=0,Gremio=0,Empates=0,grenais=0;

    while(c!=2){
        scanf("%d%d",&a,&b);
        printf("Novo grenal (1-sim 2-nao)\n");
        if(a>b){
            Inter++;
        }
        else if(a<b){
            Gremio++;
        }
        else if(a==b){
            Empates++;
        }
        grenais++;
        scanf("%d",&c);
    }
    printf("%d grenais\n",grenais);
    printf("Inter:%d\n",Inter);
    printf("Gremio:%d\n",Gremio);
    printf("Empates:%d\n",Empates);
    if(Inter>Gremio){
        printf("Inter venceu mais\n");
    }
    else if(Inter<Gremio){
        printf("Gremio venceu mais\n");
    }
    else if(Inter==Gremio){
        printf("Nao houve vencedor\n");
    }
    return 0;
}
