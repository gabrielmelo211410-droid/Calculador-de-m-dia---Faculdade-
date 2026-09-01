# Calculador-de-media-da---Faculdade- em C
Programa de calculador de media em programação C, servindo para calcular médias escolares.
#include <stdio.h>
    int main() {
        int n1, n2, n3, soma;
    printf("digite o primeiro numero ");
    scanf("%d" , &n1) ; 
    printf("digite o segundo numero ") ;
    scanf("%d" , &n2) ; 
    printf("digite o terceiro numero ") ;
    scanf("%d" ,&n3) ; 
    soma = n1+n2+n3;
    printf("resultado:" "%d\n" , soma) ; 
    return 0;
    
    
    }
