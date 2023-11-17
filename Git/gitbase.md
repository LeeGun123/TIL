
## Git
버전 관리 프로그램

개발 프로젝트에 대해 수정이 되었다는 사실을 기록하고 수정이 된 상태를 기록한다

### 사전작업
```
git config --global user.email "이메일"
git config --global user.name "이름"
```

| git init | 해당 디렉토리를 로컬 깃 저장소로 등록해줍니다. |
| git status | 지정된 저장소의 현재 상태를 나타내고, 상태 변경이 필요한 파일들을 알려준다. |
| git add <파일 이름> | 현재 작업 디렉토리의 파일을 스테이징 영역으로 이동시킨다. |
| git add --all | status에 나온 변경사항을 모두 스테이지에 올린다. |
| git commit -m "커밋 내용" | 의미있는 변경 작업들을 저장소에 기록하는 동작한다. |
