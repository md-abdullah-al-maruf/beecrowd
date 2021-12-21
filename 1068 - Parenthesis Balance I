#include<stdio.h>
int main()
{
    char a[10000];
    int i,j,m=0,n=0,p,b,c=0,d=0;
    while(scanf("%s",a)!=EOF){
    m=0,n=0,c=0,d=0;
    j=strlen(a);
    for(i=0; i<j; i++)
    {
        if(a[i]=='(')
        {
            m++;
        }
        else if(a[i]==')')
        {
            for(b=0;b<=i;b++){
                if(a[b]=='('){
                    c++;
                   }
                   else if(a[b]==')'){
                    d++;
                   }
            }
            if(c<d){
                goto aa;
            }
            n++;
        }
    }
    if(m==n){
        printf("correct\n");
    }
    else{
aa:
        printf("incorrect\n");
    }

    }
    return 0;
}
