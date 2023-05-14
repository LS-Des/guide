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

# 신규
### 1. 레파지토리 추가하기
- 자사사이트(원격저장소이름: origin)

```
git remote add origin https://github.com/LS-Des/lscompany.git
```

- 투어패스몰(원격저장소이름: 미정)

```
git remote add 미정 https://github.com/LS-Des/tourpass.git
```
### 2. 브랜치 만들기

ex) 디자인개발페이지 브랜치 만들기 (design은 만들고자하는 브랜치 이름을 의미함)
```
git branch design
```
### 3. 해당 프로젝트 브랜치로 변경
```
git checkout design
```
### 4. 데이터 올리기
- 업로드파일 선택 (전체파일 올릴려면 git add . / 부분 올릴려면 git add 파일명)
```
git add .
```
- 버전 생성 (git commit -m '버전관련 메세지내용작성')
```
git commit -m '디자인개발페이지 시작'
```
- 데이터 올리기 (앞전 1번에 추가한 레파지토리 원격저장소이름, 브랜치에 데이타 올려라)
```
git push origin design
```

# 복제
### 1. 클론
```

```
