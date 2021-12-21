#include<stdio.h>

int main()
{
    double A,B,C,a,b,c;
    scanf("%lf%lf%lf",&A,&B,&C);
    
    if(A>0 && B>0 && C>0){
    if(A>=B && A>=C){
    a=A;
    }
    else if(B>=A && B>=C){
    a=B;
    }
    else if(C>=A && C>=B){
    a=C;
    }
    if((A>=B && A<=C)||(A<=B && A>=C)){
    b=A;
    }
    else if((B>=A && B<=C)||(B<=A && B>=C)){
    b=B;
    }
    else if((C>=A && C<=B)||(C<=A && C>=B)){
    b=C;
    }
    if(A<=B && A<=C){
    c=A;
    }
    else if(B<=A && B<=C){
    c=B;
    }
    else if(C<=A && C<=B){
    c=C;
    }
    
    
    
    if(a>=b+c){
    printf("NAO FORMA TRIANGULO\n");
    }
    else if((a*a)==((b*b)+(c*c))){
    printf("TRIANGULO RETANGULO\n");
    }
    else if((a*a)>((b*b)+(c*c))){
    printf("TRIANGULO OBTUSANGULO\n");
    }
    else if((a*a)<((b*b)+(c*c))){
    printf("TRIANGULO ACUTANGULO\n");
    }
    
    if(a==b && b==c){
    printf("TRIANGULO EQUILATERO\n");
    }
    if((a==b && a!=c)||(a==c && a!=b)||(b==c && b!=a)||(b==a && b!=c)||(c==a && c!=b)||(c==b && c!=a)){
    printf("TRIANGULO ISOSCELES\n");
    }
    
    }
    return 0;
}
