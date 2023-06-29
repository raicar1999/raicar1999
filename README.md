#include <stdio.h>

int calcularSomaPA(int a1, int an, int n) {
    int soma = (n * (a1 + an)) / 2;
    return soma;
}

int main() {
    int a1, an, n;
    printf("Digite o valor do primeiro elemento (a1): ");
    scanf("%d", &a1);
    printf("Digite o valor do n-ésimo elemento (an): ");
    scanf("%d", &an);
    printf("Digite o número de termos (n): ");
    scanf("%d", &n);
    
    int soma = calcularSomaPA(a1, an, n);
    printf("A soma dos %d primeiros termos da P.A. é: %d\n", n, soma);
    
    return 0;
}
