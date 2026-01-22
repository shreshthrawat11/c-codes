#include <stdio.h>
#include <string.h>
#include <math.h>
#include <ctype.h>

int main()
{
    char str1[50] = "Hello";
    char str2[50] = "World";
    char str3[50];
    char ch = 'a';
    int num = 25;
    /* strlen() */
    printf("Length of str1 = %d\n", strlen(str1));

    /* strcpy() */
    strcpy(str3, str1);
    printf("Copied string = %s\n", str3);

    /* strcat() */
    strcat(str1, str2);
    printf("Concatenated string = %s\n", str1);

    /* strcmp() */
    if(strcmp(str2, "World") == 0)
        printf("Strings are equal\n");
    else
        printf("Strings are not equal\n");

    /* sqrt() */
    printf("Square root of %d = %.2f\n", num, sqrt(num));

    /* pow() */
    printf("2 raised to power 3 = %.0f\n", pow(2, 3));

    /* toupper() */
    printf("Uppercase of %c = %c\n", ch, toupper(ch));

    /* tolower() */
    printf("Lowercase of A = %c\n", tolower('A'));

    return 0;
}