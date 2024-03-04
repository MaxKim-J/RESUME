# RESUME

> 👔 Employed since April 2022. I am not currently looking for a job.

I'm Jonghyuk Kim (Max), a software engineer. I've been creating and operating web client products.

- location: Seoul, South Korea(UTC+09:00)
- email: hwaseen@gmail.com
- blog: https://maxkim-j.github.io
- github: https://github.com/MaxKim-J

## Work Experience

### [flex(2022.04 ~ in office)](https://flex.team/)

> **Human Relations Platform, HR B2B SaaS that solves problems about people and organizations**.

#### FE Labs(2022.04 ~ ): Product Engineer (FE).

**Main Role**: Improve flex web product (React) development productivity/developer experience, review technology adoption and validate hypotheses, develop and maintain in-house web framework (podojs), and operations related to web application server operations.

- Led an 8-month process (July 2022 - March 2023) to migrate existing flex web products from Nextjs to [Runtime Integration Micro Frontends Architecture](https://maxkim-j.github.io/posts/runtime-integration-micro-frontends), improving user/developer experience and build performance by an average of 75% per app.
- Contributed to podojs, an in-house Micro Frontends web framework using Webpack Module Federation. Performed various development tasks based on the nodejs runtime, including applying designs to prevent runtime errors while ensuring decoupling between micro apps, and configuring a local development server to enable fast refresh.
- Overhauled the environment variable injection process, including categorizing and typing environment variables and adding validation steps at app startup, to improve the chaos of environment variables being added to the codebase without any rules.
- Performed operations required for web client applications in Kubernetes and Docker-based production environments, and contributed to work visibility by writing guides for fellow FE developers to change infrastructure-related settings and [nodejs server monitoring](https://maxkim-j.github.io/posts/nodejs-server-monitoring) on their own.
- He has developed authentication/security features that require delicate handling of authentication information and ensure safe and correct behavior, such as [secondary authentication when viewing sensitive information](https://updatenotes.flex.team/c48a7aea-25be-483e-a6d6-47cce979c05a) and automatic logout when there is no user interaction.

### [Moye (2021.01 ~ 2021.08)](https://thevc.kr/moye)

> **Pre-order service to help emerging fashion designers and brands launch successfully (\*Closed in 2022)**.

#### Product Team(2021.01 ~ 2021.08): Web Frontend Engineer(Lead)

**Main Role**: Developed and maintained fashion pre-order commerce web (React) / mobile (React Native) applications, acting as a lead for a 3-person FE team.

- Convinced the product team to deconstruct the Atomic Design System-based design system with its rigid taxonomy and revamped the UI component directory structure to meet the team's need for a flexible and smaller design system.
- To improve the inefficient way of building/deploying mobile apps locally, we built a [React Native mobile app deployment pipeline](https://maxkim-j.github.io/posts/react-native-ci-cd) using Github Actions, fastlane, and codepush.
- To ensure the same behavior of the web product and mobile app product, and to quickly implement the mobile app within a challenging timeline, we used Redux and Redux Saga to centralize the server asynchronous request logic in the store so that the React web app and React Native mobile app share the same Redux Store code.
- To reduce the complexity of the Redux Saga code and reduce the time it took to add asynchronous request logic, we [introduced the Redux Toolkit](https://maxkim-j.github.io/posts/redux-store-structure) to our bloated Redux Store, which now includes state values, saga functions, and more for server asynchronous requests.
- To improve the waterfall development cycle, where front-end development starts after back-end development ends, we introduced the [OpenAPI Spec-based development approach](https://projectmaxkim.notion.site/0228-OpenAPI-46c3c26970b2407eb8c4b063bf0bff55) and managed the OPEN API spec as a separate GIT repository.

### [FREED GROUP(2020.07 ~ 2021.01)](https://www.freedgrouptech.com/)

> **Global chatbot and web commerce development/implementation service provider**.

#### Web Frontend Team(2020.07 ~ 2021.01): Web Frontend Engineer(Intern)

**Main Role**: Developed web app SI using Vue.js, such as travel recommendation web app / text ordering solution back office

- To alleviate the complexity of the logic of imperatively processing JSON responses from the backend server into a web product, I created and deployed the [functional-flattener](https://github.com/MaxKim-J/functional-flattener) npm library to modify Typescript objects in a method-chaining way and applied it to the internal admin product.
- As the web front-end team grew from 2 to 5 people, we created a front-end team wiki document to ensure team members were on the same page, including team conventions and code review rules.

## Community

### Known Articles

- What happens when you type a URL in the browser address bar: [GeekNews](https://twitter.com/GeekNewsBot/status/1491218802474127362)(2022.02.09)
- How Suspense for Data Fetching works and the concept behind it (feat.algebraic effect): [naver fe-news](https://github.com/naver/fe-news/blob/master/issues/2021-12.md)(2022.01.05)

### Presentations.

- [[2023 FE Conf] Transitioning to Micro Frontends for Large Web Applications](https://www.youtube.com/watch?v=VnJLFwnuLV4)(2023.10.21)
- [[2022 FE Conf] Why I Love FE](https://www.youtube.com/watch?v=8vKSx9KXddI)(2022.02.28)

### Contributions

- [reactjs/en.react.dev](https://github.com/reactjs/ko.react.dev): Official Korean documentation translation maintainer for React New Docs, contributing code reviews and translation guidelines (2023.03~)
- [facebookexperimental/Recoil#1584](https://github.com/facebookexperimental/Recoil/pull/1584): Contributed to official documentation Korean translation (2022.02.01)

## FYI

- Developed and ran a [Chrome extension project](https://github.com/MaxKim-J/hufs-semester-clock-v2) for 3 years with 600+ active users, [actively used screen readers](https://maxkim-j.github.io/posts/web-accessiblity-virtuous-cycle) during the development process, and wrote markup that complied with web standards and web accessibility. (100 accessibility score according to LightHouse)
- Organized weekend morning session studies with developers from various domains for 2 years (2021.01 - 2023.02), delivering [25 technical presentations](https://dent-aurora-a21.notion.site/d43fd4a132234c028ad3a1500c97c5b1).
