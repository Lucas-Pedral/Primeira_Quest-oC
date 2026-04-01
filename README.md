#include <stdio.h>

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
