# squares
This is a program of squares of numbers using array in 1 dimension.
#include <stdio.h>

int main(int argc, char const *argv[])
{
    int a[6], i;
    printf("Enter 6 numbers:");
    for (i = 0; i < 5; i++)
    {
        scanf("%d", &a[i]);
    }
    printf("Square of entered numbers are:");
    for (i = 0; i < 5; i++)
    {
        printf("%d \n", a[i] * a[i]);
    }
    return 0;
}
