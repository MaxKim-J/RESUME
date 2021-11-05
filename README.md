# 이력서

![업뎃](https://img.shields.io/github/last-commit/MaxKim-J/RESUME?color=blue&label=updated&style=flat-square) ![구직중x](https://img.shields.io/badge/currently-unemployed-green)

> 👔 2022.2월 부터 구직 시작 예정입니다.  

> 📝 레포지토리 링크의 노션 이력서는 구직중일때만 공개됩니다!

## 프로필

<div align="center">
  <img src="https://maxkim-j.github.io/assets/img/52434807.jpeg" width="300">
</div>

- 이름 : 김종혁, Max Jonghyuk Kim
- 거주지 : 서울시 동대문구
- 생년월일 : 1996.09.20
- 이메일 : hwaseen@gmail.com


> [깃헙 프로필 : MaxKim-J](https://github.com/MaxKim-J)  

> [맥스킴 기술 블로그](https://maxkim-j.github.io/)

## 자기소개

프론트엔드 개발자입니다. 스타트업에서 React, Vue를 사용한 웹 클라이언트 개발과 
React Native를 사용한 모바일 클라이언트 개발을 경험했습니다.

공개된 다양한 지표들을 토대로, 제가 만드는 프로덕트가 비즈니스에 어떤 임팩트를 끼치는지 파악하는 것을 좋아합니다.
그래서 비즈니스 지표들이 많이 공개되어 있는 조직을 좋아합니다.

지식과 경험을 문서로 정리하는 것을 좋아합니다. 회사 재직 중 팀원들에게 제가 작성한 블로그 글, 공부한 내용
등을 정리해 공유하는데서 보람을 느꼈습니다. 지식과 경험을 보기 좋은 문서로 정리해 팀에게 
좋은 인사이트를 줄 수 있는 개발자가 되고자 합니다.

여러가지 업무 상황에서 발생한 문제에 대해, 상황에 맞는 최적의 방법을 찾고자 합니다.
집요하게 리서치하고 실험하며 해결책에 대해 검증하고, 동료 개발자들의 피드백을 얻는 것을 좋아합니다.

# 경력

## [모예(2021.01 ~ 2021.08)](https://moye.kr/)

> 신인 패션 디자이너와 브랜드의 성공적인 런칭을 돕는 프리오더 서비스 스타트업
- **프론트엔드 개발자** : React, React Native를 이용한 웹, 모바일 애플리케이션 개발
  - 모예 모바일 앱 애플리케이션(ios/android)
  - [모예 웹 애플리케이션](https://moye.kr/)

### 주요 업무 성과

- ESlint, Webpack Alias를 이용한 lint rule, path alias 도입으로 개발 용이성 재고
- Github Actions를 사용한 앱,웹 서비스 CI/CD 파이프라인 구축을 통한 팀 생산성 향상
  - 모바일 앱 배포 자동화 도구(fastlane, codepush)를 이용한 [React Native 모바일 앱 CI/CD 구축](https://maxkim-j.github.io/posts/react-native-ci-cd)
  - AWS(S3, CloudFront, Route53)를 이용한 React 웹앱 CI/CD 구축
- Redux Toolkit 도입하여 Redux, Redux Saga를 이용한 [상태관리, 비동기 요청 로직 리팩토링](https://maxkim-j.github.io/posts/redux-store-structure)
  - Redux Toolkit Slice, Saga Entity 패턴 도입을 통한 Redux 관련 로직 대폭 간소화
  - 각 컴포넌트에 흩어져있던 비동기 요청 상태들을 Redux Store로 일원화하여 코드 응집도 향상
- Git Submodule를 이용한 React와 React Native앱 간 공통 모듈 공유 전략 리서치 및 구현
- OpenAPI Spec 기반 개발 방식 도입하여 백엔드와 프론트엔드간 소통 향상
- React Native 빌드시 발생하는 오류 수집 및 문서화

## [FREED GROUP(2020.07 ~ 2021.01)](https://www.freed.group/)

> 홍콩과 상하이에 본사를 두고 있는 글로벌 Chat Bot, 웹앱 솔루션 스타트업
- **인턴 프론트엔드 개발자** : Nuxt.js, Vue.js를 이용한 반응형 웹 서비스, 백오피스 SI 개발 업무 수행
  - 자체 커머스 [아라 특가](https://ara.travelflan.com) UI 리뉴얼 작업
  - Topas 여행정보 TripCody 웹앱 개발
  - 10000Lab 커피 문자 주문 솔루션 백오피스 개발

### 주요 업무 성과

- [functional-flattener](https://github.com/MaxKim-J/functional-flattener) 라이브러리 제작 및 프로젝트에 적용하여 데이터 처리 로직 간소화
  - 서버가 보내주는 response 객체의 프로퍼티, 키의 casing 등을 method chaining을 통해 쉽게 수정할 수 있는 라이브러리
  - 명령형 프로그래밍으로 작성된 장황한 데이터 가공 로직 제거
- Git Flow, 코드리뷰 규칙 등의 내용을 담은 사내 프론트엔드팀 위키 문서 작성 및 공유

## 프로젝트

### [1. 판례요지봇](https://github.com/MaxKim-J/supreme-court-API)

개인 프로젝트 : 대한민국 법원 법령정보 웹사이트의 대법원 공개 판례를 크롤링하여 하루 3번씩 판례요지의 한 단락을 트윗하는 트윗봇

> 프로젝트 기간: 2020.7 ~ 유지보수 중  
스택: Server(Express.js, postrgreSQL, jest, twitter API), Client(React.js, Redux, Redux Saga)

- 트윗을 업로드하는 서버, 판례 요지 본문을 조회할 수 있는 웹 클라이언트, 서버리스를 이용한 트윗봇까지 총 3개 프로덕트 개발
- API 서버의 경우 jest, supertest를 이용해 49개의 유닛 테스트 작성
- [트윗봇 링크](https://twitter.com/precedent_bot), [판례보기 웹앱 링크](https://tweet-bot-client.vercel.app/), [판례요지 트윗봇 개발 후기](https://maxkim-j.github.io/posts/precedent-bot-retrospect)

### [2. 외대 종강시계](https://github.com/MaxKim-J/HUFS-Semester-Clock-Extension)

개인 프로젝트 : 한국외대 학생들에게 종강까지 남은 시간 정보와 학사공지, 학교 주변 날씨 정보를 조회하는 편의 기능을 제공하는 크롬 New Tab 확장앱

> 프로젝트 기간: 2019.11 ~ 유지보수 중  
스택 : Vue.js, Vuex, Sass/SCSS, Firebase Functions, Firebase Realtime Database

- Firebase Functions과 puppeteer로 학사 공지사항과 학교 주변 날씨 정보 등을 크롤링하는 웹 스크래퍼 구현
- Firebase DB에 데이터를 요청하는 횟수를 줄이고 로딩 성능을 개선하기 위해 chrome에서 제공하는 storage API 활용
- 현재 크롬/웨일 웹스토어 기준 530여개의 브라우저에 설치되어있으며, 2020년 3월 앱 출시 후 기능을 추가해가며 계속 유지보수 중
- 현재 직접 제작한 Webpack Boilerplate, React Query, Suspense for data Fetching등을 이용한 [2.0 버전 개발 중](https://github.com/MaxKim-J/hufs-semester-clock-v2)
- [구글 웹스토어 링크](https://chrome.google.com/webstore/detail/%EC%99%B8%EB%8C%80-%EC%A2%85%EA%B0%95%EC%8B%9C%EA%B3%84/jadlpknbgnmmelikpcaogikohieafaem?hl=ko),
[외대 종강시계 개발 후기](https://maxkim-j.github.io/posts/hufs-semester-clock)

## 활동

### 웹 개발 동아리 피로그래밍(2019.6~2020.2)

- 11기 회원으로 활동하며 다른 회원들과 Python과 Django 스터디를 진행했습니다.
- Django를 이용하여 오프라인 스터디를 관리하는 웹 서비스를 만드는 프로젝트를 진행했습니다.
- 2020년 1월부터 6개월여동안 12기 운영진으로 참여하며 12기 회원들을 대상으로 세션을 진행했습니다.
  - [Git과 Github 시작하기](https://maxkim-j.github.io/posts/git-start)
  - [Python Before Django(PBD)](https://colab.research.google.com/drive/1_xQfvy0w4Z3ogbbaO26V4hHrVEuWU2s1?usp=sharing)
  - [TypeScript와 React.js로 todo-list 만들기](https://www.notion.so/projectmaxkim/React-Essentials-4d320483511149bca7d216f621e81ec9) 

### 일요 기술 스터디(2021.1~)

- 저 포함 8명의 개발자들과 매주 일요일 오전 10시에 원격으로 기술 세션 스터디를 진행하고 있습니다.
- 한 달에 한 번 관심있는 기술적 주제를 조사해 45분 정도 되는 기술 세션을 진행합니다.
- [세션 자료 모음](https://projectmaxkim.notion.site/Max-19126f9a722b48bd89f3b11c530a23ac)

## 개인 공부(레포지토리)

### [Algo](https://github.com/MaxKim-J/Algo)

- 알고리즘 이론을 정리하고 Python, JavaScript로 알고리즘 풀이를 연습하는 레포지토리입니다.
- [Github Actions과 Slack을 연동](https://maxkim-j.github.io/posts/github-actions-slack-bot)하여 매주, 
매월 알고리즘 풀이 진척 사항을 개인 슬랙 알림으로 받고 있습니다.
- 커밋 규칙을 정하고 체계적으로 커밋하려 노력합니다.

### [client-advanced](https://github.com/max-kim-tutorial/client-advanced)

- 웹 클라이언트 관련한 개발 레퍼런스를 정리해놓는 레포지토리입니다.

### [max-kim-tutorial](https://github.com/max-kim-tutorial)

- 스택 학습을 위한 튜토리얼 레포지토리를 모아놓은 organization 저장소입니다.

## 주요 스택

- Client: HTML, CSS(SCSS), JavaScript(ES6+), TypeScript, Vue.js(+Nuxt.js, Vuex), React.js(+Redux, Redux Saga, Styled Components), Webpack, Rollup, Babel
- Server: Express.js, TypeORM
- Infrastructure : AWS S3, EC2, CloudFront, Route53, Firebase Functions(serverless)
- Test : puppeteer, jest, storybook

## 학력

**한국외국어대학교**

- 영어대학 영미문학 ・ 문화학과 
- 융복합소프트웨어 이중전공
- 2022.6 졸업 예정

## 병역

공군 병장 만기 전역(2016.12 ~ 2018.12)

## 지인 평가

> 지인 평가를 PR로 받고 있습니다.

### [신한결](https://github.com/Neulhan) - (피로그래밍 11기, 로앤굿 개발팀)

> 스스로 공부하고 성장할 줄 아는 개발자입니다. 주도적으로 완결된 프로젝트를 만들어낼 수 있는 역량을 가진 멋있는 개발자이기도 합니다. 종혁이형과 이야기를 나누면 늘 새로운 것을 배우게 됩니다.
