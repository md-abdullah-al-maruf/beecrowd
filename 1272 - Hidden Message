#include <stdio.h>
int main()
{
    int a,b,c,d,i,j=0,k=0,sum=0;
    char x[100],y[100];
    scanf("%d",&a);
    getchar();
    while(a--)
    {
        gets(x);
        j=0;
        b=strlen(x);
        for(i=0;i<b;i++){
            if(((x[i]!=' ')&&(x[i-1]==' '))||((i==0&&x[i]!=' '))){
                y[j]=x[i];
                j++;
            }
        }
        y[j]='\0';
        puts(y);
    }
    return 0;
}
