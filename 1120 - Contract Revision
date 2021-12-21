#include <stdio.h>
#include <string.h>
int main()
{
    char n[1000],m[1000],p[1000];
    int a,b,i,j=0,d,e,f,k;
    while(1)
    {
        aa:
        a=0;
        b=0;
        i=0;
        j=0;
        d=0;
        e=0;
        f=0;
        scanf("%d",&d);
        scanf("%s",&n);
        if(d==0&&n[0]=='0'&&n[1]=='\0')
        {
            break;
        }
        b=strlen(n);
        for(i=0; i<b; i++)
        {
            if(n[i]==(48+d)||n[i]=='0')
            {
                j++;
            }
        }
        if(j==b)
        {
            printf("0\n");
        }
        else
        {
            for(i=0,j=0; i<b; i++)
            {
                if(n[i]==(48+d))
                {
                    continue;
                }
                else
                {
                    m[j]=n[i];
                    j++;
                }
            }
            m[j]='\0';

            for(i=0;i<j;i++){

                if(m[i]=='0'){
                    continue;
                }
                else{
                    e=i;
                    for(k=e,f=0;k<j;k++,f++){
                        p[f]=m[k];
                    }
                    p[f]='\0';
                    printf("%s\n",p);
                    goto aa;
                }

            }
        }
    }
    return 0;
}
