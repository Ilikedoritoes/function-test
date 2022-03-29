


#include <stdlib.h>
#include <stdio.h>
#define _CRT_SECURE_NO_WARNINGS

int check(int num1, int num2, int result = 1)
{
	if ((num1 * 2 == num2) && (num2 * 2 == num1))
		return result;
}

void main()
{
	int result, x = 4, y = 2;
	check(x, y);



	system("pause");
}
//יש לכתוב תוכנית אשר מפעילה פונקציה שמקבלת 2 מספרים 
//ומדפיסה אם האיבר השני גדול פי 2 מהאיבר הראשון או לא
