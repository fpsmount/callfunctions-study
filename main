#include <stdio.h>
#include <stdlib.h>

void returnFunction(){
	int option;
	
	printf("Agora, o que voce quer fazer? (1 - Voltar ao menu | 2 - Sair)\n");
			scanf("%d", &option);
			
			if (option == 1){
				printf("\n");
			} else if (option == 2){
				printf("Adeuszinho!");
				exit(0);
			} else {
				printf("Opcao Invalida!\n");
		}
}

void calcularSoma(){
	float num1, num2, soma;
	
	printf("CALCULADORA DE SOMA!\n");
	printf("Digite o primeiro numero: \n");
	scanf("%f", &num1);
	printf("Digite o segundo numero: \n");
	scanf("%f", &num2);
			
	soma = num1 + num2;
			
	printf("A soma dos numeros informados eh: %.2f\n", soma);
};


void calcularSubtracao(){
	float num1, num2, subtracao;
	
	printf("CALCULADORA DE SUBTRACAO!\n");
	printf("Digite o primeiro numero: \n");
	scanf("%f", &num1);
	printf("Digite o segundo numero: \n");
	scanf("%f", &num2);
	
	subtracao = num1 - num2;
	
	printf("A subtracao dos numeros informados eh: %.2f\n", subtracao);
};

void calcularMultiplicacao(){
	float num1, num2, multiplicacao;
	
	printf("CALCULADORA DE MULTIPLICACAO!\n");
	printf("Digite o primeiro numero: \n");
	scanf("%f", &num1);
	printf("Digite o segundo numero: \n");
	scanf("%f", &num2);
	
	multiplicacao = num1 * num2;
	
	printf("A multiplicacao dos numeros informados eh: %.2f\n", multiplicacao);
};

void calcularDivisao(){
	float num1, num2, divisao;
	
	printf("CALCULADORA DE DIVISAO!\n");
	printf("Digite o primeiro numero: \n");
	scanf("%f", &num1);
	printf("Digite o segundo numero: \n");
	scanf("%f", &num2);
	
	divisao = num1 / num2;
	
	printf("A divisao dos numeros informados eh: %f\n", divisao);
}

int main(){
	
	int opc;
	
	printf("BEM VINDO(A) A CALCULADORA FEITO EM CPP!!\n");
	
	do {
	printf("(1) - Soma\n(2) - Subtracao\n(3) - Multiplicacao\n(4) - Divisao\n");
	scanf("%d", &opc);
	
	switch (opc){
		case 1:
			calcularSoma();
			returnFunction();
		break;
			
		case 2:
			calcularSubtracao();
			returnFunction();
		break;
		
		case 3:
			calcularMultiplicacao();
			returnFunction();
		break;
		
		case 4:
			calcularDivisao();
			returnFunction();
		break;
		
		default:
			printf("Opcao Invalida!");
		break;
	};
	
	} while (1);
	
 return 0;}
