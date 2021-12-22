# --------------1. 초기설정----------------

1. git bash 설치(조건x)

링크))[gitbash설치](https://git-scm.com/downloads)


2. git bash 연결

 -git config --global user.name 계정


 -git config --global user.email 이메일 



- 만든파일에 git init 해주기

3. git clone하기

- 메인설정 

4. 코드수정하기

5. git commit 하기 

+ commit 메세지 규칙  ex)chore:코드수정

-feat : 새로운 기능에 대한 커밋


-fix : 버그 수정에 대한 커밋


-build : 빌드 관련 파일 수정에 대한 커밋


-chore : 그 외 자잘한 수정에 대한 커밋


-ci : CI관련 설정 수정에 대한 커밋


-docs : 문서 수정에 대한 커밋


-style : 코드 스타일 혹은 포맷 등에 관한 커밋


-refactor :  코드 리팩토링에 대한 커밋


-test : 테스트 코드 수정에 대한 커밋

6. git push 해주기


# --------------2. 기본 사용----------------

1. git pull 하기

2. 내용수정

3. git status 확인

4. git add

5. git commit

6. git log

7. git push  

# --------------3. branch 사용----------------

### brnach를 사용해야하는 이유

![branch 참고자료1](https://postfiles.pstatic.net/MjAyMTEyMjJfMjE2/MDAxNjQwMTUxNDg4NDgx.6O3QM60LyXEibU4MwhlNTXiDDbo0qfzV6cvHKNhyF10g.Dojn0rssuqL6gF9q8d64VA_PIr6NuWguXAPA0T32JVwg.PNG.paul5000/image.png?type=w773)



1. git branch 생성/업로드

    1. git branch 
    2. git branch 사용할 이름
    3. git checkout 사용할 이름 - branch 변경
    4. git pull origin 사용할 이름
    5. git status 깃 상태확인
    6. 내용수정
    7. git add 수정한 파일
    8. git commit -m "commit메세지:수정한 내용"
    9. git log --oneline 커밋확인
    10. git push origin 사용할이름

2. 수정내용 Merge
    1. 해당 repository pull request 해주기
    2. 상대방또는자신이 변경사항 Confirm 하기

3. 수정완료