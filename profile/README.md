
![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90)
## Hi there 👋

**Here are some ideas to get you started:**

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

**배포환경** 
`docker` `Ubuntu Server 22.04` `PostgreSQL` `Gunicorn` `EC2`




























- 와이어프레임
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68728092-c939-4531-8b45-ebc866885360/Untitled.png)

-ERD
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68728092-c939-4531-8b45-ebc866885360/Untitled.png)

-API
 https://www.notion.so/7b72107e734640e4b92d6305ec0db12b?v=c88e7821924c401ea4e8f2f9372e70f1