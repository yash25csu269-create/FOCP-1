#include <stdio.h>

int main()
{
    int a[100], n, i;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    for(i = 0; i < n; i++)
    {
        if((i == 0 || a[i] >= a[i - 1]) && (i == n - 1 || a[i] >= a[i + 1]))
        {
            printf("Peak element is %d at position %d", a[i], i + 1);
            break;
        }
    }

    if(i == n)
        printf("No peak element found.");

    return 0;
}
