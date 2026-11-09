# Awesome Automated Web Browser Testing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome automated web browser testing frameworks, tools, cloud grids, and SaaS platforms.

---

## Contents

- [Open-Source Frameworks & Tools](#open-source-frameworks--tools)
- [SaaS Web & Browser Testing Clouds](#saas-web--browser-testing-clouds)
- [Open-Core & Self-Hosted Infrastructure](#open-core--self-hosted-infrastructure)

---

## Open-Source Frameworks & Tools

Curated open-source projects for browser automation, E2E testing, and grid infrastructure, sorted by GitHub star count in descending order:

| Project | Stars | License | Description |
|---|:---:|---|---|
| [Browser Use](https://github.com/browser-use/browser-use) | [![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=social&color=white)](https://github.com/browser-use/browser-use/stargazers) | MIT | Open-source Python library for AI browser agents and automation. |
| [Playwright](https://github.com/microsoft/playwright) | [![GitHub stars](https://img.shields.io/github/stars/microsoft/playwright?style=social&color=white)](https://github.com/microsoft/playwright/stargazers) | Apache-2.0 | Cross-browser automation for Chromium, Firefox, and WebKit with a single API. |
| [Puppeteer](https://github.com/puppeteer/puppeteer) | [![GitHub stars](https://img.shields.io/github/stars/puppeteer/puppeteer?style=social&color=white)](https://github.com/puppeteer/puppeteer/stargazers) | Apache-2.0 | Node.js library providing a high-level API to control Chrome or Chromium over DevTools. |
| [Cypress](https://github.com/cypress-io/cypress) | [![GitHub stars](https://img.shields.io/github/stars/cypress-io/cypress?style=social&color=white)](https://github.com/cypress-io/cypress/stargazers) | MIT | Fast, reliable front-end testing framework for anything running in a browser. |
| [Selenium](https://github.com/SeleniumHQ/selenium) | [![GitHub stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?style=social&color=white)](https://github.com/SeleniumHQ/selenium/stargazers) | Apache-2.0 | The industry-standard browser automation framework and ecosystem. |
| [Appium](https://github.com/appium/appium) | [![GitHub stars](https://img.shields.io/github/stars/appium/appium?style=social&color=white)](https://github.com/appium/appium/stargazers) | Apache-2.0 | Cross-platform automation framework for native, hybrid, and mobile web apps. |
| [Nightwatch.js](https://github.com/nightwatchjs/nightwatch) | [![GitHub stars](https://img.shields.io/github/stars/nightwatchjs/nightwatch?style=social&color=white)](https://github.com/nightwatchjs/nightwatch/stargazers) | MIT | Integrated end-to-end testing framework written in Node.js using W3C WebDriver API. |
| [TestCafe](https://github.com/DevExpress/testcafe) | [![GitHub stars](https://img.shields.io/github/stars/DevExpress/testcafe?style=social&color=white)](https://github.com/DevExpress/testcafe/stargazers) | MIT | Node.js tool to automate end-to-end web testing without browser plugins. |
| [WebdriverIO](https://github.com/webdriverio/webdriverio) | [![GitHub stars](https://img.shields.io/github/stars/webdriverio/webdriverio?style=social&color=white)](https://github.com/webdriverio/webdriverio/stargazers) | MIT | Next-generation browser and mobile automation test framework for Node.js. |
| [Docker Selenium](https://github.com/SeleniumHQ/docker-selenium) | [![GitHub stars](https://img.shields.io/github/stars/SeleniumHQ/docker-selenium?style=social&color=white)](https://github.com/SeleniumHQ/docker-selenium/stargazers) | Apache-2.0 | Containerized Selenium Grid with Chrome, Firefox, and Edge on container platforms. |
| [Selenium IDE](https://github.com/SeleniumHQ/selenium-ide) | [![GitHub stars](https://img.shields.io/github/stars/SeleniumHQ/selenium-ide?style=social&color=white)](https://github.com/SeleniumHQ/selenium-ide/stargazers) | Apache-2.0 | Open-source record-and-playback test automation extension for the web. |
| [Selenoid](https://github.com/aerokube/selenoid) | [![GitHub stars](https://img.shields.io/github/stars/aerokube/selenoid?style=social&color=white)](https://github.com/aerokube/selenoid/stargazers) | Apache-2.0 | Lightweight, container-native Selenium Grid implementation in Golang. |

---

## SaaS Web & Browser Testing Clouds

Cloud-based cross-browser and real-device testing platforms with hosted infrastructure.

| Platform | Pricing Model | Starting Price | Free Tier / Limits | Description |
|---|---|---|---|---|
| [BrowserStack](https://www.browserstack.com/) | Per parallel session | $199/parallel/mo | Free trial (limited minutes/sessions) | Leading cloud platform for instant access to 3,000+ real mobile devices and browsers. |
| [Sauce Labs](https://saucelabs.com/) | Per parallel session | Live: $39/mo; Virtual: $149/mo; Real: $199/mo | Free trial (limited minutes/sessions) | Enterprise cloud testing platform for automated cross-browser and mobile application testing. |
| [TestMu AI (LambdaTest)](https://www.lambdatest.com/) | Per parallel session | Live: $15/mo; Desktop: $79/mo; Real Device: $199/mo | Free tier (60 mins/month live testing, 1 parallel test, 10 min/session) | AI-powered next-generation unified testing cloud for web and mobile browsers. |
| [Cypress Cloud](https://www.cypress.io/cloud) | Per test result | $75/mo (Starter) | Free tier available (up to 500 test results/month, 3 users) | Hosted test orchestration, flaky test analytics, and smart test prioritization service for Cypress. |
| [Katalon](https://katalon.com/) | Per seat | True Platform: $59/seat/mo; Studio Enterprise: $229/seat/mo | Free tier available (limited executions/month) | Comprehensive software quality platform for web, API, mobile, and desktop testing. |
| [TestGrid](https://www.testgrid.io/) | Per seat | Starter: $199/seat/mo | Free trial available (limited test cases & device minutes) | End-to-end testing platform with AI agent automation on real devices and browsers. |

---

## Open-Core & Self-Hosted Infrastructure

Hybrid / open-core tools offering self-hosted options alongside commercial plans:

| Platform | Stars | License | Pricing | Free Tier / Limits | Description |
|---|:---:|---|---|---|---|
| [Moon by Aerokube](https://github.com/aerokube/moon) | [![GitHub stars](https://img.shields.io/github/stars/aerokube/moon?style=social&color=white)](https://github.com/aerokube/moon/stargazers) | Apache-2.0 (Open-core) | $5/parallel session/month | Free tier up to 4 parallel browser sessions | Kubernetes-native browser automation execution solution supporting Selenium, Playwright, Puppeteer, and Cypress. |
| [Browserless](https://github.com/browserless/browserless) | [![GitHub stars](https://img.shields.io/github/stars/browserless/browserless?style=social&color=white)](https://github.com/browserless/browserless/stargazers) | Commercial / Source-available | Cloud plans from $50/mo; Self-hosted enterprise licensing available | Open-source core / free self-hosted docker container for personal use; Cloud free tier: 1,000 free sessions/month | Headless Chrome and Puppeteer/Playwright service designed for high concurrency and browser automation. |
