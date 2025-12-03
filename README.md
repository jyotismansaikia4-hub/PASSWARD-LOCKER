
#include <stdio.h>
#include <string.h>
int main(void) {
    const char secret[] = "t7;Z";
    while (1) { 
        char input[20];
        printf("Enter code: ");
        scanf("%19s", input);
        if (strcmp(input, secret) == 0) {
            puts("Unlocked!");
            return 0; 
            puts("wrong password");
            break;
        }
    }
    return 0;
}

        
