#include <stdio.h>

int main() {
    char chr;
    printf("Enter the character:");
    scanf("%c", &chr);
    if (chr=='a' || chr=='e' || chr=='i' || chr=='o' || chr=='u' || chr=='A' || chr=='I' || chr=='E' || chr=='O' || chr=='U') 
    {   
        printf("vowel");
    }
    else
    {
        printf("consonant");
    }
    return 0;
}
