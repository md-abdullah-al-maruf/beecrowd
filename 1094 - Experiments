#include<stdio.h>
int main()
{
    int a=0,i,c=0,r=0,s=0,n=0;
    float cp=0,rp=0,sp=0,total=0.0;
    char b;
    scanf("%d",&a);
    for(i=0;i<a;i++){
        scanf("%d",&n);
        if(n>=1&&n<=15){
        scanf(" %c",&b);
        if(b=='C'){
             c=c+n;
        }
        else if(b=='R'){
            r=r+n;
        }
        else if(b=='S'){
            s=s+n;
        }
        }
        else{
            return 0;
        }
    }
    total=c+r+s;
    cp=((c/total)*100.00);
    rp=((r/total)*100.00);
    sp=(( s/total)*100.00);

    printf("Total: %.0f cobaias\n",total);
    printf("Total de coelhos: %d\n",c);
    printf("Total de ratos: %d\n",r);
    printf("Total de sapos: %d\n",s);
    printf("Percentual de coelhos: %.2f %%\n",cp);
    printf("Percentual de ratos: %.2f %%\n",rp);
    printf("Percentual de sapos: %.2f %%\n",sp);
    return 0;
}
