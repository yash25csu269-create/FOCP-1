#include <stdio.h>

int main()
{
    int a[100], n, i, f = -1;
    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    for(i = 0; i < n; i++)
    {
        if(a[i] == 99)
        {
            f = i;
            break;
        }
    }

    if(f != -1)
        printf("First occurrence of 99 is at position %d", f + 1);
    else
        printf("99 not found in the array");

    return 0;
}
