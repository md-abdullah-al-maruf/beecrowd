#include<stdio.h>
int main()
{
    int i,j=0,k;
    char a[1000],b[1000];
    while(gets(a)!='\0')
    {
        for(i=0; a[i]!='\0'; i++)
        {
            if(a[i]!=' ')
            {

                if(j%2==0)
                {
                    if(a[i]>='a'&&a[i]<='z')
                    {
                        a[i]=a[i]-32;
                    }
                }
                else
                {
                    if(a[i]>='A'&&a[i]<='Z')
                    {
                        a[i]=a[i]+32;
                    }
                }
                j++;
            }
        }
        printf("%s\n",a);
        j=0;
    }
    return 0;
}
