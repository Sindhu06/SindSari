# SindSari
To get an array of elements and sort them.
#include<stdio.h>
int main()
{
char s;
int i,a[10],max=0;
scanf("%c",s);
for(i=0;i<10;i++)
{
scanf("%d",&a[i]);
}

for(i=0;i<10;i++)
{
if(max<a[i])
max=a[i];
}
printf("\n%d",max);
return 0;
}

