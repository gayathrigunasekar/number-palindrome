# number-palindrome
check number is palindrome or not
#include<stdio.h>
int main()
{int n,reverseno=0,originalno,remainder;
printf("enter an integer:");
scanf("%d",&n);
originalno=n;
while(n!=0){remainder=n%10;
reverseno=reverseno*10+remainder;
n/10;}
if(originalno==reverseno)
printf("%d is a palindrome",originalno);
else
printf("%d is not a palindrome ",originalno);
return 0;
}
