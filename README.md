# django_basic
django 기본익히기

# django 가상환경 만들기, 활성화
```
 conda create -n dj42_env python=3.12
 conda activate dj4_env
```

# django 라이브러리 설치
```
pip install django==4.2
pip show django
```

# django 프로젝트 생성
```
# doit_djngo 폴더 생성
django-admin startproject doit_django

# 현재 폴더에 프로젝트 생성
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
- 사용자 페이지 : http://127.0.0.1
- 관리자 페이지 : http://127.0.0.1/admin

# django 관리자 계정 생성
```
python manage.py createsuperuser
```