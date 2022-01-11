# length-of-string-without-using-lib-function


#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
char str[30];
int i,count=0;
printf("enter string:\n");
scanf("%s",str);
for(i=0;str[i]!=0;i++)
{
    count++;
}
printf("%d",count);
    
    return 0;
}
