#include <stdio.h>

int main()
{
    int a[100], n, i, j, f = 0;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    printf("Duplicate elements: ");

    for(i = 0; i < n; i++)
    {
        int count = 0;

        for(j = i + 1; j < n; j++)
        {
            if(a[i] == a[j] && a[i] != -1)
            {
                count++;
                a[j] = -1;
            }
        }

        if(count > 0 && a[i] != -1)
        {
            printf("%d ", a[i]);
            f = 1;
        }
    }

    if(f == 0)
        printf("-1");

    return 0;
}
