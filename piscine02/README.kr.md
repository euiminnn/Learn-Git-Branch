[English](https://github.com/euiminnn/Learn-Git-Branch/blob/main/piscine02/README.md)
# Chapter Ⅰ<br>Instruction

- 과제 레포지토리를 fork해서 사용하세요
- 제출은 **main 브랜치에서 push**를 통해서 진행할 수 있습니다.
- branch, 커밋이 꼬인 경우에는 처음부터 다시 시작해야할 수 있습니다.
- 제출 commit 메세지는 자유롭게 작성하시면 됩니다.
- 프로젝트 커밋, 브랜치의 시간순 현황은 `git log —-oneline —-graph —-all` 명령으로 간단하게 확인할 수 있습니다.



<br>
<br>
<br>
    
# Chapter Ⅱ<br>Exercise 00 : Fast-Forword merge

| 제출 브랜치 | 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|:--:|
| main | ex00/ | answer.txt | git branch, git merge |

<br>

- `main`에서 `dev00` 브랜치로 이동하세요.
- `dev00` 브랜치에서 원하는 만큼 커밋을 하세요.
- `main` 브랜치로 돌아가서 `dev00` 브랜치를 merge하세요.
- `git reflog` 명령어를 통해 두 브랜치간 merge가 Fast-Forword인지 확인하세요.
- answer.txt 라는 이름의 파일을 만들고, 이 파일에 `git reflog` 했을때 보이는 결과를 넣어 제출해주세요.

<br>
<br>
<br>

# Chapter Ⅲ<br>Exercise 01 : 브랜치와 merge 확인해보기

| 제출 브랜치 | 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|:--:|
| main | ex01/ | answer.txt | git branch --merged, git branch --no-merged|

<br>

- answer.txt 라는 이름의 파일을 만들고, 이 파일에 **`git branch --merged`를 실행한 결과**를 적어 제출해주세요.

<br>
<br>
<br>


# Chapter Ⅳ<br>Exercise 02: merge 취소하기

| 제출 브랜치 | 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|:--:|
| main | ex02/ | answer.txt | git merge , git merge --abort|

<br>

- `feature` 브랜치를 `dev01` 브랜치에 머지하세요.
- conflict가 나면, 적절한 명령어를 사용해서 되돌리세요.

<br>

! conflict가 난다고 해서 무조건 reset해야 하는 것은 아닙니다! 실수로 머지했는데 conflict가 난 경우에 사용해보세요!
