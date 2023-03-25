# 이력서

> 👔 2022년 4월부터 재직 중입니다. 현재 구직중이 아닙니다.

저는 소프트웨어 엔지니어 김종혁(Max)입니다. 주로 웹 클라이언트 제품을 만들고 운영해왔어요.

- email: hwaseen@gmail.com
- blog: https://maxkim-j.github.io
- github: https://github.com/MaxKim-J

## Work Experience

### [flex(2022.04 ~ 재직 중)](https://flex.team/)

> 사람과 조직에 관한 문제를 해결하는 Human Relations Platform

**웹 프론트엔드 엔지니어** : FE Platform Team 소속, flex 웹 제품 개발 생산성 향상 및 코드베이스 개선

### [모예(2021.01 ~ 2021.08)](https://thevc.kr/moye)

> 신인 패션 디자이너와 브랜드의 성공적인 런칭을 돕는 프리오더 서비스 (\*2022년 폐업)

**웹 프론트엔드 엔지니어** : 패션 프리오더 커머스 웹(React)/ 모바일(React Native) 애플리케이션 개발 및 유지보수, 3명 규모 FE 팀 테크리드 역할 수행

- 유연하고 작은 디자인 시스템이 필요했던 팀의 실정에 맞게, 제품팀 설득을 통해 확고한 분류 기준을 가진 Atomic Design System 기반의 디자인 시스템을 해체하고 UI 컴포넌트 디렉토리 구조를 개선했습니다.
- 모바일 앱을 로컬에서 빌드/배포하는 비효율적인 방식을 개선하기 위해, Github Actions, fastlane, codepush를 사용해 [React Native 모바일 앱 배포 파이프라인](https://maxkim-j.github.io/posts/react-native-ci-cd)을 구축했습니다.
- 웹 제품과 모바일 앱 제품의 같은 동작을 보장하기 위해, Redux와 Redux Saga를 이용해 store에 서버 비동기 요청 로직을 일원화하여 React 웹앱과 React Native 모바일 앱이 같은 Redux Store 코드를 공유하게 했습니다.
- Redux Saga 코드의 복잡함을 완화하고 비동기 요청 로직을 추가하는데 드는 시간을 단축하기 위해, 서버 비동기 요청에 대한 상태값, saga 함수 등을 모두 포함하게 되어 비대해진 Redux Store에 [Redux Toolkit을 도입](https://maxkim-j.github.io/posts/redux-store-structure)했습니다.
- 백엔드 개발이 끝난 후 프론트엔드 개발이 시작되는 폭포수 개발 사이클을 개선하기 위해, [OpenAPI Spec 기반 개발 방식](https://projectmaxkim.notion.site/0228-OpenAPI-46c3c26970b2407eb8c4b063bf0bff55)을 도입하고 open api 스펙을 별도의 git 레포지토리로 관리했습니다.

### [FREED GROUP(2020.07 ~ 2021.01)](https://www.freedgrouptech.com/)

> 글로벌 Chat Bot, 웹앱 솔루션

**웹 프론트엔드 엔지니어(인턴)** : 여행 추천 웹앱 / 문자 주문 솔루션 백오피스 등 Vue.js를 이용한 웹앱 SI 개발

- 백엔드 서버의 JSON 응답을 웹 제품에 맞게 명령적으로 가공하는 로직의 복잡성을 완화하기 위해, Typescript 객체를 메서드 체이닝 방식으로 수정할 수 있는 [functional-flattener](https://github.com/MaxKim-J/functional-flattener) npm 라이브러리를 제작해 배포하고 내부 어드민 제품에 적용했습니다.
- 웹 프론트엔드 팀이 2명에서 5명으로 늘어남에 따라 팀원간 동일한 이해를 보장하기 위해, 팀 컨벤션과 코드 리뷰 규칙 등의 내용을 담은 프론트엔드팀 위키 문서를 작성했습니다.

## Community

### Known Articles

- 브라우저 주소창에 URL을 치면 일어나는 일들: [GeekNews](https://twitter.com/GeekNewsBot/status/1491218802474127362)(2022.02.09)
- Suspense for Data Fetching의 작동 원리와 컨셉(feat.대수적 효과): [naver fe-news](https://github.com/naver/fe-news/blob/master/issues/2021-12.md)(2022.01.05)

### Presentations

- [[2022 피로컨퍼런스] 내가 FE를 좋아하는 이유](https://www.youtube.com/watch?v=8vKSx9KXddI)(2022.02.28)

### Contributions

- [facebookexperimental/Recoil#1584](https://github.com/facebookexperimental/Recoil/pull/1584): 공식 문서 한국어 번역 기여

### Study Group

- [주간기술동향](https://www.notion.so/d43fd4a132234c028ad3a1500c97c5b1): 다양한 도메인의 개발자들과 진행하는 주말 세션 스터디(2021.01.31~)

## Personal Projects

### 판례요지봇(2020.7 ~ )

법원 법령정보 웹사이트의 대법원 판례를 크롤링하여 판례요지를 주기적으로 트윗하는 트윗봇 서버, 판례 요지 본문을 조회할 수 있는 웹앱 개발 ([판례요지봇 트위터](https://twitter.com/precedent_bot) / [판례 보기 웹앱](https://supreme-court-tweet-bot.vercel.app/) / [프로젝트 레포지토리](https://github.com/MaxKim-J/supreme-court-tweet-bot))

- 첫번째 버전에서 달에 3만원 정도였던 EC2 + PSQL + Express 서버 과금을 줄이기 위해, firebase의 서버리스 함수와 데이터베이스를 사용해 서버 코드를 재작성했고 과금을 1000원대 수준으로 낮췄습니다.
- 판례 조회 웹앱의 최대한 빠른 페이지 로딩 성능을 유지하면서 서버에서 주기적으로 크롤링되는 최신 판례 정보를 업데이트하기 위해, Nextjs의 Incremental Static Regeneration을 이용해 최신 판례 정보를 크롤링 주기에 맞춰 정적 페이지로 생성해놓도록 했습니다.
- 트위터 봇 팔로워 450여명(2023.01.05)

### 외대 종강시계(2019.11 ~ )

한국외대 학생들에게 종강까지 남은 시간 정보와 학사공지 조회 등의 편의 기능을 제공하는 크롬 익스텐션 개발 ([웹 버전](http://hufs-semester-clock-web.s3-website.ap-northeast-2.amazonaws.com/) / [크롬 웹스토어](https://chrome.google.com/webstore/detail/%EC%99%B8%EB%8C%80-%EC%A2%85%EA%B0%95%EC%8B%9C%EA%B3%84/jadlpknbgnmmelikpcaogikohieafaem?hl=ko) / [웨일 스토어](https://store.whale.naver.com/detail/mckjnmgioalpnggjipjkmadnandhomei) / [프로젝트 레포지토리](https://github.com/MaxKim-J/hufs-semester-clock-v2))

- 웹과 크롬 익스텐션이라는 각 다른 환경에 배포할 수 있는 2개의 빌드 결과물을 생산하기 위해, webpack을 이용해 크롬 익스텐션 + 웹앱 보일러 플레이트를 직접 구현했습니다.
- [스크린 리더를 개발 과정에서 적극적으로 사용](https://maxkim-j.github.io/posts/web-accessiblity-virtuous-cycle)하며, 웹 표준과 웹 접근성을 준수한 마크업을 작성했습니다. (LightHouse 기준 접근성 100점)
- 크롬, 웨일 브라우저 포함 600여개 브라우저에 설치(2023.01.05)

## Interest

### 관심이 많은 기술적 문제

- 유저의 어렵고 복잡한 문제를 가장 쉽고 유려한 UI/UX로 풀어내는데 도전하는 웹 제품
- 높은 개발자 경험과 생산성을 유지하는 대규모 웹앱 개발 플랫폼 구축
- 적정 수준 엔지니어링과 장기적인 관점의 기술부채 관리 및 상환
- 가장 효과적인 방식의 문서화/기술 공유를 통한 원할한 엔지니어링 커뮤니케이션과 암묵지 줄이기

### 선호하는 조직과 팀

- 구성원들이 회사를 행복하게 다닐 수 없게 하는 장애물을 식별하고 제거하려하는 조직
- 구성원 모두가 같은 목표를 지향한다는데서 오는 상호 신뢰와 강력한 얼라인이 있는 조직
- 모든 종류의 제품/비즈니스 의사 결정에 제안과 지적이 열려있는 조직
- 모든 질문에 열려있으며, 엔지니어들이 언제나 필요한 시점에 적절한 도움을 주고 받을 수 있는 개발 조직
