# Git Clone 이후 환경 설정

1. Git Clone 수행
2. python 가상환경 설정 및 requirements.txt를 활용한 python 패키지 설치
3. shortener 폴더 이름을 shortener_ex로 변경
4. shrinkers/settings.py의 AUTH_USER_MODEL과 INSTALLED_APPS에 shortener와 관련된 부분 주석 처리
5. python manage.py startapp shortener 명령어 수행
6. shrotener 폴더에 shortener_ex 폴더의 내용들을 모두 옮기기
7. shrinkers/settings.py의 AUTH_USER_MODEL과 INSTALLED_APPS에 shortener와 관련된 부분 주석 해제 처리
8. python manage.py makemigrations 명령어 수행
9. python manage.py migrate --run-syncdb 명령어 수행