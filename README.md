#include <stdio.h>

//Primeira
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

//Segunda

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

//Terceira
int main(){
    
  float nota;
  
  printf("Qual a sua nota ");
  scanf("%f", &nota);
  
  if(nota >= 7 ){
  printf("Aprovado");
  }
  
  else if (nota >= 5){
      printf("Recuperação");
  }

else {
    printf("Reprovado");
}
    
return 0;
}
