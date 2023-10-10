#include <stdio.h>
#include <locale.h>

int main(){
	setlocale(LC_ALL, "Portuguese");
	double peso, altura, imc, num1, num2, soma, sub, mult, div, area, raio, celsius, fahrenheit;
	int opcao;
	
	printf("Escolha uma das operações abaixo:\n\n");
	
	printf("1- IMC: Índice de Massa Corporal.\n");
	printf("2- Soma.\n");
	printf("3- Subtração.\n");
	printf("4- Multiplicação.\n");
	printf("5- Divisão.\n");
	printf("6- Área do círculo.\n");
	printf("7- Conversão de Celsius para fahrenheit.\n\n");
	scanf("%d", &opcao);
	
	switch(opcao){
		case 1:
			printf("Digite o seu peso:\n");
			scanf("%lf", &peso);
			printf("Digite sua altura:\n");
			scanf("%lf", &altura);
			
			imc= peso/(pow(altura, 2));
			
			printf("Seu imc é %.2lf.\n", imc);
			break;
		
		case 2:
		    printf("Digite dois número para que a soma seja realizada.\n");
			scanf("%lf %lf", &num1, &num2);
			
			soma = num1+num2;
			
			printf("A soma de %.2lf mais %.2lf é %.2lf.\n", num1, num2, soma);
			
			break;	
			
		case 3:
			
			printf("Digite dois número para que a subtração seja realizada.\n");
			scanf("%lf %lf", &num1, &num2);
			
			sub = num1-num2;
			
			printf("A diferença entre %.2lf e %.2lf é %.2lf.\n", num1, num2, sub);
			
			break;
			
		case 4:
			
			printf("Digite dois número para que a multiplicação seja realizada.\n");
			scanf("%lf %lf", &num1, &num2);
			
			mult = num1*num2;
			
			printf("O produto de %.2lf vezes %.2lf é %.2lf.\n", num1, num2, mult);
			
			break;
			
		case 5:
			
			printf("Digite dois número para que a divisão seja realizada.\n");
			scanf("%lf %lf", &num1, &num2);
			
			div = num1/num2;
			
			printf("O quaciente de %.2lf dividido por %.2lf é %.2lf.\n", num1, num2, div);
			
			break;
			
		case 6:
			printf("Digite o raio do círculo:\n");
			scanf("%lf", &raio);
			
			area = 3.14*(pow(raio, 2));
			
			printf("A área do círculo é %.2lf.\n", area);
			break;
			
		case 7:
			printf("Digite uma temperatura em graus celsius:\n");
			scanf("%lf", &celsius);
			
			fahrenheit = (celsius*9/5)+32;
			
			printf("A converção de celsius para fahrenheit é %.2lf", fahrenheit);
			break;
			
		default:
		    printf("Você digitou uma opção inválida");
			break;	
			
	}

}
