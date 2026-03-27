# String-conversion
C programing
#include <stdio.h>
#include <string.h>
#include <ctype.h>
int main () {
    char s [100];
    printf("Enter the string: ");
    fgets(s, 100, stdin);
    for(int i = 0; s[i] != '\0'; i++)
    {
        s[i] = tolower(s[i]); // convert to lower letter like a,b,c,d 
    }
    printf("%s", s);
    for(int i = 0; s[i] != '\0'; i++)
    {
        s[i] = toupper(s[i]); //convert to upper letter like A,B,C,D
    }
    printf("%s", s);
    return 0;
}
