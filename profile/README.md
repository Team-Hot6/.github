
![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=🐤Togeduck%&fontSize=90)
# 👋 We are Team-Hot6 

Convention

## 커밋 컨벤션
 - create : 생성
 - update : 수정
 - delete : 삭제
 - temp : 임시

## 네이밍 컨벤션

### 🧲 URL name 패턴 이름에는 언더바(_)를 사용
url(...
name='add_topping')

### 🧲 클래스명은 CamelCase로 작성 (UserView)
class BlogWriter:
pass

### 🧲 Variable, Function, Method의 이름은 underscore로 작성
def get_unique_voters():
pass

### 🧲 Model Field 이름은 underscore로 
class Person(models.Model):
first_name = models.CharField(max_length=20)
last_name = models.CharField(max_length=40)

## 개발 환경
- **개발언어** 
`JavaScript` `python`

- **머신러닝 모델** 
(미정)

- **데이터베이스** 
`SQLite3`

- **개발환경** 
`djangorestframework 3.14.0`

- **배포환경** 
`docker` `Ubuntu Server 22.04` `PostgreSQL` `Daphne` `EC2`

# 🕖 중간 점검 2022_12_2 ~ 2022_12_14
## 남은 기간 목표
### 1. 기능 다듬기
📌 Article app 과 Workshop app 에서 Category 별 최신순, 인기순 정렬 기능(CRUD 다듬기)
📌  

### 2. 목표 추가 기능
📌 Kakao 지도 api를 이용한 워크샵 시행 위치를 사용자에게 직관적으로 제공
📌 소셜 로그인 도입으로 사용자 편의 증대
📌 아임포트를 이용한 결제 모델 추가 or kakao 네이버 결제 api 도입 목표
📌 Chat app 읽은 채팅, 읽지 않은 채팅 식별과 채팅알림 기능 추가

### 3. 수정될 디자인
📌 워크샵, 커뮤니티를 제외한 부분 전반적인 수정
📌 워크샵 커뮤니티 페이지 다듬기

### 4. 배포
📌 실시간 채팅을 위해 미들웨어 ASGI를 사용하여 Gunicorn으로 배포 불가능
📌 AWS 서버를 이용하여 Daphne를 이용한 배포 예정

### 5. 머신러닝
📌 비속어 필터링 모델 채팅 기능에 추가 예정
























- 와이어프레임
![image](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68728092-c939-4531-8b45-ebc866885360/Untitled.png)

-ERD
![image](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68728092-c939-4531-8b45-ebc866885360/Untitled.png)

-API
 https://www.notion.so/7b72107e734640e4b92d6305ec0db12b?v=c88e7821924c401ea4e8f2f9372e70f1