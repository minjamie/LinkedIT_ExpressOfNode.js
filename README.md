# LinkedIT Front-end 소개

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

### 🤝 Back-end Repository

---

https://github.com/wecode-bootcamp-korea/fullstack2-2nd-Linked-IT-backend

<br/>

## 📑 구현 기능 상세

### 1. 공통 구현 사항

- Header
  - 로그인/회원가입 페이지로 이동하는 링크 구현
  - 상품 검색창 및 장바구니 아이콘 기능 구현
- NavBar
  - '전체 카테고리' 부분을 hover하면, 카테고리 네비게이션이 Dropdown되는 효과 구현
  - 카테고리 항목별로 click하면, 해당 카테고리의 상품 리스트 페이지로 이동하는 라우팅 기능 구현
- Footer
  - 정해진 시간에만 '채팅상담' 버튼 활성화 기능 구현 (그외 시간에 click하면, 경고창 Popup으로 대체)

### 2. Home/SignUp/SignIn 페이지

- 정규표현식을 활용하여 입력한 이메일/닉네임/비밀번호의 타당성 검사 기능 구현
- 회원가입 페이지에서 회원가입 성공 시, 로그인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, 메인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, Header의 '로그인/회원가입' 링크가 '로그아웃'으로 변경되는 기능 구현
- 로그인 페이지에서 로그인 실패 시, 경고창 Popup으로 로그인 실패 사실에 대한 알림 기능 구현

### 3. Feed(타임라인) 페이지

- 정규표현식을 활용하여 입력한 이메일/닉네임/비밀번호의 타당성 검사 기능 구현
- 회원가입 페이지에서 회원가입 성공 시, 로그인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, 메인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, Header의 '로그인/회원가입' 링크가 '로그아웃'으로 변경되는 기능 구현
- 로그인 페이지에서 로그인 실패 시, 경고창 Popup으로 로그인 실패 사실에 대한 알림 기능 구현

### 4. MyNetwork(인맥) 페이지

- 정규표현식을 활용하여 입력한 이메일/닉네임/비밀번호의 타당성 검사 기능 구현
- 회원가입 페이지에서 회원가입 성공 시, 로그인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, 메인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, Header의 '로그인/회원가입' 링크가 '로그아웃'으로 변경되는 기능 구현
- 로그인 페이지에서 로그인 실패 시, 경고창 Popup으로 로그인 실패 사실에 대한 알림 기능 구현

### 5. Jobs(채용공고) 페이지

- 정규표현식을 활용하여 입력한 이메일/닉네임/비밀번호의 타당성 검사 기능 구현
- 회원가입 페이지에서 회원가입 성공 시, 로그인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, 메인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, Header의 '로그인/회원가입' 링크가 '로그아웃'으로 변경되는 기능 구현
- 로그인 페이지에서 로그인 실패 시, 경고창 Popup으로 로그인 실패 사실에 대한 알림 기능 구현

### 6. MyProfile(이력서) 페이지

- 정규표현식을 활용하여 입력한 이메일/닉네임/비밀번호의 타당성 검사 기능 구현
- 회원가입 페이지에서 회원가입 성공 시, 로그인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, 메인 페이지로 이동하는 기능 구현
- 로그인 페이지에서 로그인 성공 시, Header의 '로그인/회원가입' 링크가 '로그아웃'으로 변경되는 기능 구현
- 로그인 페이지에서 로그인 실패 시, 경고창 Popup으로 로그인 실패 사실에 대한 알림 기능 구현

<br/>

### ※ References

---

- 본 프로젝트는 팀원들의 학습을 목적으로 [링크드인(LinkedIn)](https://www.linkedin.com/)을 참고하여 만들었습니다. 이 코드를 활용하여 상업적인 이득을 취하거나 무단으로 배포할 경우에는 법적으로 문제될 수 있습니다.
- 본 프로젝트에서 사용하고 있는 각종 이미지들은 [Unsplash](https://unsplash.com/) 등에서 무료로 배포 중인 이미지들로 대체하였습니다.
