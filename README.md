- š Hi, Iām @YagnaRaval28
- š Iām interested in ...
- š± Iām currently learning .C..
- šļø Iām looking to collaborate on ...
- š« How to reach me yagnaraval4@gmail.com...

<!---
YagnaRaval28/YagnaRaval28 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
//Function of Dereference:
int dereferences(int *a,int *b)
{
	int c;
	*a=*a+*b;
	*b=*a-*b;
	return;
}
int main()
{
	int a=4,b=3;
	scanf("%d %d",&a,&b);
	dereferences(&a,&b);
	printf("A=%d,B=%d",a,b);
	return 0;

}
