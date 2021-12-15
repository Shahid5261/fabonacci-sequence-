# fabonacci-sequence-
#include<stdio.h>
int main()
{
	int n,f;
	printf("enter any number");
	scanf("%d",&n);
	f=fab(n);
	printf("%d sequence of fabonacci is %d",n,f);
	
}
int fab(int n)
{
	if(n==1||n==2)
	{
		return 1;
		
	}
	else
	{
		return fab(n-1)+fab(n-2);
	}

}
