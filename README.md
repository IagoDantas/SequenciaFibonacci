# SequenciaFibonacci
Sequência de Fibonacci, feito em C


/***SEQUENCIA DE FIBONACCI***/
#include <stdio.h>

int main()
{
    int num1,num2,num3,i;
    num1 = 1; 
    num2 = 1;
    num3 = 0;
    i = 2;
    printf("%u\t %u\t",num3,num1,num2);
    while(i<50){
        num3 = num1 + num2;
        num1 = num2;
        num2 = num3;
        printf("%u\t",num3);
        i++;
    }
    return 0;
}
