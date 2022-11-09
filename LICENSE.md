#include<iostream>
#include<stdio.h>
#include<windows.h>
int main(void) {
	float x, y, a;
	for (y = 1.5;y > -1.5;y -= 0.1)
	{
		for (x = -1.5;x < 1.5;x += 0.05)
		{
			a = x * x + y * y - 1;
			putchar(a * a * a - x * x * y * y * y <= 0.0 ? '*' : ' ');
		}
		system("color 0c");
		putchar('\n');
	}
	printf("宝贝专属\n");
	printf("愿你天天开心 爱你哟！！！\n");
	return 0;
}
