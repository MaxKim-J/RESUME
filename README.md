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
- 아키텍처 마이그레이션 이후 남아있던 마이크로 프론트엔드 앱 간 코드 강결합을 메시징 인터페이스 등의 방식으로 점진적으로 해소하면서도 앱 간 하위호환을 엄격히 준수하는 릴리즈 계획을 수립하고 수행해 배포간 장애 발생 없이 앱 간 디커플링 수준을 높이고 기술부채를 상환하였습니다.
- Webpack Module Federation 기반의 사내 Micro Frontends 웹 프레임워크 podojs를 시작하고 기여했습니다. [Webpack Module Federation Plugin를 규모가 큰 SaaS 웹 제품에 적용할 수 있도록 튜닝 및 사용례를 제한하며](https://maxkim-j.github.io/posts/module-federation-shared#%EC%8B%A4%EC%A0%9C-%EC%9A%B4%EC%98%81%ED%99%98%EA%B2%BD%EC%97%90%EC%84%9C%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%93%B0%EB%8A%94%EA%B2%8C-%EC%A2%8B%EC%9D%84%EA%B9%8C), nodejs 기반 서버, cli, 웹 클라이언트를 아우르는 프레임워크 인터페이스 설계, 빠른 개발을 위한 로컬 개발 서버를 구성하는 등 nodejs 런타임 기반의 다양한 개발 업무를 수행했습니다.
- Kubernetes, Docker 기반의 운영 환경에서 웹 클라이언트 애플리케이션에 필요한 오퍼레이션을 진행하며, 동료 FE 개발자들이 인프라 관련 설정 값 변경, [nodejs 서버 모니터링](https://maxkim-j.github.io/posts/nodejs-server-monitoring)을 자체적으로 진행할 수 있도록 관련 가이드를 작성하는 등 업무 가시화에 기여했습니다.
- 웹 제품 성능향상 TF 리드를 맡아 6개월동안 flex 전체 웹 앱의 P75 LCP를 34% 개선하는데 기여하고, 향상된 성능이 유지될 수 있도록 제품 성능 지표 가시화를 위한 모니터링 활동을 주도했습니다.
- 22개 웹앱과 500개의 패키지를 수용하고 30명이 개발하던 웹 프론트엔드 제품 모노레포를 [14개의 레포지토리로 쪼개는 1년간의 마이그레이션 과정을 설계하고 주도하여](https://youtu.be/Nqzjsdjgogo?si=7kTrMXiK4qifQyBW), 안정성 문제로 모든 제품이 정기배포를 통해 일주일에 단 한번만 나갈 수 있는 사내 배포 정책을 수정하고 각 제품을 개발하는 개발자가 릴리즈 계획과 주기를 정할 수 있도록 하여 팀의 웹 제품 인도 과정의 병목 제거에 기여했습니다.
- 5년여간 특별한 규칙 없이 관리되지 않은 모노레포 내 복잡한 패키지간 의존성을 단방향으로 정리하고, 패키지들의 사용 빈도 및 의존 관계를 고려해 적절한 단위로 통합하거나 없애는 과정을 통해 코드 변경시 어떤 애플리케이션을 배포해야 하는지 추적 가능한 코드베이스를 설계하고 실제로 구성하는데 기여했습니다.

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

- [[2025 FEConf] 모노레포 절망편, 14개 레포로 부활하기까지 걸린 1년](https://youtu.be/Nqzjsdjgogo?si=owoZsEZzOsg9KkLk)(2025.08.23)
- [[2023 FEConf] 대형 웹 애플리케이션 Micro Frontends 전환기](https://www.youtube.com/watch?v=VnJLFwnuLV4)(2023.10.21)
- [[2022 피로컨퍼런스] 내가 FE를 좋아하는 이유](https://www.youtube.com/watch?v=8vKSx9KXddI)(2022.02.28)

### Contributions

- [reactjs/ko.react.dev](https://github.com/reactjs/ko.react.dev): React New Docs 공식 한국어 문서 번역 메인테이너, 코드 리뷰 및 번역 가이드라인 기여(2023.03 ~ 2024)
- [facebookexperimental/Recoil#1584](https://github.com/facebookexperimental/Recoil/pull/1584): 공식 문서 한국어 번역 기여(2022.02.01)

## FYI

- 실사용자 600명 이상의 [크롬 익스텐션 프로젝트](https://github.com/MaxKim-J/hufs-semester-clock-v2)를 개발하고 3년간 운영했습니다. 개발 과정에서 [스크린 리더를 개발 과정에서 적극적으로 사용](https://maxkim-j.github.io/posts/web-accessiblity-virtuous-cycle)하며, 웹 표준과 웹 접근성을 준수한 마크업을 작성했습니다. (LightHouse 기준 접근성 100점)
- 다양한 도메인의 개발자들과 함께 2년간(2021.01 ~ 2023.02) 주말 아침 세션 스터디를 진행하며, [25번의 기술 관련 발표](https://dent-aurora-a21.notion.site/d43fd4a132234c028ad3a1500c97c5b1)를 진행했습니다.
