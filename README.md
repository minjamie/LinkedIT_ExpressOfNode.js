# LinkedIT -end 소개

- 비즈니스 전문 소셜 미디어 '[링크드인(LinkedIn)](https://www.linkedin.com/)'을 클론 코딩한 프로젝트입니다.
- 아래 이미지를 클릭하면, 본 프로젝트의 Demo 영상을 시청할 수 있습니다.
  [![[LinkedIT] Demo 영상](./public/images/readme_thumbnail.png)](https://vimeo.com/634975398)

### 🗓 기간

---

2021.10.25 ~ 2021.11.05 (12일)

### 🛠 기술

---

- `Front-end`: React, React-Hooks, React-Router, Styled-Component
- `Back-end`: Node.js, Express, MySQL, Prisma, Bcrypt, JWT, Jest

### 👨‍👩‍👧‍👦 Team Front-end

---

- [김시원](https://github.com/k-cool) : MyProfile(이력서) 페이지, User Card 컴포넌트
- [김재원](https://github.com/jambottle) : Home/SignUp/SignIn 페이지, Global Footer 컴포넌트
- [이성재](https://github.com/hanslee1) : TopNav(+검색창) 컴포넌트, Button 컴포넌트
- [한승완](https://github.com/han0gu) : MyNetwork(인맥) & Jobs(채용공고) 페이지, Company Card 컴포넌트
- [한지훈](https://github.com/JivenHan) : Feed(타임라인) 페이지, Floating Footer 컴포넌트

### 👨‍👩‍👧‍👦 Team Back-end

---

- [김민재](https://github.com/minjamie) : 초기 세팅 및 Database Model 구성 그리고 Search API & Jobs API & Feed API 구현
- [김재원](https://github.com/jambottle) : SignUp/SignIn API 및 소셜 로그인 구현
- [김진성](https://github.com/jsung1103) : Prisma Schema 작성 및 MyProfile API 구현

### 🤝 Front-end Repository

---

https://github.com/wecode-bootcamp-korea/fullstack2-2nd-Linked-IT-Frontend

### 🤝 MODELING DB DIAGRAM 
 
https://dbdiagram.io/d/6176b8da6239e14647819222 

### 🤝 API DOCUMENTARY

https://documenter.getpostman.com/view/17483034/UVC3jnpj

<br/>

## 📑 구현 기능 상세

### 1. Search(검색) API
- 검색하는 키워드에 해당되는 회사 + 회원 정보를 검색 창에 보여주는 API
- 해당 검색어로 검색하면 검색어와 관련된 유저와 회사 리스트를 3명씩 보여주는 API
- 검색 된 유저정보 더보기 버튼 클릭시 따라 페이지네이션을 위한 검색된 회원 수와 offset, limit이 설정된 API

### 2. Feed(타임라인) API
- 유저가 작성한 글과 친구 관계인 회원의 글 읽어오는 API
- 새로운 글 작성하는 API
- 작성한 글 업데이트 하는 API
- 본인이 쓴 글을 삭제하는 API
- 무한 스크롤을 위한 offset이 들어간 API

#### 2_1. 댓글 데이터 읽어오기, 만들기, 수정하기, 삭제하기 기능
- 포스트에 달린 모든 댓글과 총 갯수 읽어오는 API
- 새로운 댓글 작성하는 API
- 작성한 댓글 업데이트 하는 API
- 본인의 댓글을 삭제하는 API

#### 2_2. 포스트와 댓글에 달린 좋아요 기능
- 글에 달린 좋아요 생성 및 삭제하기 API
- 댓글에 달린 좋아요 생성 및 삭제하기 API


### 3. Jobs(채용공고) API
- 채용공고 리스트 API
- 채용공고 디테일 리스트 API
- 필터가 적용된 채용고고 리스트 데이터 API(포스팅 기간, 고용형태, 간편지원 여부, 근무형태, 회사명등의 필터링이 적용된) 
<br/>

### ※ References

---

- 본 프로젝트는 팀원들의 학습을 목적으로 [링크드인(LinkedIn)](https://www.linkedin.com/)을 참고하여 만들었습니다. 이 코드를 활용하여 상업적인 이득을 취하거나 무단으로 배포할 경우에는 법적으로 문제될 수 있습니다.
- 본 프로젝트에서 사용하고 있는 각종 이미지들은 [Unsplash](https://unsplash.com/) 등에서 무료로 배포 중인 이미지들로 대체하였습니다.
