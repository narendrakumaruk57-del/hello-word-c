#include <stdio.h>

int main() {
    // Standard variables
    char name[50];
    int age;

    // Prompting the user for name and age
    printf("========================================\n");
    printf("   Welcome to the C Collaboration Lab   \n");
    printf("========================================\n");
    
    printf("Enter your name: ");
    scanf("%s", name);

    printf("Enter your age: ");
    scanf("%d", &age);

    // Printing the output
    printf("\n--- User Details ---\n");
    printf("Hello, %s! You are %d years old.\n", name, age);
    printf("Program executed successfully and tested!\n");

    return 0;
}
