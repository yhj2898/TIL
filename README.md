# TIL Day 01
## 1. Git Intro
> Git : (분산) 버전 관리 프로그램

### Git를 이용한 버전관리
- 목적 : 백업, 복구, 협업
    - 백업 : 과거의 자료들도 저장
    - 복구 : 예전 버전의 모습 보여줌
    - 협업 : 변경사항에 육하원칙 기술
  

### Github를 이용한 포트폴리오
- Git를 사용하는 프로젝트의 협업을 위한 웹호스팅 서비스
- 포트폴리오를 자랑할 수 있는 공간

## 2. CLI 기초
### GUI vs CLI
- GUI : 그래픽을 통해 사용자와 컴퓨터가 상호작용하는 방식
- CLI : 터미널을 통해 사용자와 컴퓨터가 상호작용 하는 방식
  - GUI는 CLI에 비해 쉽지만 단계가 많고 컴퓨터의 성능 더 많이 소모

### 터미널 명령어


| 명령어 |              설명               |
| :----: | :-----------------------------: |
| mkdir  |            폴더 생성            |
| touch  |            파일 생성            |
|   ls   |   현재 폴더의 파일 목록 출력    |
|   mv   |폴더/파일을 다른 폴더 내로 이동 or 이름 변경|
|   cd   |        다른 폴더로 이동         |
|   rm   | 파일 삭제 / 폴더 삭제 (-r 옵션) |
| strt | 폴더/파일 열기|
  
### 터미널 명령어 예시

```bash
$ mkdir test

$ touch a.txt

$ ls
$ ls -a

$ cd ..
$ cd test

$ rm a.txt
$ rm -r test
```

## 3. Visual Studio Code
> Visual Studio Code (비주얼 스튜디오 코드)는 마이크로소프트에서 개발한 텍스트 에디터의 한 종류이다.

### 장점

- Windows, Mac, Linux 운영체제를 모두 지원한다.
- 기존 개발 도구보다 빠르고 가볍다.
- Extension을 통해 다양한 기능을 설치할 수 있어서, 무한한 확장성을 가진다.
- 무료로 사용 가능하다.

### Git Bash 연동하기

