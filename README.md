# 이력서

> 👔 2022년 4월부터 재직 중입니다. 현재 구직중이 아닙니다.

저는 소프트웨어 엔지니어 김종혁(Max)입니다. 주로 웹 클라이언트 제품을 만들고 운영해왔어요.

- email: hwaseen@gmail.com
- blog: https://maxkim-j.github.io
- github: https://github.com/MaxKim-J

## Work Experience

### [flex(2022.04 ~ 재직 중)](https://flex.team/)

> **사람과 조직에 관한 문제를 해결하는 Human Relations Platform, HR B2B SaaS**

#### Web Client Platform(2022.04 ~ ): Product Engineer(FE)

**Main Role**: flex 웹 제품(React) 개발 생산성/개발자 경험 향상, 기술 도입 검토 및 가설 검증, 사내 웹 프레임워크(podojs) 개발 및 유지보수, 웹 애플리케이션 서버 운영 관련 오퍼레이션

- 기존 flex 웹 제품을 Nextjs에서 [런타임 통합 Micro Frontends 아키텍처](https://maxkim-j.github.io/posts/runtime-integration-micro-frontends)로 마이그레이션하는 8개월간의 과정(2022.07 ~ 2023.03)을 주도하여, 사용자/개발자 경험을 개선하고 빌드 성능을 앱당 평균 75% 개선했습니다.
- Webpack Module Federation을 사용한 사내 Micro Frontends 웹 프레임워크인 podojs에 기여했습니다. Micro App 간 디커플링을 보장하면서 런타임 에러를 방지하는 설계를 적용하고, fast refresh를 사용할 수 있는 로컬 개발 서버를 구성하는 등 nodejs 런타임 기반의 다양한 개발 업무를 수행했습니다.
- 별다른 규칙 없이 코드베이스에 추가되던 환경변수의 혼란스러움을 개선하기 위해, 환경변수 카테고리 분류 및 타입을 정의하고 앱 기동시에 밸리데이션 스텝을 추가하는 등 환경변수 주입 프로세스를 정비했습니다.
- Kubernetes, Docker 기반의 운영 환경에서 웹 클라이언트 애플리케이션에 필요한 오퍼레이션을 진행하며, 동료 FE 개발자들이 인프라 관련 설정 값 변경, [nodejs 서버 모니터링](https://maxkim-j.github.io/posts/nodejs-server-monitoring)을 자체적으로 진행할 수 있도록 관련 가이드를 작성하는 등 업무 가시화에 기여했습니다.
- 웹 제품 성능향상 TF 리드를 맡아 전체 앱의 P75 LCP를 34% 개선하는데 기여하고, 향상된 성능이 유지될 수 있도록 제품 성능 지표 가시화를 위한 모니터링 활동을 주도했습니다.

### [모예(2021.01 ~ 2021.08)](https://thevc.kr/moye)

> **신인 패션 디자이너와 브랜드의 성공적인 런칭을 돕는 프리오더 서비스 (\*2022년 폐업)**

#### Product Team(2021.01 ~ 2021.08): Web Frontend Engineer(Lead)

**Main Role**: 패션 프리오더 커머스 웹(React)/ 모바일(React Native) 애플리케이션 개발 및 유지보수, 3명 규모 FE 팀 리드 역할 수행

- 유연하고 작은 디자인 시스템이 필요했던 팀의 실정에 맞게, 제품팀 설득을 통해 확고한 분류 기준을 가진 Atomic Design System 기반의 디자인 시스템을 해체하고 UI 컴포넌트 디렉토리 구조를 개선했습니다.
- 모바일 앱을 로컬에서 빌드/배포하는 비효율적인 방식을 개선하기 위해, Github Actions, fastlane, codepush를 사용해 [React Native 모바일 앱 배포 파이프라인](https://maxkim-j.github.io/posts/react-native-ci-cd)을 구축했습니다.
- 웹 제품과 모바일 앱 제품의 같은 동작을 보장하면서 도전적인 일정 안에 모바일 앱을 빠르게 구현할 수 있도록, Redux와 Redux Saga를 이용해 store에 서버 비동기 요청 로직을 일원화하여 React 웹앱과 React Native 모바일 앱이 같은 Redux Store 코드를 공유하게 했습니다.
- Redux Saga 코드의 복잡함을 완화하고 비동기 요청 로직을 추가하는데 드는 시간을 단축하기 위해, 서버 비동기 요청에 대한 상태값, saga 함수 등을 모두 포함하게 되어 비대해진 Redux Store에 [Redux Toolkit을 도입](https://maxkim-j.github.io/posts/redux-store-structure)했습니다.
- 백엔드 개발이 끝난 후 프론트엔드 개발이 시작되는 폭포수 개발 사이클을 개선하기 위해, [OpenAPI Spec 기반 개발 방식](https://projectmaxkim.notion.site/0228-OpenAPI-46c3c26970b2407eb8c4b063bf0bff55)을 도입하고 open api 스펙을 별도의 git 레포지토리로 관리했습니다.

### [FREED GROUP(2020.07 ~ 2021.01)](https://www.freedgrouptech.com/)

> **글로벌 챗봇, 웹 커머스 개발/구축 서비스를 제공하는 IT Solution Provider**

#### Web Frontend Team(2020.07 ~ 2021.01): Web Frontend Engineer(Intern)

**Main Role**: 여행 추천 웹앱 / 문자 주문 솔루션 백오피스 등 Vue.js를 이용한 웹앱 SI 개발

- 백엔드 서버의 JSON 응답을 웹 제품에 맞게 명령적으로 가공하는 로직의 복잡성을 완화하기 위해, Typescript 객체를 메서드 체이닝 방식으로 수정할 수 있는 [functional-flattener](https://github.com/MaxKim-J/functional-flattener) npm 라이브러리를 제작해 배포하고 내부 어드민 제품에 적용했습니다.
- 웹 프론트엔드 팀이 2명에서 5명으로 늘어남에 따라 팀원간 동일한 이해를 보장하기 위해, 팀 컨벤션과 코드 리뷰 규칙 등의 내용을 담은 프론트엔드팀 위키 문서를 작성했습니다.

## Community

### Known Articles

- 브라우저 주소창에 URL을 치면 일어나는 일들: [GeekNews](https://twitter.com/GeekNewsBot/status/1491218802474127362)(2022.02.09)
- Suspense for Data Fetching의 작동 원리와 컨셉(feat.대수적 효과): [naver fe-news](https://github.com/naver/fe-news/blob/master/issues/2021-12.md)(2022.01.05)

### Presentations

- [[2023 FE Conf] 대형 웹 애플리케이션 Micro Frontends 전환기](https://www.youtube.com/watch?v=VnJLFwnuLV4)(2023.10.21)
- [[2022 피로컨퍼런스] 내가 FE를 좋아하는 이유](https://www.youtube.com/watch?v=8vKSx9KXddI)(2022.02.28)

### Contributions

- [reactjs/ko.react.dev](https://github.com/reactjs/ko.react.dev): React New Docs 공식 한국어 문서 번역 메인테이너, 코드 리뷰 및 번역 가이드라인 기여(2023.03 ~)
- [facebookexperimental/Recoil#1584](https://github.com/facebookexperimental/Recoil/pull/1584): 공식 문서 한국어 번역 기여(2022.02.01)

## FYI

- 실사용자 600명 이상의 [크롬 익스텐션 프로젝트](https://github.com/MaxKim-J/hufs-semester-clock-v2)를 개발하고 3년간 운영했습니다. 개발 과정에서 [스크린 리더를 개발 과정에서 적극적으로 사용](https://maxkim-j.github.io/posts/web-accessiblity-virtuous-cycle)하며, 웹 표준과 웹 접근성을 준수한 마크업을 작성했습니다. (LightHouse 기준 접근성 100점)
- 다양한 도메인의 개발자들과 함께 2년간(2021.01 ~ 2023.02) 주말 아침 세션 스터디를 진행하며, [25번의 기술 관련 발표](https://dent-aurora-a21.notion.site/d43fd4a132234c028ad3a1500c97c5b1)를 진행했습니다.
