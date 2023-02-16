#include<stdio.h>
main()
{
    int i=1,n;
    printf("enter the value of n\n");
    scanf("%d",&n);
    while(i<=n)
    {
        if(n%i==0)
        {
            printf("%d\t",i);
        }
        i++;
    }
}
