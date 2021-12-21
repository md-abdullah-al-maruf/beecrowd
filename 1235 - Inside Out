#include<stdio.h>
#include<string.h>
int main()
{
    int i,j=0,k,m,n;
    char a[110];
    scanf("%d",&k);
    getchar();
    while(k--)
    {
        gets(a);
        m=strlen(a);
        if(m%2==0)
        {
            for(i=((m/2)-1); i>=0; i--)
            {
                printf("%c",a[i]);
            }
            for(i=m-1; i>((m/2)-1); i--)
            {
                if(i==(m/2)){
                    printf("%c\n",a[i]);
                }
                else{
                     printf("%c",a[i]);
                }
            }
        }
        else{
            for(i=(m/2); i>=0; i--)
            {
                printf("%c",a[i]);
            }
            for(i=m-1; i>=((m/2)+1); i--)
            {
                if(i==((m/2)+1)){
                    printf("%c\n",a[i]);
                }
                else{
                    printf("%c",a[i]);
                }
            }
        }
    }
    return 0;
}

