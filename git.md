# GIT최초설정
사용자의 이름과 이메일 주소를 정해야 함.
commit을 할때마다, 한번 커밋 후 정보를 변경할 수 없음
$ git config--global user.name 'jkhyun'
$ git config --global user.email 'jk_117@naver.com'

## 명령어
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
