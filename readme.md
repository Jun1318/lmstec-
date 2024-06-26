<<<<<<< HEAD
# django 서버 구동하기
=======
django 서버 구동하기
=====================

github 연결하기
---------------
>>>>>>> 8b55cf6860de95dea4123cac5fb8175790b280f7

**mstec_django 리포지토리 생성 후 연결**

1. 내 컴퓨터와 GIT이 연결이 되어있는지 확인하기
$git config -- global user.email
$git conifg -- global user.name

2. github에서 리포지토리 만들기

3. 프로젝트 디렉토리에서 깃 시작하기
$ git init

4. 연결하기
'$ git remote add origin 'https://깃허브 리포지토리 주소'
연결후 확인하기'
'$ git remote -v'


<<<<<<< HEAD
## 2. Django 프로젝트 시작하기
=======
Django 프로젝트 시작하기
------------------------

>>>>>>> 8b55cf6860de95dea4123cac5fb8175790b280f7
1. 디랙토리 생성 후 이동하기
pwd : 현재 디렉토리 확인 
cd : 이동할 디렉토리
cd .. : 뒤로가기

2. 가상환경 생성(이놈이 중요)
'python -m venv myenv(얘는 그냥 이름 짓기 나름)'

3. 가상환경 실행
'$ source myenv/Scripts/activate'

4. 가상환경 끄기
'$ deactivate'

5. 가상환경 켜졌는지 확인 (venv) pip freeze 한번 해보자.

6. Django 다운로드
'$pip install django==4.2.4'

7. dashboard 프로젝트 생성
'$django-admin startproject dashboard .'  .<- 현재 디랙터리 / 내가 위치한곳

8. django 서버 실행하기(로켓 봐야함)
'$python manage.py runserver'
127.0.0.1:8000


기타 1. 작업을 한 뒤 형상관리(GIT)
----------------------------------

**작업을 한 뒤**   
'$ git add .'(내가 작업한 내용 모두를 staging area 올리겠다.)

'$git commit -m '커밋명' (커밋하기)
'$git push origin master (푸쉬하기)

-----------------------------------

숙제
====

20240626
----------

1. mtv 패턴 뭔지 알아보기(애는 100자로)
2. 관계형 데이터베이스 조금 더 이해해보기
3. 관계형 데이터베이스 종류들 그냥 한번 보기
4. SQL이 뭔지 알아보기
5. git 명령어 좀 고민해보기(나를 위해서)   + IDE

대략 50자정도로 각각 정리해오기.

일지
====

20240626
---------

1. c언어 문제 하나 품(구조체로 사각형 길이 + 선분 길이 구하기)
2. 파이썬 개념 익히기 (문자열 관련 기능, 자료형 - [] / () 등등의 형식 배움)
3. 마크다운 언어 익힘
4. 웹사이트 강의 - dashboard라는 프로젝트에 여러 어플리케이션들이 있고 밖에는 데이터베이스가 있으며, 어카운트라는 어플리케이션 안에 모델이라는 것이 데이터베이스와 연결되어있다. 데이터베이스애는 nosql과 rdbms가 있다는 것을 알게되었다. rdbms는 2차원 테이블이다.
