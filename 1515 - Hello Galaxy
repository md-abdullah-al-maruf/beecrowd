#include<stdio.h>
int main()
{
    int n;
    while(scanf("%d",&n)){
        if(n==0){
            break;
        }
        int i,j,y,m,min=1000000;
        struct a{
            char b[100];
        }c[n];
        for(i=0;i<n;i++){
            scanf("%s %d %d",&c[i].b,&y,&m);
            if((y-m)<min){
                min=y-m;
                j=i;
            }
        }
        printf("%s\n",c[j].b);
    }
    return 0;
}
