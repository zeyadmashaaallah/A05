# A05
#include <stdio.h>
#include<stdbool.h>
bool fun(int a[], int n)
{
int i;
bool y=false;
for(i=0;i<n;i++)
{
if(a[i]==0)
y=true;
}
return y;
}
int main() {
int a[] = {1,0,3,4};
bool x=fun(a,4);
printf("%d",x);
return 0;
}

