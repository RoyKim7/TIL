# Git Command

> ​	Git 명령어 정리



### 0. init

- `git init`
- 최초에 한번만 하면 된다.
- `.git/` 폴더를 생성해준다.
- ![1](./GitCommand.assets/1.png)

(위는 처음에는 Desktop/TIL 다음에 (maters) 표시가 없었다. 그 이유는                 git 파일이 아니었기 때문에. 따라서 `git init` 을 쳐서 엔터 쳐줬다.)

(사진이 asset 폴더에 자동적으로 저장된 건, 수업시간에 우리가 파일 -> 환경설정에 들어가서 바꿔줬으므로 자동으로 저장.)



### 1. add

- `git add <추가하고 싶은 파일>`
  - `git add .` : 현재 폴더의 모든 파일과 폴더를 add
- working directory => staging area 로 파일 이동



### 2. config

- `git config --global user.email "myemail@gmail.com"`
- `git config --global user.name "myname"`
- 최초에 한번만 하면 된다.



### 3. commit

- `git commit -m "메세지"`
- 스냅샷을 찍는 동작
- add 되어있는 파일들을 하나의 묶음으로 저장
- 메세지에 들어가는 내용은 기능 단위로



### 4. remote

- `git remote add origin <주소>`
- 원격 저장소와 현재 로컬 저장소를 연결.



### 5.  push

- `git push origin master`
- 깃아 올려줘 origin으로 master를
- 원격 저장소에 로컬 저장소의 데이터를 전송



### 6. status

- `git status`
- 현재 git 상태로 출력