1. 터미널을 연다. (Ctrl + `)
2. 화살표를 누르고 *Select Default Profile*을 클릭한다.
3. Git Bash를 선택한다.
4. 휴지통을 눌러서 터미널을 종료하고, 재시작한다.
   - 휴지통은 Kill Terminal 로써, 터미널 자체를 아예 종료한다.
   - 닫기는 Close Terminal 로써, 터미널을 종료하지 않고 창만 보이지 않게 만든다.
5.  기본 터미널이 Git Bash로 열리는지 확인한다.


## 4. Markdown
> Markdown (마크다운)은 일반 텍스트 기반의 경량 Markup (마크업) 언어이다.

### Markup (마크업) 이란?

- 마크(Mark)로 둘러싸인 언어를 뜻한다. 마크란 글의 역할을 지정하는 표시이다.
- HTML도 마크업 언어인데, 글에 제목의 역할을 부여할 때 `<h1>제목1</h1>` 과 같이 작성한다.

### 마크다운의 장점과 단점

1. 장점
   - 문법이 직관적이고 쉽다.
   - 지원 가능한 플랫폼과 프로그램이 다양하다.
2. 단점
   - 표준이 없어서 사용자마다 문법이 상이하다.
   - 모든 HTML의 기능을 대신하지는 못한다.

### 주의 사항

- 마크다운의 본질은 글에 **역할**을 부여하는 것이다.
- 반드시 역할에 맞는 마크다운 문법을 작성한다. 글씨를 키우고 싶다고 해서 본문에 제목의 역할을 부여하면 안된다.

### 주요문법
1. 강조
     - 기울임 : `*글자*` or `_글자_`
     - 굵게 : `**글자**` or `__글자__`
     - 취소 : `~~글자~~`

2. 코드
    - 인라인 코드 : `inline code`처럼 백틱을 통해 코드를 감싸줌
        - 파이썬의 print는 `print("Hello World!")`
  - 블록코드 : ```python``` 처럼 백틱을 3번 입력하고 코드의 종류 작성
      ```bash
      $ touch test.txt
      ```

3. 링크
    - [표시할 글자](이동할 주소)
    - [GOOGLE](https://google.com)

4. 이미지
    - ![대체 텍스트](이미지 주소)
    - ![Git로고](data:image/png;base64,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)

5. 인용
    - `>` 사용

6. 표
    - 파이프(|)와 하이픈(-)을 이용해 행/렬 구분  
  
| 동물 | 종류 | 다리 개수 |
| :----: | :----: | :----: |
|사자|포유류|4개|
|닭|조류|2개|
|도마뱀|파충류|4개| 

## 5. Git 기초
### 1. Git 초기 설정
> 누가 커밋 기록 남겼는지 확인할 수 있도록 최초 한 번만 설정

```bash
git config --global user.name "이름"
git config --global user.email "메일주소"
```

### 2. 로컬 저장소
- working directory : 일반적 작업이 일어나는 곳
- staging area : 커밋을 위한 파일 및 폴더가 추가되는 곳
- repository : staging area에 있던 파일 및 폴더의 변경사항(커밋)을 저장하는 곳
- Git은 working directory -> staging area -> repository 과정으로 버전 관리 수행

### 3. git 기본 명령어

#### (1) git init
- 현재 작업중인 디렉토리를 Git으로 관리한다는 명령어
  
#### (2) git status
- 파일의 현재 상태 알려줌
  
#### (3) git add
- working directory에 있는 파일을 staging area로 올리는 명령어
#### (4) git commit
- staging area에 올라온 파일의 변경사항을 하나의 버전(커밋)으로 저장하는 명령어
#### (5) git log
- 커밋의 내역 조회
- `--oneline` : 한 줄로 축약해서 보여줌

## 6. GitHub
### 1. 원격저장소
- Github의 원격저장소를 이용해 내 컴퓨터의 로컬 저장소를 다른 사람과 공유

### 2. 로컬저장소와 원격저장소 
1. 원격저장소 생성 후 저장소의 주소 복사
2. TIL 폴더에서 vscode 실행
3. git init 통해 TIL 폴더를 로컬 저장소로 만들기
`git init`
4. git remote : 로컬저장소에 원격 저장소를 등록, 조회, 삭제할 수 있는 명령어

    (1) 등록 : git remote add <이름> <주소>  
`git remote add origin <https:// ~>`

    (2). 조회 : `git remote -v`
    (3) 삭제(로컬과 원격 저장소의 연결 끊음) : `git remote rm <이름>` or `git remote remove <이름>`
    > `git remote rm origin` or `git remote remove origin`

### 3. 원격 저장소에 커밋 업로드

1. 로컬 저장소에 커밋 생성
`git status`  
`git add day1.md` 
`git commit -m "Upload TIL Day1"`  
`git log --oneline`

2. git push : 로컬 저장소의 커밋을 원격 저장소에 업로드
   
`git push <저장소 이름> <브랜치 이름>`
> `git push origin master`


### 예시
```bash
LG@DESKTOP-NQ8EVCE MINGW64 ~/hello 
$ git init
Reinitialized existing Git repository in C:/Users/LG/hello/.git/

LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git add README.md

LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git commit -m "add README.md"
[master 97f2760] add README.md
 1 file changed, 1 insertion(+), 1 deletion(-)

LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git log --oneline
97f2760 (HEAD -> master) add README.md
c16dd87 (origin/master) add README.md
651e8fc add README.md

LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git remote add origin https://github.com/yhj2898/hello.git
error: remote origin already exists.

LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git remote -v
origin  https://github.com/yhj2898/hello.git (fetch)
origin  https://github.com/yhj2898/hello.git (push)

LG@DESKTOP-NQ8EVCE MINGW64 ~/hello (master)
$ git push origin master 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 286 bytes | 143.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/yhj2898/hello.git
   c16dd87..97f2760  master -> master
   ```