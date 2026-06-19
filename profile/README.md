# Allure Framework

> Official Allure Framework projects, integrations, and community resources for test reporting.

[<img src="https://allurereport.org/public/img/allure-report.svg" height="85px" alt="Allure Report logo" align="right" />](https://allurereport.org "Allure Report")

- Learn more about Allure Report at https://allurereport.org
- 📚 [Documentation](https://allurereport.org/docs/) – discover official documentation for Allure Report
- ❓ [Questions and Support](https://github.com/orgs/allure-framework/discussions/categories/questions-support) – get help from the team and community
- 📢 [Official announcements](https://github.com/orgs/allure-framework/discussions/categories/announcements) – be in touch with the latest updates
- 💬 [General Discussion](https://github.com/orgs/allure-framework/discussions/categories/general-discussion) – engage in casual conversations, share insights and ideas with the community

---

## Overview

Allure Report is an open-source, framework-agnostic test result visualization tool. It turns automated test output into clear, interactive reports with steps, fixtures, attachments, labels, links, retries, history, environments, and failure details.

Allure was built to make test results readable by people rather than buried in CI logs. The plot twist is that the same structured evidence is useful for agents too: both humans and AI assistants can inspect a run, understand what failed, and decide what to do next.

[![Allure Report 3 demo](assets/allure-report-3-demo.gif)](https://allure-framework.github.io/allure3-demo/)

## Start Here

| Need | Start with |
| --- | --- |
| Learn what Allure Report shows | [Allure Report docs](https://allurereport.org/docs/), [live demo](https://allure-framework.github.io/allure3-demo/) |
| Generate a local report | [Allure Report 3](https://allurereport.org/docs/v3/), [Allure Report 2](https://allurereport.org/docs/v2/) |
| Add Allure to a test suite | [Integration directory](#integration-directory), [full framework index](https://allurereport.org/docs/frameworks/) |
| Publish reports in CI/CD | [CI/CD and tooling](#cicd-and-tooling) |
| Centralize launches, analytics, and governance | [Allure TestOps](#allure-testops) |

## Ecosystem

| Project | Use it for |
| --- | --- |
| [Allure Report 3](https://github.com/allure-framework/allure3) | Current-generation report UI, dashboards, environments, quality gates, and agent-friendly report data. |
| [Allure Report 2](https://github.com/allure-framework/allure2) | Mature report generator with broad integration coverage and long-running ecosystem support. |
| Allure integrations | Language and framework adapters that write Allure result files from test runs. |
| [Allure TestOps](https://qameta.io/?utm_source=github&utm_medium=readme&utm_campaign=testops-link) | Commercial quality platform for centralized test management, analytics, governance, and collaboration. |

## Integration Directory

Most framework adapters live in a language-level repository. Expand a stack below or use the [full framework index](https://allurereport.org/docs/frameworks/).

<details>
<summary><strong>Java, Kotlin, Scala, Groovy, and JVM</strong></summary>

- Repositories: [allure-java](https://github.com/allure-framework/allure-java), [allure-kotlin](https://github.com/allure-framework/allure-kotlin), [allure-gradle](https://github.com/allure-framework/allure-gradle), [allure-maven](https://github.com/allure-framework/allure-maven)
- Test runners: [JUnit 4](https://allurereport.org/docs/junit4/), [JUnit 4 AspectJ](https://github.com/allure-framework/allure-java/tree/main/allure-junit4-aspect), [JUnit 5](https://allurereport.org/docs/junit5/), [JUnit Platform](https://github.com/allure-framework/allure-java/tree/main/allure-junit-platform), [TestNG](https://allurereport.org/docs/testng/), [Cucumber-JVM](https://allurereport.org/docs/cucumberjvm/), [JBehave 5](https://allurereport.org/docs/jbehave/), [ScalaTest](https://github.com/allure-framework/allure-java/tree/main/allure-scalatest), [Spock](https://allurereport.org/docs/spock/), [Citrus](https://github.com/allure-framework/allure-java/tree/main/allure-citrus), [Karate](https://github.com/allure-framework/allure-java/tree/main/allure-karate)
- UI, API, and clients: [Playwright Java](https://github.com/allure-framework/allure-java/tree/main/allure-playwright), [Selenide](https://github.com/allure-framework/allure-java/tree/main/allure-selenide), [Selenium BiDi](https://github.com/allure-framework/allure-java/tree/main/allure-selenium-bidi), [REST Assured](https://allurereport.org/docs/restassured/), [Apache HttpClient](https://github.com/allure-framework/allure-java/tree/main/allure-httpclient), [Apache HttpClient 5](https://github.com/allure-framework/allure-java/tree/main/allure-httpclient5), [OkHttp](https://github.com/allure-framework/allure-java/tree/main/allure-okhttp), [OkHttp 3](https://github.com/allure-framework/allure-java/tree/main/allure-okhttp3), [gRPC](https://github.com/allure-framework/allure-java/tree/main/allure-grpc), [JAX-RS](https://github.com/allure-framework/allure-java/tree/main/allure-jax-rs), [Servlet API](https://github.com/allure-framework/allure-java/tree/main/allure-servlet-api), [Spring Web](https://github.com/allure-framework/allure-java/tree/main/allure-spring-web)
- Utilities: [AssertJ](https://github.com/allure-framework/allure-java/tree/main/allure-assertj), [Hamcrest](https://github.com/allure-framework/allure-java/tree/main/allure-hamcrest), [JsonUnit](https://github.com/allure-framework/allure-java/tree/main/allure-jsonunit), [JUnit Jupiter assertions](https://github.com/allure-framework/allure-java/tree/main/allure-jupiter-assert), [Awaitility](https://github.com/allure-framework/allure-java/tree/main/allure-awaitility), [jOOQ](https://github.com/allure-framework/allure-java/tree/main/allure-jooq), [JavaDoc descriptions](https://github.com/allure-framework/allure-java/tree/main/allure-descriptions-javadoc)

</details>

<details>
<summary><strong>JavaScript and TypeScript</strong></summary>

- Repositories: [allure-js](https://github.com/allure-framework/allure-js), [allure-npm](https://github.com/allure-framework/allure-npm)
- Test runners and tools: [AVA](https://github.com/allure-framework/allure-js/tree/main/packages/allure-ava), [Bun](https://allurereport.org/docs/bun/), [CodeceptJS](https://allurereport.org/docs/codeceptjs/), [Cucumber.js](https://allurereport.org/docs/cucumberjs/), [Cypress](https://allurereport.org/docs/cypress/), [Jasmine](https://allurereport.org/docs/jasmine/), [Jest](https://allurereport.org/docs/jest/), [Mocha](https://allurereport.org/docs/mocha/), [Newman](https://allurereport.org/docs/newman/), [Node.js test runner](https://github.com/allure-framework/allure-js/tree/main/packages/allure-node-test), [Playwright](https://allurereport.org/docs/playwright/), [TestCafe](https://github.com/allure-framework/allure-js/tree/main/packages/testcafe-reporter-allure-official), [Vitest](https://allurereport.org/docs/vitest/), [WebdriverIO](https://allurereport.org/docs/webdriverio/)
- API and assertion helpers: [Axios](https://allurereport.org/docs/axios/), [Chai](https://allurereport.org/docs/chai/), [Fetch](https://allurereport.org/docs/fetch/)

</details>

<details>
<summary><strong>Python</strong></summary>

- Repository: [allure-python](https://github.com/allure-framework/allure-python)
- Integrations: [Behave](https://allurereport.org/docs/behave/), [Pytest](https://allurereport.org/docs/pytest/), [Pytest-BDD](https://allurereport.org/docs/pytestbdd/), [Robot Framework](https://allurereport.org/docs/robotframework/)

</details>

<details>
<summary><strong>.NET</strong></summary>

- Repository: [allure-csharp](https://github.com/allure-framework/allure-csharp)
- Integrations: [NUnit](https://allurereport.org/docs/nunit/), [Reqnroll](https://allurereport.org/docs/reqnroll/), [SpecFlow](https://allurereport.org/docs/specflow/), [xUnit.net](https://allurereport.org/docs/xunit/)

</details>

<details>
<summary><strong>PHP</strong></summary>

- Repositories: [allure-php-commons2](https://github.com/allure-framework/allure-php-commons2), [allure-php-api](https://github.com/allure-framework/allure-php-api), [allure-phpunit](https://github.com/allure-framework/allure-phpunit), [allure-codeception](https://github.com/allure-framework/allure-codeception), [allure-behat](https://github.com/allure-framework/allure-behat)
- Integrations: [Behat](https://allurereport.org/docs/behat/), [Codeception](https://allurereport.org/docs/codeception/), [PHPUnit](https://allurereport.org/docs/phpunit/)

</details>

<details>
<summary><strong>Ruby</strong></summary>

- Repository: [allure-ruby](https://github.com/allure-framework/allure-ruby)
- Integrations: [Cucumber.rb](https://allurereport.org/docs/cucumberrb/), [RSpec](https://allurereport.org/docs/rspec/)

</details>

<details>
<summary><strong>Apple and Xcode</strong></summary>

- Integration: [XCResults Reader](https://allurereport.org/docs/guides/xcresults-reader/)

</details>

<details>
<summary><strong>Go</strong></summary>

- Repository: [allure-go](https://github.com/allure-framework/allure-go)
- Docs: [repository docs](https://github.com/allure-framework/allure-go)

</details>

<details>
<summary><strong>Dart and Flutter</strong></summary>

- Repository: [allure-dart](https://github.com/allure-framework/allure-dart)
- Packages: [Dart package:test](https://pub.dev/packages/allure_dart_test), [Flutter flutter_test and integration_test](https://pub.dev/packages/allure_flutter_test), [Dart commons SDK](https://pub.dev/packages/allure_dart_commons)

</details>

<details>
<summary><strong>Rust</strong></summary>

- Repository: [allure-rust](https://github.com/allure-framework/allure-rust)
- Crates and docs: [Rust Cargo Test](https://allurereport.org/docs/rust/), [Cargo test adapter](https://github.com/allure-framework/allure-rust/tree/main/crates/allure-cargotest), [reqwest integration](https://github.com/allure-framework/allure-rust/tree/main/crates/allure-reqwest), [Rust commons SDK](https://github.com/allure-framework/allure-rust/tree/main/crates/allure-rust-commons), [test macros](https://github.com/allure-framework/allure-rust/tree/main/crates/allure-test-macros)

</details>

## CI/CD and Tooling

| Need | Links |
| --- | --- |
| GitHub Actions | [allure-action](https://github.com/allure-framework/allure-action), [setup-allurectl](https://github.com/allure-framework/setup-allurectl), [GitHub Action docs](https://allurereport.org/docs/integrations-github-action/) |
| Azure DevOps | [Azure DevOps docs](https://allurereport.org/docs/integrations-azure/) |
| Jenkins | [Allure Jenkins plugin](https://plugins.jenkins.io/allure-jenkins-plugin/), [Jenkins docs](https://allurereport.org/docs/integrations-jenkins/) |
| Bamboo | [allure-bamboo](https://github.com/allure-framework/allure-bamboo), [Bamboo docs](https://allurereport.org/docs/integrations-bamboo/) |
| TeamCity | [allure-teamcity](https://github.com/allure-framework/allure-teamcity), [TeamCity docs](https://allurereport.org/docs/integrations-teamcity/) |
| IDEs | [JetBrains IDEs](https://allurereport.org/docs/integrations-jetbrains/), [Visual Studio Code](https://allurereport.org/docs/integrations-vscode/) |
| Command line and packaging | [allurectl](https://github.com/allure-framework/allurectl), [allure-npm](https://github.com/allure-framework/allure-npm), [allure-debian](https://github.com/allure-framework/allure-debian) |
| Demos | [Allure 3 demo](https://github.com/allure-framework/allure3-demo), [Allure demo report](https://github.com/allure-framework/allure-demo) |

## Allure TestOps

Allure Report is Apache 2.0 open source and works locally, in CI, and in private environments.

When reporting alone is no longer enough, [Allure TestOps](https://qameta.io/?utm_source=github&utm_medium=readme&utm_campaign=testops-section) turns the same ecosystem into centralized, actionable quality management for teams that need long-term storage, launch analytics, compliance, access control, and cross-project visibility.

For security and compliance details, see the [Allure Trust Center](https://trust.allureteam.com/).

## Community

- Ask usage questions in [Questions and Support](https://github.com/orgs/allure-framework/discussions/categories/questions-support).
- Follow project news in [Announcements](https://github.com/orgs/allure-framework/discussions/categories/announcements).
- Share ideas in [General Discussion](https://github.com/orgs/allure-framework/discussions/categories/general-discussion).
- Open issues in the repository that owns the affected package or integration.
- Report security vulnerabilities privately at security at qameta.io.
