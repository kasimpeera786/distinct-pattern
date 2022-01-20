#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{
    char s[2000001];
    long int ans=1;
    int a[256];
    
    scanf("%s",s);//ab ==> ab, ba ==> 2
    int len=strlen(s);
    
    for(int i=0; i<len; i++)
    {
        ans = ans + i - a[s[i]];
        a[s[i]]++;
    }
    printf("%ld",ans);
    
    return 0;
}
