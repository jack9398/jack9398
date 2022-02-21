#include<stdio.h>
int main()
{
    int n,i;
    printf("10:");
    scanf("%d",&n);
    printf("First n natural numbers in descending order %d:\n",n);
    for(i=n;i>0;i--)
    {
        printf("%d",i);
    }
    return 0;
}
