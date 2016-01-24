
#include<stdio.h>

int main(void)
{

int cat = 0;
float ball = 0;
double sky = 0;
char boy, girl;

printf("Please enter a value for cat, ball, sky, boy, girl: ");
scanf("%d%f%lf%c%c", &cat, &ball, &sky, &boy, &girl);

printf("The value of cat is: %0.2d\n", cat);
printf("The value of ball is: %0.2f\n", ball);
printf("The value of sky is: %0.2f\n", sky);
printf("The value of boy is: %c\n", boy);
printf("The value of girl is: %c\n", girl);


return 0;
}
