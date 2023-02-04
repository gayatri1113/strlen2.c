//# strlen2.c//
#include<stdio.h>
#include<string.h>
int main()
{
    int n;
    printf("Enter string:");
    scanf("%d",&n);
    n=strlen("%d");
    printf("length of string:%d",n);
    return 0;
}
