#include <stdio.h>

int main()
{
    int a[100], n, pos, val, i;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    printf("\nArray before insertion: ");
    for(i = 0; i < n; i++)
        printf("%d ", a[i]);

    printf("\nEnter position to insert (1 for front, %d for end, or any in between): ", n + 1);
    scanf("%d", &pos);

    printf("Enter value to insert: ");
    scanf("%d", &val);

    if(pos < 1 || pos > n + 1)
        printf("Invalid position!");
    else
    {
        for(i = n; i >= pos; i--)
            a[i] = a[i - 1];

        a[pos - 1] = val;
        n++;

        printf("\nArray after insertion: ");
        for(i = 0; i < n; i++)
            printf("%d ", a[i]);
    }

    return 0;
}
