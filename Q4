#include <stdio.h>
1ST METHOD
int main()
{
    int a, b, t;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    t = a;
    a = b;
    b = t;

    printf("After swapping: a = %d, b = %d", a, b);
    return 0;
}
2ND METHOD
#include <stdio.h>

int main()
{
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    a = a + b;
    b = a - b;
    a = a - b;

    printf("After swapping: a = %d, b = %d", a, b);
    return 0;
}
3RD METHOD
#include <stdio.h>

int main()
{
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    a = a ^ b;
    b = a ^ b;
    a = a ^ b;

    printf("After swapping: a = %d, b = %d", a, b);
    return 0;
}
4TH METHOD
#include <stdio.h>

int main()
{
    int a, b, t, *p, *q;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    p = &a;
    q = &b;

    t = *p;
    *p = *q;
    *q = t;

    printf("After swapping: a = %d, b = %d", a, b);
    return 0;
}
