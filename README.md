# git.comment

# git 설치 --> 기본값으로 그대로 설치했음

# 시작버튼에서 Git Bash 열기 (실행)

```
 git config--global user.name"hodumaru
```
```
 git config--global user.name"hodumaru
```
# git hub 가입시 입력한 이메일과 동일해야한다.
 git config --global user.email "karen9716@naver.com"

 # 정보 확인하기
 git config --list

 ![image](https://github.com/hodu97/git.comment/assets/145514463/7176887f-369b-4528-8636-25587e0cdf59)


☝️ 위의 내용은 컴퓨터에 한번만 설치하면 된다
--------------------------------------
--------------------------

#github에 코드 업로드 하기 🥦

1. 초기화

   ```
  git init
  ```
# .git이라는 폴더가 생성

2. 파일올리기
```
git add .
```
3. 히스토리 만들기
```
git commit -m "내가 적고싶은 메세지 적으면 됨"
```
# 메세지에는 한글이 가능함
# -m 메세지의 줄임말

4. Github repository랑 내 로컬 프로젝트랑 연결 (깃업에 프로젝트를 올릴 repository를 먼저 만들어야한다 )
# 아래 주소는 깃업에서 만든 repository에서 복사해서 가져와야한다(repository를 만들때 readme 선택하지 말기)

```
git remote add origin https://github.com/hodu97/webstandard.git
```
![image](https://github.com/hodu97/git.comment/assets/145514463/6e227e3e-07c9-4ef7-b628-fb6a29432b3e)

5. 잘 연결되었는지 확인 (필수 아님)
```
git remote -v
```

6. Github에 자료 올리기
```
git push origin master
```
# ☝ 여기까지 하면 Github의 repository에 자료가 올라가 있다.
