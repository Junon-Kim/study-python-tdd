# study-python-tdd
파이썬을 이용한 클린 코드를 위한 테스트 주도 개발 스터디

## 1장. 기능 테스트를 이용한 Django 설치
- Firefox Driver 대신 Chrome Driver를 쓸 경우 Chrome Driver를 다운로드하고 path를 잡아줘야 함. 
(https://sites.google.com/a/chromium.org/chromedriver/home)

- 6page ```django-admin.py startproject superlists```실행시 파이썬 버전은 높은데 책대로 Django 버전을 1.7로 설치하면 
 ```AttributeError: module 'html.parser' has no attribute 'HTMLParseError'```와 같은 에러가 발생함. Django 버전을 1.8로 변경하면 해결됨. 
 
 