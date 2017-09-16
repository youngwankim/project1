# Github 사용법
github 사용법을 기록
---

## 컴퓨터 내부
### 1. Github 시작하기
- `git init`
- git을 시작한다.

### 2. 파일 추가
- `git add [파일명]`
- 파일 하나 추가 
- `git add .`
- 모든 파일 추가
 
### 3. 저장하기(Commit)
- 저장/커밋 : `git commit -m "저장메세지"`

### 4. 저장기록 보기
- 저장 기록 : `git log`

### 5. 현재 상태 보기
- `git status`

## 원격저장소

### 6. 원격 저장소 추가하기
- Github에 저장소 만들기(new repository)
- 저장소 연결하기 : `git remote add [원격저장소 주소]`

### 7. 원격 저장소에 코드 밀어 넣기
- 코드 밀기 : `git push -u origin master`