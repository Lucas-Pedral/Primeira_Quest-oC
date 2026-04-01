#include <stdio.h>

\\Primeira Questão
int main() {
    float idade;
    
    printf("Qual o número ");
    scanf("%f", &idade);
    printf("%.1f", idade);
    
    if(idade >= 18 ){
        printf("Pode entrar");
    }
    
    else if(idade >= 16 ) {
        printf("Pode entrar com responsavel");
    }
    
    else{
        printf("Não entra");
    }


    return 0;
}

\\Segunda Questão

int main(){
    
 float valor;
 
 printf(" Qual o valor da compra ");
 scanf("%f", &valor);
 
 if(valor > 100){
     printf("Possui desconto");
 }
 else {
     printf ("Não possui desconto");
 }
    
    return 0;
    
}
