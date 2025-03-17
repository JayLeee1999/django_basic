# django_basic
django 기본 익히기
# django 가상환경 만들기, 활성화
```
mkdir django4_ex
cd django4_ex
conda create -n dj4_env python=3.12
conda activate dj4_env
cd django_basic
code .
```
# django 라이브러리 설치
```
pip install django==4.2
pip show django
```
# django 프로젝트 생성
```
django-admin startproject doit_django .
```
# django 기본 DB 생성
```
python manage.py migrate
```
# django 서버 실행
```
python manage.py runserver
```
# django 관리자 계정 생성
``` 
python manage.py createsuperuser
```
id: admin, pw: 8자리 이상 > 서버 주소 뒤에 /admin 입력해서 접속