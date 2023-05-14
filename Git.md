# 초기세팅


### 1. Git 설치하기 [다운로드사이트](https://git-scm.com)
### 2. Git 저장소 만들기
새로운 프로젝트를 시작할 때 Git 저장소를 새로 만드는 명령어
```
git init
```

### 3. vs code에 계정 등록하기
- 사용자 이름
```
git config --global user.name 'Ls-Des'
```
- 사용자 이메일
```
git config --global user.email 'kyh9827@lscompany.co.kr'
```

<br>

# 신규 프로젝트 생성
### 1. 레파지토리 추가하기
- 자사사이트(원격저장소이름: origin)
```
git remote add origin https://github.com/LS-Des/lscompany.git
```
### 2. 버전만들어서 파일 업로드
- 업로드파일 선택 (전체파일 올릴려면 git add . / 부분 올릴려면 git add 파일명)
```
git add .
```
- 버전 생성 (git commit -m '버전관련 메세지내용작성')
```
git commit -m '메인페이지 시작'
```
- 데이터 올리기 (git(깃) push(밀어넣어라) origin(1번에 추가한 레파지토리 원격저장소이름의) main(브랜치에)
```
git push origin main
```
- 로그인하기

<br>

# 기존 프로젝트에 브랜치 추가하기
- 나무가지 기둥 : "main or master" <-네이밍 거의 고정, 자사사이트 메인페이지 / 뻗어나가는 가지 네이밍 자유 ex)시스템,브랜드마케팅,상품팀,디자인팀 페이지등등 
### 1. 브랜치 만들기
ex) 디자인개발페이지 브랜치 만들기 (design은 만들고자하는 브랜치 이름을 의미함)
```
git branch design
```
### 2. 해당 프로젝트 브랜치로 변경
```
git checkout design
```
### 3. 데이터 올리기
- 업로드파일 선택 (전체파일 올릴려면 git add . / 부분 올릴려면 git add 파일명)
```
git add .
```
- 버전 생성 (git commit -m '버전관련 메세지내용작성')
```
git commit -m '디자인개발페이지 시작'
```
- 데이터 올리기
```
git push origin design
```

<br>

# 복제
### 1. 클론
```

```
