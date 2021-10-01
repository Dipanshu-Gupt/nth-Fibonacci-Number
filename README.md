# nth-Fibonacci-Number
first code at github

#include <stdio.h>

int main()
{
    int a,b,res,n,i;
    printf("enter the nth position at which you want fibonacci number");
    scanf("%d",&n);
    a=0;
    b=1;
    for(i=0;i<n;i++)
    { 
        res=a+b;
        a=b;
        b=res;
    }
    printf("%d",a);
    return 0;
}
