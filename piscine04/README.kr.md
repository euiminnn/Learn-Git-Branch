[English](README.md)
# Chapter Ⅰ<br>Instruction

- 과제 레포지토리를 fork해서 사용하세요
- 제출은 push를 통해서 진행할 수 있습니다.
- branch, 커밋이 꼬인 경우에는 처음부터 다시 시작해야할 수 있습니다.
- 제출 commit 메세지는 자유롭게 작성하시면 됩니다.
- 프로젝트 커밋, 브랜치의 시간순 현황은 `git log —-oneline —-graph —-all` 명령으로 간단하게 확인할 수 있습니다.

<br>

- 이번 프로젝트는 계산기를 만드는 프로젝트 입니다.
- 최소 2명 이상의 팀을 이루세요.

<br>
<br>
<br>
    
# Chapter Ⅱ<br>Exercise 00 : 브랜치로 협업해보기 - 계산기 만들기

| 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|
| ex00/ | calculator | anything |

<br>

![](https://github.com/euiminnn/Learn-Git-Branch/blob/main/assets/p04example.png?raw=true)

- 위 그림과 같은 형태의 git graph를 만들어 보세요
- `main` 브랜치에서 `dev` 브랜치를 만듭니다.
- `dev` 브랜치에서 아래와같은 브랜치를 만듭니다.
    - **팀원과 서로 다른 브랜치에서 작업해 주세요.**
    - feature/square 브랜치에서는 제곱 기능을 구현합니다.
    - feature/sqrt 브랜치에서는 루트 기능을 구현합니다.
    - feature/gcd 브랜치에서 최대공약수를 구현합니다.
    - feature/lcm 브랜치에서 최소공배수를 구현합니다.
- `dev`브랜치에 feature/* 브랜치들을 **rebase** 하세요.
- `main`브랜치에 `dev` 브랜치를 merge 하세요.
- 계산기는 `main` 브랜치에서 정상적으로 작동해야 합니다.

<br>

* Example :

```c
#include <stdio.h>

double sqrt(int n);
int square(int n);
int gcd(int a, int b);
int lcm(int a, int b);

int main(void)
{
    printf("sqrt(4) : %d \n", sqrt(4));
    printf("square(4) : %d \n", square(4));
	printf("gcd(4, 2) : %d \n", gcd(4, 2));
	printf("lcm(42, 2) :  %d \n", lcm(42, 2));

	return (0);
}
```

<br>

> git log --oneline --graph --all 혹은 vscode git graph 로 merge와 rebase의 차이를 비교해보세요!

<br>
<br>
<br>