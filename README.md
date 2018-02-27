#include<stdio.h>
#include<string.h>
int main() 
{
   char str[100];
   int n,i,j;
   scanf("%s",str);
   scanf("%d",&n);
  for(i=n;i<strlen(str);i++)
   {
       printf("%c",str[i]);
   }
   for(i=0;i<n;i++)
   {
       printf("%c",str[i]);
   }
 }
