[English](README.md)
# Chapter Ⅰ<br>Instruction

- 내용
    - 과제 레포지토리를 fork해서 사용하세요
    - 제출은 push를 통해서 진행할 수 있습니다.
    - branch, 커밋이 꼬인 경우에는 처음부터 다시 시작해야할 수 있습니다 ^_^
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
| ex00/ | ./calculator | anything |

<br>

- 위 그림과 같은 형태의 git graph를 만들어 보세요
- `main` 브랜치에서 `dev` 브랜치를 만듭니다.
- `dev` 브랜치에서 아래와같은 브랜치를 만듭니다.
    - feature/plus 브랜치에서는 덧셈 기능을 구현합니다.
    - feature/minus 브랜치에서는 뺄셈 기능을 구현합니다.
    - feature/multiple 브랜치에서는 곱셈 기능을 구현합니다.
    - feature/divide 브랜치에서는 나눗셈 기능을 구현합니다.
    - feature/square 브랜치에서는 제곱 기능을 구현합니다.
- `dev`브랜치에 feature/* 브랜치들을 rebase 하세요.
- `main`브랜치에 `dev` 브랜치를 merge 하세요.
- 계산기는 `main` 브랜치에서 정상적으로 작동해야 합니다.

<br>

### main function

```c
#include <stdio.h>

int plus(int n1, int n2);
int minus(int n1, int n2);
int multiple(int n1, int n2);
int divide(int n1, int n2);

int main(void)
{
    printf("plus : 4 + 2 = %d \n", plus(4, 2));
    printf("minus : 4 - 2 = %d \n", minus(4, 2));
	printf("multiple : 4 * 2 = %d \n", multiple(4, 2));
	printf("divide : 42 % 2 = %d \n", divide(42, 2));

	return (0);
}
```

> git log --oneline --graph --all 혹은 vscode git graph 로 merge와 rebase의 차이를 비교해보세요!

<br>
<br>
<br>