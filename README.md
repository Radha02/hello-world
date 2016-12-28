#include<stdio.h>
#define null 0
int main()
{
    int n,r=0,rev = 0;
    printf("enter the number);
    scanf("%d",&n);
    if(n = null)
    {
        rev = 0;
    }
    else 
    {
        r=n%10;
        rev = rev+r;
        n = n/10;
    }
    printf("The reverse of the given number is = %d",rev);
}
