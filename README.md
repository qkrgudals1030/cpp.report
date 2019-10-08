1. 메인

#include<stdio.h>

int add(int a, int b);

int sub(int a, int b);

int mul(int a, int b);

double div(float a, float b);

int cjy(int a, int b);

int phm(int a, int b);

int main(){

int a=9, b=2;

printf("%d\n", add(a,b));

printf("%d\n", sub(a,b));

printf("%d\n", mul(a,b));

printf("%4.2f\n", div(a,b));

printf("%d\n", cjy(a,b));

printf("%d\n", phm(a,b));

}

2. 더하기

int add(int a, int b){

return (a+b);

}

3. 뺼셈

int sub(int a, int b){

return (a-b);

}

4. 곱하기

int mul(int a, int b){

return (a*b);

}

5. 나누기

double div(float a, float b){

return (a/b);

}

6. 모듈라

int cjy(int a, int b){

return (a%b);

}

7. 몫

int phm(int a, int b){

return (a/b);

}

8. 소감 


