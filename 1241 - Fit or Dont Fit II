#include<stdio.h>
#include<string.h>
int main()
{
    int i,j,k=1,m,n,p;
    char a[1001],b[1001],c[1001];
    scanf("%d",&m);
    while(m--)
    {
        scanf("%s %s",&a,&b);
        n=strlen(a);
        p=strlen(b);
        if(n<p){
            printf("nao encaixa\n");
        }
        else{
            for(i=(n-p),j=0;i<n;i++,j++){
                c[j]=a[i];
            }
            c[j]='\0';
            k=strcmp(c,b);
            if(k==0){
                printf("encaixa\n");
            }
            else{
                printf("nao encaixa\n");
            }
        }
    }
    return 0;
}

