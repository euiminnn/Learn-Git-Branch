[English](README.md)
# Chapter Ⅰ<br>Instruction

- 과제 레포지토리를 fork해서 사용하세요
- 제출은 push를 통해서 진행할 수 있습니다.
- branch, 커밋이 꼬인 경우에는 처음부터 다시 시작해야할 수 있습니다.
- 제출 commit 메세지는 자유롭게 작성하시면 됩니다.
- 프로젝트 커밋, 브랜치의 시간순 현황은 `git log —-oneline —-graph —-all` 명령으로 간단하게 확인할 수 있습니다.



<br>
<br>
<br>
    
# Chapter Ⅱ<br>Exercise 00 : Fast-forword merge

| 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|
| ex00/ | answer.txt | git branch, git merge |

<br>

- `dev` 브랜치로 이동하고,
- `dev` 브랜치로 잘 이동되었는지 확인해보세요.
- answer.txt 라는 이름의 파일을 만들고, 이 파일에 `git branch` 했을때 보이는 결과를 넣어 제출해주세요.

<br>
<br>
<br>

# Chapter Ⅲ<br>Exercise 01 : 브랜치와 merge 확인해보기

| 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|
| ex01/ | answer.txt | git merge --merged, git merge --no-merged|

<br>

- 프로젝트에서 머지되지 않은 브랜치를 찾아서 main 브랜치에 머지해보세요.
- answer.txt 라는 이름의 파일을 만들고, 이 파일에 **`git merge --merged`를 실행한 결과**를 적어 제출해주세요.

<br>
<br>
<br>


# Chapter Ⅳ<br>Exercise 02: merge 취소하기

| 제출 디렉토리 | 제출 파일 | 허용 명령어 |
|:--:|:--:|:--:|
| ex02/ | answer.txt | git merge , git merge --abort|

<br>

- `feature` 브랜치를 `dev` 브랜치에 머지하세요.
- conflict가 나면, 적절한 명령어를 사용해서 되돌리세요.

<br>

! conflict가 난다고 해서 무조건 reset해야 하는 것은 아닙니다! 실수로 머지했는데 conflict가 난 경우에 사용해보세요!
