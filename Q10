#include <stdio.h>

int main()
{
    int n, i, c = 0;
    int a[100];
    printf("Enter number of students: ");
    scanf("%d", &n);

    printf("Enter marks of %d students: ", n);
    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    printf("Students who scored 99:\n");
    for(i = 0; i < n; i++)
    {
        if(a[i] == 99)
        {
            printf("Student %d\n", i + 1);
            c++;
        }
    }

    printf("Total students who scored 99: %d", c);
    return 0;
}
