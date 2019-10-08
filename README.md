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

평소와 다르게 개발자 명령프롬프트를 활용하여 모든 파일과 코드를 만들고 작업을 하면서 cpp에 대해 더 많은 이해를  할 수 있었습니다. 
처음에는 코드도 평소 보던 것과 달라 생소하고 익숙하지 않아 고생도 하였지만 점점 명령어의 뜻을 이해해가면서 수월하게 할 수 있었습니다.

내일이 돼어도 까먹지 않도록 집에 돌아가서도 반복하여 더욱 노력하도록 하겠습니다.


