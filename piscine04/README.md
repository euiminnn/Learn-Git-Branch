[한국어](README.kr.md)
# Chapter Ⅰ<br>Instruction

- Fork the Piscine04 repository.
- You can use `git push` to push to Github.
- You always can restart the project if you didn't get the right result.
- Commit with the message you want.
- Try the command `git log --oneline --graph --all` and it will show you all the commits you've made.

<br>

- You should make a calculator for this project.
- This is a group project so you need at least one person in your team.

<br>
<br>
<br>
    
# Chapter Ⅱ<br>Exercise 00 : Make a calculator

| Turn-in directory | Files to turn in | Allowed commands |
|:--:|:--:|:--:|
| ex00/ | calculator | anything |

<br>

![](https://github.com/euiminnn/Learn-Git-Branch/blob/main/assets/p04example.png?raw=true)

- Create a git graph same as the above.
- Make a `dev` branch from the `main` branch.
- Make these branches from the `dev` branch.
    - feature/square : write a program which has **square** feature
    - feature/sqrt : write a program which has **square root** feature
    - feature/gcd : write a program which has **GCD** feature
    - feature/lcm : write a program which has **LCM** feature
- **Rebase** feature/* branches into the `dev` branch.
- Merge `dev` branch into the `main` branch.
- Your calculator should work well on the `main` branch.

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

> To see the difference, write a command `git log --oneline --graph --all` or try VScode git graph.

<br>
<br>
<br>