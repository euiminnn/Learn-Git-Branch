[한국어](https://github.com/euiminnn/Learn-Git-Branch/blob/main/piscine03/README.kr.md)
# Chapter Ⅰ<br>Instruction

- Fork the Piscine03 repository.
- You can use **`git push` at the `main` branch** to push to the server.
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

| Turn-in branch | Turn-in directory | Files to turn in | Allowed commands |
|:--:|:--:|:--:|:--:|
| main | ex00/ | calculator | anything |

<br>

![](https://github.com/euiminnn/Learn-Git-Branch/blob/main/assets/p03example.png?raw=true)

- Create a git graph same as the above.
- Make a `dev` branch from the `main` branch.
- Make these branches from the `dev` branch.
    - **Each team members should work on different branches.**
    - feature/plus : write a program which has **add** feature
    - feature/minus : write a program which has **subtract** feature
    - feature/multiple : write a program which has **multiplication** feature
    - feature/divide : write a program which has **division** feature
- **Merge** feature/* branches into the `dev` branch.
- Merge `dev` branch into the `main` branch.
- Your calculator should work well on the `main` branch.


<br>

* Example :

```c
#include <stdio.h>

int plus(int n1, int n2);
int minus(int n1, int n2);
int mul(int n1, int n2);
int div(int n1, int n2);
int square(int n);

int main(void)
{
    printf("plus : 4 + 2 = %d \n", plus(4, 2));
    printf("minus : 4 - 2 = %d \n", minus(4, 2));
	printf("mul : 4 * 2 = %d \n", mul(4, 2));
	printf("div : 42 % 2 = %d \n", div(42, 2));
    printf("square : 4 ^ 2 = %d \n", square(4));

	return (0);
}
```

<br>
<br>
<br>