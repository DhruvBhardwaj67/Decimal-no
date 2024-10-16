#include <stdio.h>


void printBinary(int n) {
    if (n > 1) {
        printBinary(n / 2);
    }
    printf("%d", n % 2);
}

int main() {
    int decimal;

   
    printf("Enter a decimal number: ");
    scanf("%d", &decimal);

   
    printf("Hexadecimal: %X\n", decimal);

  
    printf("Octal: %o\n", decimal);

   
    printf("Binary: ");
    printBinary(decimal);
    printf("\n");

    return 0;
}
# Decimal-no
