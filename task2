#include <stdio.h>
#include <stdlib.h>

int main()
{
    int n;
    double sum = 0;

    printf("Enter the number of elements: ");
    scanf("%d", &n);

    int *arr = calloc(n, sizeof(int));

    if (arr == NULL)
    {
        printf("Memory allocation failed.\n");
        return 1;
    }

    printf("Array after calloc: ");
    for (int i = 0; i < n; i++)
    {
        printf("%d ", arr[i]);
    }

    printf("\nEnter %d integers: ", n);

    for (int i = 0; i < n; i++)
    {
        scanf("%d", &arr[i]);
    }

    printf("Updated array: ");
    for (int i = 0; i < n; i++)
    {
        printf("%d ", arr[i]);
        sum += arr[i];
    }

    double average = sum / n;

    printf("\nAverage of the array: %.1f\n", average);

    free(arr);

    return 0;
}
