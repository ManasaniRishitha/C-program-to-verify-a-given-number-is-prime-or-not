# C-program-to-verify-a-given-number-is-prime-or-not
#include<stdio.h>
void main()
{
int n,flag=0,i;
printf("enter a number:");
scanf("%d",&n);
for(i=2;i<n;i++)
{
if(n%i==0)
{
flag++;
}
}
if(flag==0)
printf("\n %d is a prime number",n);
else
printf("\n %d is not  a prime number",n);
}
