
# Git
버전 관리 프로그램

개발 프로젝트에 대해 수정이 되었다는 사실을 기록하고 수정이 된 상태를 기록한다

### 사전작업
```
git config --global user.email "이메일"
git config --global user.name "이름"
```

## git 명령어
| 명령어 | 설명 |
| :------: | :------------: | 
| ```git init``` | 해당 디렉토리를 로컬 깃 저장소로 등록해줍니다. |
| ```git status``` | 지정된 저장소의 현재 상태를 나타내고, 상태 변경이 필요한 파일들을 알려준다. |
| ```git add <파일 이름>``` | 현재 작업 디렉토리의 파일을 스테이징 영역으로 이동시킨다. |
| ```git add --all``` | status에 나온 변경사항을 모두 스테이지에 올린다. |
| ```git commit -m "커밋 내용"``` | 의미있는 변경 작업들을 저장소에 기록하는 동작한다. |
| ```git restore --staged``` | 스테이지에 올린 파일을 되돌린다. |
| ```git reset <커밋 아이디>``` | 커밋을 취소하는 명령이다 |
| ```git clone <주소>``` | 원격의 Git 저장소를 통해 로컬에 복제해온다. |
| ```git log``` | 저장소의 커밋 히스토리를 시간순으로 보여준다. |
|```git log --oneline``` | 각 커밋을 한 라인으로 보여준다. |

### SSH 공개키 만들기
1. ```ssh-keygen```

2. ```cat .ssh/id_rsa.pub```

3. github > Settings > SSH and GPG Keys > SSH Keys 등록


### 원격 저장소 추가
```git remote add origin <Git 주소>```

### conflict가 발생했을 때
```git config pull.rebase false```

### 링크 연결하기
[이름](폴더 이름/파일 이름)

[주소에 대한 설명](주소)

- [하현상 - 등대](하현상-등대/README.md)

### git push/pull
git push를 할 단계라면 pull을 먼저 해보자. 다른 팀원이 작업을 진행해 이미 원격에서 merge됐을 수 있기 때문이다.