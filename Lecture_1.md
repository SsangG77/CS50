# c 언어 소개
## 스크래치와 c언어 비교
- 스크래치에서 hello, world 출력기능을 c에서 구현

```c
#include <stdio.h>
int main(void) 
{
  printf("Hello, world");
}
```

- 코딩에서는 큰따움표로 문자열을 표현해야 한다.
- #include <stdo h> 이것을 사용하는 이유는 스크래치와 다르게 해당 함수가 구현된 위치, 저장된 위치를 미리 컴퓨터에게 알려주는 역할이다.
- c언어를 바이너리로 변환해주는 소프트웨어를 컴파일러라고 한다.
- 터미널에서 clang 으로 해당 코드를 실행하는데 이것 또한 특정 집단이 만든 프로그램이다.
clang hello.c 입력 후, ./a.out 입력하면 프로그램 실행됨.

```c
string anser = get_string("What`s your name?\n");
printf("answer: %s", answer)
```

- 변수 생성 방법: 자료형 변수명 <- 이렇게 생성

- 플레이스 홀더 입력: `printf("hello, %s\n", answer);`
%s로 출력 문자열에서 표시를 하고 그 위치에 나타낼 실제 데이터를 두번째 매개변수로 입력한다.

### 스크래치에서 변수사용 예제
- 변수 선언 방법: `int counter = 0;`
- `자료형 변수명 = 값`으로 변수선언을 한다.
- 1씩 카운팅하는 방법 `counter = counter + 1` 재사용시에는 맨앞에 자료형을 사용하지 않는다.

### if문 사용 예제
```c
if (x < y)
{
  printf("x is less than y\n");
}
else 
{
  printf("x is not less than y\n");
}
```

