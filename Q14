#include <stdio.h>

int main()
{
    int a[100], n, i, j, c = 0, p;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    for(i = 0; i < n; i++)
    {
        if(a[i] < 2)
            continue;

        p = 1;
        for(j = 2; j * j <= a[i]; j++)
        {
            if(a[i] % j == 0)
            {
                p = 0;
                break;
            }
        }

        if(p == 1)
            c++;
    }

    printf("Total prime numbers in array: %d", c);
    return 0;
}
