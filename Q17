#include <stdio.h>

int main()
{
    int a[100], n, pos, i;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    printf("\nArray before deletion: ");
    for(i = 0; i < n; i++)
        printf("%d ", a[i]);

    printf("\nEnter position to delete (1 for front, %d for end, or any in between): ", n);
    scanf("%d", &pos);

    if(pos < 1 || pos > n)
        printf("Invalid position!");
    else
    {
        for(i = pos - 1; i < n - 1; i++)
            a[i] = a[i + 1];

        n--;

        printf("\nArray after deletion: ");
        for(i = 0; i < n; i++)
            printf("%d ", a[i]);
    }

    return 0;
}
