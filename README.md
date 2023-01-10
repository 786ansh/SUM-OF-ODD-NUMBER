# SUM-OF-ODD-NUMBER
#include<stdio.h>
int main()
{
    int a, n,i,sum=0;
    printf("enter starting range");
    scanf("%d",&a);
    printf("enter end range");
    scanf("%d",&n);
    for(int i=a;i<=n;i++)
    if(i%2!=0)
    {
        sum=sum+i;
    }
    printf("sum is: %d",sum);
    return 0;
}
