# hicc_git_practice

## Git 기본 기능

- git init : 새로운 저장소 생성 (master branch)
- clone : github에서 저장소 받아오기
- add : 파일 추가
- commit : 내용 저장, 커밋(버전)의 생성 (HEAD에 반영)
- push : 원격 서버로 저장된 커밋을 올리기

### 브랜치(branch)

- 저장소 새로 만들면 기본으로 master branch 생성(main)
- checkout : 원하는 branch 생성 후 갈아타기

### pull & merge

- pull : 원격 저장소에 맞춰 로컬 저장소 갱신 (fetch + merge)
- merge : 다른 브랜치에 있는 내용 현재 브랜치에 병합(merge)
- 충돌 일어날 수 있음 -> git에서 충돌 부분 확인 후 파일 직접 수정
- 충돌 수정 후, git add (아까의 파일 병합)
- diff : 병합 전후로 어떻게 바뀌었는지 비교

## 로컬 저장소 구성 

- 작업 디렉토리(Working directory) : 실제 파일
- 인덱스(Index) : 준비 영역(staging area)
- HEAD : 최종 확정본(commit)