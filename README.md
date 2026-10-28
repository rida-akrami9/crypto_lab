# crypto_lab
LAB 1 : WRITE A C PROGRAM THAT CONTAINS A STRING (CHAR POINTER) 
\HELLO WORLD. THE PROGRAM SHOULD XOR EACH CHARACTER IN THIS 
STRING WITH ZERO AND DISPLAY THE RESULT
#include <stdio.h>
int main() {
    char *str = "Hello World"; 
    int i = 0; 
    printf("Original string: %s\n", str); 
    printf("After XOR with 0: ");
   while(str[i]!= '\0') { 
        char result = str[i] ^ 0; 
        printf("%c", result); 
        i++; 
    }
    printf("\n"); 
    return 0; 
}
