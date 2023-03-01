git branch 생성및 삭제


1. branch를 생성해봅시다.
```
git branch test
```
git branch <생성할 branch 이름>
위 명령어로 test branch를 생성했습니다.



```
git branch

* master
  test
```
git branch 명령어로 brach list를 조회해보니 기존에 있던 master branch와 새로 생성한 test branch가 확인됩니다.

 

 2. checkout 명령어를 이용하여 test branch로 이동합니다
  ```
  git checkout test
  ```


터미널에 git branch를 입력한다면 다음과 같이 나옴
```
  git branch

  master
* test
```

```
git commit program.pyp
```
program.py를 test branch에서 commit해줍니다.

 
이후
```
git merge test
```
merge 명령어를 이용하여 test branch의 수정사항을 master branch로 merge해줍니다.


```
git branch -d test
```
git branch -d <branch 이름>

위 명령어를 사용하면 -d 옵션이 branch를 삭제하라는 의미이므로 test branch를 삭제합니다.

보통 다 사용한 branch는 삭제하기 마련이니까요.