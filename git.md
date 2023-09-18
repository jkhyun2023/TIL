# GIT최초설정
사용자의 이름과 이메일 주소를 정해야 함.
commit을 할때마다, 한번 커밋 후 정보를 변경할 수 없음
$ git config--global user.name 'jkhyun'
$ git config --global user.email 'jk_117@naver.com'

## 로컬 명령어
1.`git init`   ==> .git directory(숨긴폴더)
    -`-git`  repository를 생성하는 명령어

2.`git add . <file name>`  ==> add라는 과정을 통해 무대위로,,
    -`working directory`에서 `staging area`로 추가하는 과정
    - 일반적으로 모든파일, 폴더를 한번에 추가하기 위해
      아래의 명령어로 작성

3.`git commit -m "first commit"`
            ==> commit를 통해 directory로 저장
    -   `staging area`에 올라간 파일들의 스냅샷을 찍어
        directory에 저장
    - git commit 에 -m 옵션을 넣어서 커밋메시지 추가
    -`git commit -m` ` "message" 어떤변경사항 있었는지 메시지~

## 원격저장소
-`git remote`  원격저장소 주소를 관리하기 위한 명령어
-`git remote add origin <url>`  https://github.com/jkhyun2023/TIL.git

-`git push` 원격저장소에 로컬코드를 업로드하기 위한 명령
- `git push <remote> <branch>`  remote이름을 origin으로 하지 않고 다른이름으로 했다면, 해당이름을 바꿔야
