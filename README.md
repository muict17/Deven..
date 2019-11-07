# Deven..
Homework krub
#include<stdio.h>
int palin(int n,int r,int t,int y)
{
    while(t!=0)
    {
        y=t%10;
        r=r*10+y;
        t=t/10;
    }
    if(r==n)
    {
        printf("palindrome");
    }
    else printf("Not palindrome");
    return n;

}
int main()
{
    int n,r=0,t,y;
    scanf("%d",&n);
    r=n;
    printf("%d",palin(n,r,t,y));
    return 0;
}
