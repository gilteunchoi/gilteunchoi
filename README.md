# 배워서 남 주는 개발자,  최길튼입니다
> 개발이 너무 재미있어서, 남들에게 직접 가르쳐주며 적극 권유해보고 있습니다.
> 

# 🙋 **About Me**


- 안녕하세요, 주니어 백엔드 개발자 최길튼입니다.
- 다른 사람들과 이야기하며 배우는 방식을 선호합니다.
    - 오프라인 스터디와 커피챗☕ 에 참여하는 것을 매우 좋아합니다.
    - 코딩교육 봉사 동아리 [코드코치](https://codecoach.imweb.me/)의 회장입니다, 대학교 새내기 시절부터 2년간 활동하고 있습니다.
- 내가 완벽해야 남에게 가르쳐 줄 수 있다고 생각하지 않습니다.
    - 완벽하지 않아도 가르쳐 줄 수 있고, 그 과정에서 성장하고자 노력합니다.

# 📞 Contact & Channel


- **Email | gilteunchoi@gmail.com**
- **Github | [https://github.com/gilteunchoi](https://github.com/gilteunchoi)**
- **Blog | [https://mailcar.com](https://mailcar.com)**

# 🛠 Skills


## Backend

- Java, Python
- Spring Boot, Spring Data JPA, Django
- Hibernate
- IntelliJ, Visual Studio Code
- Git, Github


## DevOps

- AWS (EC2, S3, RDS, IAM, Elastic Beanstalk, Lightsail)
- MySQL
- MySQL Workbench


## Collaboration

- Postman
- Slack, JANDI, Discord


# 💻 Work Experience & Projects


## 세차새차 백엔드 개발

[세차장 조회 및 예약 플랫폼] 2022.08 ~ 현재
- 팀 구성 | 스타트업 (파트타임 백엔드 1인 개발)
- 담당 기능 | SpringBoot와 MySQL를 활용한 REST API 서버
    - 주변 세차장 정보 조회 및 예약 기능
- 기능이 추가 될 때마다 생기는 수많은 DTO 클래스들을 쉽게 관리하기 위해 이를 Static Nested 클래스화 하여 코드 가독성을 높힘


## VISS 백엔드 개발

[W3의 [VISS표준](https://www.w3.org/TR/viss2-core/)을 따르는 IoT 차량 서버] 2021.08 ~ 2021.09
- 팀 구성 | 성균관대학교 IoT연구실 (풀타임 연구 인턴쉽)
- 담당 기능 | Django를 활용한 WebSocket API 서버
    - VISS표준을 따르는 가상의 차량 데이터 생성 기능
    - 큰 트리 구조를 가진 차량 데이터의 검색 기능
- 검색 구문에서 와일드카드 캐릭터를 지원하여야 했기 때문에 이를 재귀를 이용한 트리 검색 알고리즘에 적절히 반영함
- 주변의 다른 많은 차량들과 통신해야 하는 IoT 서버의 특성에 따라 WebSocket과 JWT를 이용하여 통신함으로써 다른 선택지였던 HTTP 세션 관리에 들어가는 자원을 절감함
- 총 3개월의 개발 일정을 1개월 가량 단축함.

# 📖 Personal Experience & Projects


## Elecvery 클론 백엔드 개발

[전기차 충전소 앱 클론] 2022.09 ~ 현재
- 팀 구성 | 3인 팀 (수업 텀 프로젝트 팀장)
- 담당 기능 | SpringBoot와 MySQL를 활용한 REST API 서버
    - Github의 Repository 메인테이너
    - 주변 충전소 정보 조회 및 예약 기능
- 상술한 세차새차 프로젝트와의 차별성을 위해 Github의 Project 관련 기능들을 적절히 활용하여 소통하고, 메인테이너로써의 역할에 중점을 둠
- Issue → PR → Review → Merge의 사이클을 통해 추후에 문제가 될 만한 변수명을 수정하거나, 패키지 구조를 변경하는 등의 더 나은 코드 품질을 유지할 수 있었음


## RustPython 오픈소스 기여

[Rust로 만드는 Python 인터프리터] 2022.07 ~ 현재
- 팀 구성 | 1인 개발 (오픈소스 컨트리뷰션 아카데미)
- 담당 기능 | String Formatter 버그 픽스 외 다수
- 기여 과정에서 해결이 어려운 부분을 기존 Cpython의 코드를 이해하고 이를 Rust로 이식하거나, GitLens 플러그인을 통하여 과거 소스코드 이력을 보며 구조를 파악하여 문제를 해결할 수 있었음
- OptionalOption [작성중]


## LoAlphaGo 디스코드 채팅봇

[게임(LostArk)이벤트 알림 디스코드 채팅봇] 2018.12 ~ 2019.03
- 팀 구성 | 1인 개발 (취미)
- 담당 기능 | Node.js를 활용한 Discord API 서버
    - 게임 이벤트 시점에 제공되는 채팅 알림 기능
    - 게임사 홈페이지 크롤링을 통한 공지사항 알림 및 캐릭터 정보 열람
- 한국어 및 영어 서비스, 알람 도달 유저 18,000명
- 서비스 개시 첫 일주일간은 Postman의 Mock Collection안에 추가 요청이 온 채팅방의 URL을 수작업으로 넣어가며 운영하였으나, 이후 폭발적인 유저 반응으로 수작업의 한계를 깨닫고 Node.js를 이용한, 자동 등록이 가능한 서버 구축
- 서버용 노트북을 베란다에 켜 두었으나 과열로 자꾸 서비스가 다운됨, 이후 AWS EC2로 서버를 이전하여 안정적인 서비스를 제공할 수 있었음
- 이후 AWS 자격증을 취득하고 개발의 길을 걷게 한 결정적인 서비스


# 🎓 Education

### 2022 오픈소스 컨트리뷰션 아카데미

- 2021.08 ~ 2021.10
- 정보통신산업진흥원 주관 오픈소스 멘토링 아카데미


### 부산대학교 정보컴퓨터공학부

- 2021.03 ~ 현재
- 4학기 재학 중
- 학점 평균 4.18 / 4.5
- 전공 평균 4.23 / 4.5


# 🎖 **Awards** & Certifications

- 2022.10 | 2022 오픈소스 컨트리뷰션 아카데미 과학기술정보통신부 장관상

- 2022.03 | AWS Certified Solutions Architect – Associate

- 2021.11 | 2021년도 한국통신학회 추계종합학술발표회 학부우수논문상

- 2021.11 | 부산대학교 Mini Kaggle 대회 “콩 세는 밤” 최우수상

- 2021.11 | 2021 MathWorks Korea MATLAB Cody Challenge 6등

- 2021.09 | 제 1회 Pusan National University Cody Challenge 1등

- 2021.06 | 제 1회 부산대학교 SW-AI 문제해결 경진대회 최우수상

- 2021.01 | 2021학년도 부산대학교 입학 전 소프트웨어교육 해커톤 최우수상

- 2019.05 | AWS Certified Cloud Practitioner


# 📄 Publication


> 박승렬, 최길튼, 홍진욱, 조환규, [곡식 알갱이 개수 추정 알고리즘 개발과 성능평가](https://github.com/gilteunchoi/gilteunchoi/blob/main/Grain-Seeds-Counting.pdf), IPIU 2022, Online, February 9-11, 2022.
> 

> Gilteun Choi, Seongreol Park, Jihyeon Lee, Jungwan Choy, and Jaehoon (Paul) Jeong, "[Wi-Fi Beacon-Based Localization for Guiding Visually Impaired Persons in Subway Stations](https://github.com/gilteunchoi/gilteunchoi/blob/main/WiFi-Beacon-Localization.pdf)", KICS-2021-Fall, **Best Student Paper Award**, Yeosu City, Korea, November 17-19, 2021.
>
