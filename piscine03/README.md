[한국어](README.kr.md)
# Chapter Ⅰ<br>Instruction

- 내용
    - Fork the Piscine02 repository.
    - You can use `git push` to push to Github.
    - You always can restart the project if you didn't get the right result.
    - Commit with the message you want.
    - Try the command `git log --oneline --graph --all` and it will show you all the commits you've made.

<br>

- You should make a calculator on this project.
- This is a group project so you need at least one person in your team.

<br>
<br>
<br>
    
# Chapter Ⅱ<br>Exercise 00 : 브랜치로 협업해보기 - 계산기 만들기

| Turn-in directory | Files to turn in | Allowed commands |
|:--:|:--:|:--:|
| ex00/ | ./calculator | anything |

<br>

- Create a git graph same as picture01.
- Make a `dev` branch from `main` branch.
- Make these branches from the `dev` branch.
    - feature/plus : add feature
    - feature/minus : subtract feature
    - feature/multiple : multiplication feature
    - feature/divide : division feature
- Merge feature/* branches into the `dev` branch.
- Merge `dev` branch into the `main` branch.
- Your calculator should work well on the `main` branch.


<br>

### main function

```c
#include <stdio.h>

int plus(int n1, int n2);
int minus(int n1, int n2);
int mul(int n1, int n2);
int div(int n1, int n2);

int main(void)
{
    printf("plus : 4 + 2 = %d \n", plus(4, 2));
    printf("minus : 4 - 2 = %d \n", minus(4, 2));
	printf("mul : 4 * 2 = %d \n", mul(4, 2));
	printf("div : 42 % 2 = %d \n", div(42, 2));

	return (0);
}
```

<br>
<br>
<br>