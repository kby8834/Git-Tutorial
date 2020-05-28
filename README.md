# Git-Tutorial

## 테이블
명령어|설명
---|---|
git config --list| 설정 목록
git config --global https.proxy http://ip:port|Proxy 설정
git config --global http.proxy http://ip:port|Proxy 설정
git config --global http.sslVerify false|ssl 설정
git config --global --unset http.proxy|설정 초기화
git init|Repository 초기화
git add 파일명|인덱스에 등록
git commit -m "설명"|Commit
git remote add origin "Repository URL"|원격 주소지에 추가
git remote update|원격의 branch를 찾지 못할 경우 갱신
git push u origin master|Push
git push remoteName branchName|Push
git pull|최신 코드 받아 Merge
git fetch|최신 코드 받음
git reset --hard|commit 취소
git reset --soft|코드는 유지하고 commit 취소
git reset merge|merge 취소
git stach / git stash save "설명"|작업코드 임시저장하고 branch 변경
git stash pop|마지막으로 임시 저장한 코드 가져오기
git clone https://github.com/kby8834/git-tutorial.git|Repository 복사
git branch|branch 목록
git branch -r|원격 branch 목록
git branch -a|로컬 branch 목록
git branch live-chat|branch 생성
git branch -d branchname| branch 삭제
git checkout live-chat|사용할 branch 지정

## 글자 크기
### 글자 크기
#### 글자 크기
##### 글자 크기
###### 글자 크기
####### 글자 크기

## 강조
**안녕**하세요

## 기울임
***안녕***하세요

## 취소선
공부하기 ~~싫다~~

## 목록
* 목록 1
* 목록 2
  * 목록 2-1
    * 목록 2-1-1

## 인용
>안녕하세요
>> 반갑습니다.

## 테이블
이름|직업
---|---|
K|프로그래머

## 소스코드
```java
public class Tutorial {

}
```
```c
#include <stdio.h>
int main(void) {
  printf("Hello World!");
  return 0;
}
```

## 링크
[GitHub](https://github.com/)
