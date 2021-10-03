#include<stdio.h>

int main()
{
    int r,c;
    printf("Enter the order of 2D matrix (row*col)\n");
    scanf("%d %d",&r,&c);
    int a[r][c];
    printf("Enter the 2D array\n");
    for(int i=0;i<r;i++)
    {
        for(int j=0;j<c;j++)
            scanf("%d",&a[i][j]);
    }
    int n=r*c;
    int b[n];
    int k=0;
    printf("Inital 2D Array:\n");
    for(int i=0;i<r;i++)
    {
        for(int j=0;j<c;j++)
            printf("%d ",a[i][j]);
        printf("\n");
    }
    for(int i=0;i<r;i++)
    {
        for(int j=0;j<c;j++)
        {
            b[k]=a[i][j];
            k++;
        }
    }
    printf("\n Final 1D array:\n");
    for(int i=0;i<n;i++)
        printf("%d ",b[i]);
} 
