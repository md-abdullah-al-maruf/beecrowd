#include<stdio.h>
int main()
{
    char a[100];
    int i,j,k,c=0,s=0,n=0,x=0;
    while(gets(a))
    {
        c=0,s=0,n=0,x=0;
        k=strlen(a);
        if(k>=6&&k<=32)
        {
            for(i=0; i<k; i++)
            {
                if(a[i]>='A'&&a[i]<='Z')
                {
                    c++;
                }
                else if(a[i]>='a'&&a[i]<='z')
                {
                    s++;
                }
                else if(a[i]>='0'&&a[i]<='9')
                {
                    n++;
                }
                else
                {
                    x++;
                }
            }
            if(x!=0||c==0||s==0||n==0){
                printf("Senha invalida.\n");
            }
            else{
                printf("Senha valida.\n");
            }
        }
        else
        {
            printf("Senha invalida.\n");
        }
    }
    return 0;
}
