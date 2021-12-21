#include <stdio.h>
int main()
{
    int a,i,j,k,led=0;
    char c[1000];
    scanf("%d ",&a);
    for(i=0; i<a; i++)
    {
        scanf("%s",&c);
        k=strlen(c);
        for(j=0; j<k; j++)
        {
            switch(c[j])
            {
            case '0':
                led=led+6;
                break;
            case '1':
                led=led+2;
                break;
            case '2':
                led=led+5;
                break;
            case '3':
                led=led+5;
                break;
            case '4':
                led=led+4;
                break;
            case '5':
                led=led+5;
                break;
            case '6':
                led=led+6;
                break;
            case '7':
                led=led+3;
                break;
            case '8':
                led=led+7;
                break;
            case '9':
                led=led+6;
                break;

            }
        }
        printf("%d leds\n",led);
        led=0;
    }
    return 0;
}
