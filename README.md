## 개발자의 품격 : 제품 판매 웹앱 구현(부트스트랩 + Vue.js + Node.js + MariaDB)
[thank you very much-개발자의 품격 #바로가기](https://www.youtube.com/watch?v=9nDLGbtcn-A&list=PLqbWuGdVBJd38FoWC6IG__QlzBtYoqyfp&index=3)
### 1. 제품 판매웹앱 구현 - 무엇을 만들것인가?

### 2. 부트스트랩 기본 익히기

### [3. 제품 리트스 페이지 구현](https://www.youtube.com/watch?v=9nDLGbtcn-A&list=PLqbWuGdVBJd38FoWC6IG__QlzBtYoqyfp&index=3)
- 부트스트랩 기반 판매리스트 html 하드코딩 구현! 

### [4. 제품 상세 페이지 구현](https://www.youtube.com/watch?v=QcNiaDrp2kQ&list=PLqbWuGdVBJd38FoWC6IG__QlzBtYoqyfp&index=4)
- 부트스트랩 기반 제품상세 페이지 html 하드코딩 구현!

### [5. 제품 등록 페이지 구현](https://www.youtube.com/watch?v=nCuHP7zgELY&list=PLqbWuGdVBJd38FoWC6IG__QlzBtYoqyfp&index=6)
-  부트스트랩 기반 제품등록 페이지 html 하드코딩 구현!

### [6. MariaDB 설치하기](https://www.youtube.com/watch?v=kLdHp6zrPJE&list=PLqbWuGdVBJd38FoWC6IG__QlzBtYoqyfp&index=6)
- 도커를 이미지를 이용한 마리아 디비 설치!
```
# 도커 마리아디비 다운로드 (최신버전)
docker pull mariadb

# 이미지 확인하기
docker image ls

# 도커 컨테이너 실행(-d:백그라운드 실행, -p: 포트 3306:3306, -e: 환경변수(패스워드설정)MYSQL_ROOT_PATHWORD=mariadb 이름:mariadb)
docker run --name mariadb -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=mariadb


```