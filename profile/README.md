
![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90)
## Hi there 👋

<<<<<<< HEAD
## 👨‍👩‍👧‍👦 취미 공유 플랫폼
- 모임을 만들고 사람을 찾을 수 있는 workshop
- 사람들과 같은 관심사를 가지고 소통할 수 있는 community
- 편리한 모임 합류를 위한 채팅, 지도, 결제 기능 제공
=======
**Here are some ideas to get you started:**
>>>>>>> 22f24c2a935cb4cc848b47720459e3aeb4c92ef3

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## 2주동안의 목표
### 1. 기능 다듬기
- 1. Article app 과 Workshop app 에서 Category 별 최신순, 인기순 정렬 기능
- 2. Chat app 읽은 채팅, 읽지 않은 채팅 식별과 채팅알림 기능
- 3. 

### 2. 목표 추가 기능

### 3. 수정될 디자인

### 4. 배포
- 1. 실시간 채팅을 위해 미들웨어 ASGI를 사용하여 Gunicorn으로 배포 불가능
- Daphne를 이용한 배포 시도 예정

### 5. 머신러닝
- 1. 사용자의 

Convention

1. 커밋 컨벤션
 - create : 생성
 - update : 수정
 - delete : 삭제
 - temp : 임시

 2. 네이밍 컨벤션

# URL name 패턴 이름에는 언더바(_)를 사용
url(...
name='add_topping')

# 클래스명은 CamelCase로 작성 (UserView)
class BlogWriter:
pass

# Variable, Function, Method의 이름은 underscore로 작성
def get_unique_voters():
pass

# Model Field 이름은 underscore로 짓습니다.
class Person(models.Model):
first_name = models.CharField(max_length=20)
last_name = models.CharField(max_length=40)

개발 환경
**개발언어** 
`JavaScript` `python 3.8`

**머신러닝 모델** 
(미정)

**데이터베이스** 
`SQLite3`

**개발환경** 
`djangorestframework 3.14.0`

<<<<<<< HEAD
- **배포환경** 
`docker` `Ubuntu Server 22.04` `PostgreSQL` `Daphne` `EC2`

# 🕖 중간 점검 2022_12_2 ~ 2022_12_14
## 남은 기간 목표
### 1. 기능 다듬기
- 📌 Article app 과 Workshop app 에서 Category 별 최신순, 인기순 정렬 기능(CRUD 다듬기)

### 2. 목표 추가 기능
- 📌 Kakao 지도 api를 이용한 워크샵 시행 위치를 사용자에게 직관적으로 제공
- 📌 소셜 로그인 도입으로 사용자 편의 증대
- 📌 아임포트를 이용한 결제 모델 추가 or kakao 네이버 결제 api 도입 목표
- 📌 Chat app 읽은 채팅, 읽지 않은 채팅 식별과 채팅알림 기능 추가
- 📌 django cron tab 을 이용한 실시간 인기 게시물 시간, 좋아요, 조회수의 점수를 조합하여 갱신

### 3. 수정될 디자인
- 📌 워크샵, 커뮤니티를 제외한 부분 전반적인 수정
- 📌 워크샵 커뮤니티 페이지 다듬기

### 4. 배포
- 📌 실시간 채팅을 위해 미들웨어 ASGI를 사용하여 Gunicorn으로 배포 불가능
- 📌 AWS 서버를 이용하여 Daphne를 이용한 배포 예정

### 5. 머신러닝
### 📌 비속어 필터링 모델 채팅 기능에 추가 예정













=======
**배포환경** 
`docker` `Ubuntu Server 22.04` `PostgreSQL` `Gunicorn` `EC2`
>>>>>>> 22f24c2a935cb4cc848b47720459e3aeb4c92ef3











- 와이어프레임
<img src="https://user-images.githubusercontent.com/113074921/207654055-4deed7a7-cf6e-452f-8746-f2442abe286c.png" width="700px" height="500px">

- ERD
<img src="https://user-images.githubusercontent.com/113074921/207654453-b67f223a-c317-4fea-837f-3d2d984530ae.png" width="700px" height="500px">
<img src="https://user-images.githubusercontent.com/113074921/207654666-9f69b4fb-1988-478e-9892-cde01d9c99ad.png" width="700px" height="500px">


- API 설계

https://www.notion.so/7b72107e734640e4b92d6305ec0db12b?v=082c5f8ae76f438ca4b50a4d304f509a

 
