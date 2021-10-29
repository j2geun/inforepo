## git 저장소 만들기
```bash
git init
```

## 기존 저장소 clone
```bash
git clone url dir_name
git clone user@server:path/to/repo.git #ssh를 이용해 clone
```
## git 상태 확인
```bash
git status
```

## 파일 수정 후 github 저장소에 올리기
```bash
git add git.md
git commit -m "git" git.md
git push origin master # maser 브랜치를 origin 서버에 Push 하는 것
```
clone 하면 보통 자동으로 origin 이름이 생성된다.
clone 한 사람이 여러명 있을 때 다른 사람이 Push 한 후에 Push 하려고 하면 Push 할 수 업사. 먼저 다른 사람이 작업한 것을 가지고 와서 Merge한 후에 Push 할 수 있다.