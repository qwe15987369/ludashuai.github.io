```c
#include<stdio.h>
#include<math.h>
#define EPS 1e-6
int main (void){
float a,b;
scanf("%f %f",&a,&b);
fabs( a - b )<EPF;//比较浮点数大小是否相等（在可接受误差范围里面）
}
\```