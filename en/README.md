# Resume

> 👔 Employed since April 2022. Currently not seeking a new job.

I am Jonghyuk Kim (Max), a software engineer primarily focused on developing and operating web client products.

- Email: hwaseen@gmail.com
- Blog: [https://maxkim-j.github.io](https://maxkim-j.github.io)
- GitHub: [https://github.com/MaxKim-J](https://github.com/MaxKim-J)

## Work Experience

### [flex (April 2022 - Present)](https://flex.team/)

> **Human Relations Platform solving issues related to people and organizations, HR B2B SaaS**

#### Web Client Platform (April 2022 - Present): Product Engineer (FE)

**Main Role**: Enhance development productivity and developer experience for flex web products (React), evaluate and validate technology adoption, develop and maintain the in-house web framework (podojs), and handle operations related to web application servers.

- Led an 8-month transition (July 2022 - March 2023) of the existing flex web product from Next.js to a [runtime integration Micro Frontends architecture](https://maxkim-j.github.io/posts/runtime-integration-micro-frontends), improving user and developer experience and enhancing build performance by an average of 75% per app.
- After the architecture migration, gradually eliminated tight coupling between micro frontend apps using messaging interfaces and other methods while strictly adhering to backward compatibility in release plans, increasing decoupling levels without deployment failures and paying off technical debt.
- Initiated and contributed to the development of the in-house Micro Frontends web framework podojs based on Webpack Module Federation. Designed framework interfaces covering Node.js-based servers, CLI, and web clients, and performed various development tasks based on the Node.js runtime.
- Conducted operations necessary for web client applications in a Kubernetes and Docker-based operating environment, contributing to work visibility by writing guides for fellow FE developers to independently change infrastructure-related configuration values and [monitor Node.js servers](https://maxkim-j.github.io/posts/nodejs-server-monitoring).
- Led the web product performance improvement task force, contributing to a 34% improvement in the P75 LCP of all flex web apps over six months, and spearheaded monitoring activities to visualize product performance metrics to maintain enhanced performance.

### [Moye (January 2021 - August 2021)](https://thevc.kr/moye)

> **Pre-order service assisting the successful launch of new fashion designers and brands (\*closed in 2022)**

#### Product Team (January 2021 - August 2021): Web Frontend Engineer (Lead)

**Main Role**: Develop and maintain fashion pre-order commerce web (React) and mobile (React Native) applications, and lead a team of 3 FE developers.

- Improved the UI component directory structure by dismantling the Atomic Design System-based design system, which had a firm classification standard, to fit the team's need for a flexible and small design system, convincing the product team.
- Established a [React Native mobile app deployment pipeline](https://maxkim-j.github.io/posts/react-native-ci-cd) using GitHub Actions, Fastlane, and CodePush to improve the inefficient method of building and deploying mobile apps locally.
- Unified server asynchronous request logic in the store using Redux and Redux Saga to ensure consistent behavior between web and mobile apps, allowing the React web app and React Native mobile app to share the same Redux Store code.
- Introduced [Redux Toolkit](https://maxkim-j.github.io/posts/redux-store-structure) to the bloated Redux Store, which included state values and saga functions for server asynchronous requests, to reduce the complexity of Redux Saga code and shorten the time required to add asynchronous request logic.
- To improve the waterfall development cycle where frontend development started after backend development was completed, introduced an [OpenAPI Spec-based development method](https://projectmaxkim.notion.site/0228-OpenAPI-46c3c26970b2407eb8c4b063bf0bff55) and managed the open API specs in a separate Git repository.

### [FREED GROUP (July 2020 - January 2021)](https://www.freedgrouptech.com/)

> **IT Solution Provider offering global chatbot and web commerce development and implementation services**

#### Web Frontend Team (July 2020 - January 2021): Web Frontend Engineer (Intern)

**Main Role**: Developed SI web apps such as travel recommendation web apps and text ordering solution back offices using Vue.js.

- Developed and deployed the [functional-flattener](https://github.com/MaxKim-J/functional-flattener) npm library, which allows TypeScript objects to be modified using method chaining, to alleviate the complexity of imperative processing logic for backend server JSON responses, and applied it to internal admin products.
- As the web frontend team grew from 2 to 5 members, wrote frontend team wiki documents containing team conventions and code review rules to ensure a common understanding among team members.

## Community

### Known Articles

- What Happens When You Enter a URL in the Browser Address Bar: [GeekNews](https://twitter.com/GeekNewsBot/status/1491218802474127362) (February 9, 2022)
- The Mechanism and Concept of Suspense for Data Fetching (feat. Algebraic Effects): [naver fe-news](https://github.com/naver/fe-news/blob/master/issues/2021-12.md) (January 5, 2022)

### Presentations

- [[2023 FE Conf] Transitioning Large Web Applications to Micro Frontends](https://www.youtube.com/watch?v=VnJLFwnuLV4) (October 21, 2023)
- [[2022 Piro Conference] Why I Love FE](https://www.youtube.com/watch?v=8vKSx9KXddI) (February 28, 2022)

### Contributions

- [reactjs/ko.react.dev](https://github.com/reactjs/ko.react.dev): Main maintainer for the official Korean translation of React New Docs, contributed to code reviews and translation guidelines (March 2023 - Present)
- [facebookexperimental/Recoil#1584](https://github.com/facebookexperimental/Recoil/pull/1584): Contributed to the official Korean translation (February 1, 2022)

## FYI

- Developed and operated a [Chrome extension project](https://github.com/MaxKim-J/hufs-semester-clock-v2) with over 600 active users for three years. During development, [actively used screen readers](https://maxkim-j.github.io/posts/web-accessiblity-virtuous-cycle) to ensure compliance with web standards and accessibility, achieving a Lighthouse accessibility score of 100.
- Conducted weekend morning session studies with developers from various domains for two years (January 2021 - February 2023), delivering [25 technical presentations](https://dent-aurora-a21.notion.site/d43fd4a132234c028ad3a1500c97c5b1).
