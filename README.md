#include <stdio.h>

int main() {
	char name[10];
	int num;
	printf("이름을 입력하시오: ");
	scanf_s("%s",name,10);
	printf("\n");
	printf("학번을 입력하시오: ");
	scanf_s("%d", &num);
	printf("\n");

	printf("<출력>");
	printf("\n");
	printf("이름:%s ",name);
	printf("\n");
	printf("학번:%d ",num);
	return 0;
}
