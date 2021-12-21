#include<stdio.h>
#include<string.h>
int main()
{
    int i,j,k=0,l,m,n;
    char a[1000],b[1000],c[1000];
    scanf("%d ",&l);
    while(l--){
        scanf("%s %s",&a,&b);
        m=strlen(a);
        n=strlen(b);
        if(m<=n){
            for(i=0;i<=n;i++){
                if(i<m){
                    c[k]=a[i];
                    c[k+1]=b[i];
                    k=k+2;
                }
                else{
                    c[k]=b[i];
                    k++;
                }
            }
        }
        if(m>n){
            for(i=0;i<=m;i++){
                if(i<n){
                    c[k]=a[i];
                    c[k+1]=b[i];
                    k=k+2;
                }
                else{
                    c[k]=a[i];
                    k++;
                }
            }
        }
        k=0;
        puts(c);
    }
    return 0;
}
