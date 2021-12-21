#include<stdio.h>
#include<string.h>
int main()
{
    int i,j=1,k=1,m,n;
    char a[1000];
    while(gets(a)!='\0')
    {
        m=strlen(a);
        for(i=0; i<=m; i++)
        {
            if(i<m)
            {
                if(a[i]=='_'&&j%2==1)
                {
                    printf("<i>");
                    j++;
                }
                else if(a[i]=='_'&&j%2==0)
                {
                    printf("</i>");
                    j++;
                }
                else if(a[i]=='*'&&k%2==1)
                {
                    printf("<b>");
                    k++;
                }
                else if(a[i]=='*'&&k%2==0)
                {
                    printf("</b>");
                    k++;
                }
                else
                {
                    printf("%c",a[i]);
                }
            }
            else if(i==m)
            {
                printf("\n");
            }
        }
    }
    return 0;
}
