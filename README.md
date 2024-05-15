# AtividadeComC1

#include <stdio.h>
#include <stdlib.h>

int main() { 

float nota1;
float nota2;
float nota3;
float nota4;

// Cálculo do total de 4 notas
    printf("Digite a primeira nota: ");
	scanf("%f",&nota1);
	printf("Digite a segunda nota: ");
	scanf("%f",&nota2);
	printf("Digite a terceira nota: ");
	scanf("%f",&nota3);
	printf("Digite a quarta nota: ");
	scanf("%f",&nota4);
	
	float total = nota1+nota2+nota3+nota4;
	printf("Nota total: %f", total);
	
	   return 0;
}
