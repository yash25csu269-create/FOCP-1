# FOCP-1
#include <stdio.h>
#include <math.h>

int main()
{
    int n, t, r, c = 0;
    float s = 0;

    printf("Enter a number: ");
    scanf("%d", &n);

    t = n;
    while (t != 0)
    {
        t = t / 10;
        c++;
    }

    t = n;
    while (t != 0)
    {
        r = t % 10;
        s = s + pow(r, c);
        t = t / 10;
    }

    if ((int)s == n)
        printf("%d is an Armstrong number.", n);
    else
        printf("%d is not an Armstrong number.", n);

    return 0;
}
