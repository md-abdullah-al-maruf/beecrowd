#include<stdio.h>
int main()
{
    float a,b,c,d,e,avg,avg2;
    scanf("%f%f%f%f",&a,&b,&c,&d);
    avg=(a*2+b*3+c*4+d*1)/10;
    printf("Media: %.1f\n",avg);
    if(avg>=7)
    {
        printf("Aluno aprovado.\n");
    }
    if(avg<5)
    {
        printf("Aluno reprovado.\n");
    }
    if(avg>=5 && avg<=6.9)
    {
        printf("Aluno em exame.\n");
        scanf("%f",&e);
        printf("Nota do exame: %.1f\n",e);
        avg2=(avg+e)/2;
        if(avg2>=5)
        {
            printf("Aluno aprovado.\n");
        }
        else
        {
            printf("Aluno reprovado.\n");
        }
        printf("Media final: %.1f\n",avg2);
    }
    return 0;
}
