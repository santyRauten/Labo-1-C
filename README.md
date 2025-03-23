//# Labo-1-C
//Primera prueba de CodeBlocks
#include <stdio.h>
int main(){
    int n1=0,n2=0,suma=0,resta=0,multiplicacion=0;
    float division=0, promedio=0;
    printf("ingrese algun numero \n");
scanf("%d" , &n1);
printf("ingrese otro numero: \n");
scanf("%d" , &n2);
printf("numero 1: %d \n", n1);
printf("numero 2: %d \n", n2);
fflush(stdin);
suma=n1+n2;
printf("la suma da:%d \n",suma);
resta=n1-n2;
printf("la resta da:%d \n",resta);
multiplicacion=n1*n2;
printf("la multiplicacion da:%d \n",multiplicacion);
division= (float)n1/n2;
printf("la division da da:%.2f \n",division);
promedio=(float)(n1+n2)/2;
printf("el promedio da:%.1f \n",promedio);


return 0;
}
