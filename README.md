# 오늘 사용한 git 명령어

## git init
Git Repository 생성 및 폴더 초기화 한다.

```bash
git init
```

## git add [파일명]
git 저장소에 해당 파일을 추적한다.

```bash
git add .  # 모든 변경된 파일 추가
git add test.py # 특정파일 추가
```

## git commit
`git add`를 이용하서 추가한 파일들의 변경사항을 커밋한다.

```bash
git commit # 텍스트 에디터가 나오면서 변경사항을 입력할 수 있음
git commit -m "커밋 메세지"
```

## git push \[원격저장소] \[브렌치명]
로컬의 정보를 원격저장소에 반영한다.

```bash
git push
git push origin feature/README
```

