#include <stdio.h>
#include <math.h>

int main()
{
    int ch;
    printf("Choose conversion:\n1. Binary to Decimal\n2. Decimal to Binary\n");
    scanf("%d", &ch);

    if (ch == 1)
    {
        long b;
        int d = 0, i = 0, r;
        printf("Enter a binary number: ");
        scanf("%ld", &b);

        while (b != 0)
        {
            r = b % 10;
            d = d + r * pow(2, i);
            b = b / 10;
            i++;
        }
        printf("Decimal value = %d", d);
    }

    else if (ch == 2)
    {
        int d, b[32], i = 0;
        printf("Enter a decimal number: ");
        scanf("%d", &d);

        while (d > 0)
        {
            b[i] = d % 2;
            d = d / 2;
            i++;
        }

        printf("Binary value = ");
        for (i = i - 1; i >= 0; i--)
            printf("%d", b[i]);
    }

    else
        printf("Invalid choice!");

    return 0;
}
