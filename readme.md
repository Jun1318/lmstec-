django 서버 구동하기
=====================

github 연결하기
---------------

**mstec_django 리포지토리 생성 후 연결**

1. 내 컴퓨터와 GIT이 연결이 되어있는지 확인하기
$git config -- global user.email
$git conifg -- global user.name

2. github에서 리포지토리 만들기

3. 프로젝트 디렉토리에서 깃 시작하기
$ git init

4. 연결하기
$ git remote add origin 'https://깃허브 리포지토리 주소'
연결후 확인하기
'$ git remote -v'


Django 프로젝트 시작하기
------------------------

1. 디랙토리 생성 후 이동하기
pwd : 현재 디렉토리 확인 
cd : 이동할 디렉토리
cd .. : 뒤로가기

2. 가상환경 생성(이놈이 중요)
'python -m venv myvenv(얘는 그냥 이름 짓기 나름)'

3. 가상환경 실행
'$ source myvenv/Scripts/activate'

4. 가상환경 끄기
'$deactivate'

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
'$ git add,'(내가 작업한 내용 모두를 staging area 올리겠다.)

'$git commit -m '커밋명' (커밋하기)
'$git push origin master (푸쉬하기)
