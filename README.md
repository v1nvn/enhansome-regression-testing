# Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 445,821 | 🐛 80 | 📅 2026-03-09 with stars

> Curated list of awesome visual regression testing resources.

Regression testing is a type of software testing which verifies that software which was previously developed and tested still performs the same way after it was changed or interfaced with other software. The purpose of regression testing is to ensure that changes to the software have not introduced new faults.

## Foreword

This is intended to be an *incomplete* list of resources about visual regression testing. It is not tailored to a specific area or role (Developer/QA/UX-Designer). Note that this is for all areas of regression software testing *after* the code in question is written. For a awesome list on general software testing see e.g. [awesome-testing](https://github.com/TheJambo/awesome-testing) ⭐ 2,219 | 🐛 0 | 📅 2026-03-14.

Finally, I'm sure everyone who reads this list has one thing they want to add. Please read the [How to Contribute](origin/.github/CONTRIBUTING.md) page and **Feel free to add to the list!!**. If you think this is helpful **Please give a Star ⭐️**.

## Contents

* [General information](#general-information)
* [Browser automation](#browser-automation)
* [Tools and frameworks](#tools-and-frameworks)
* [Online services](#online-services)
* [Blog posts](#blog-posts)
* [Slideshows, talks and videos](#slideshows-talks-and-videos)
* [Deprecated](#deprecated)
* [Miscellaneous](#Miscellaneous)
  * [Contributing](#contributing)
  * [Code of Conduct](#code-of-conduct)
  * [License](#license)

## General information

* [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)
* [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)

## Browser automation

* [Selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,127 | 🐛 195 | 🌐 Java | 📅 2026-03-16 - Browser automation framework and ecosystem.
* [Webdriver.io](https://github.com/webdriverio/webdriverio/) ⭐ 9,751 | 🐛 281 | 🌐 TypeScript | 📅 2026-03-15 - Node.js bindings implementation for the W3C WebDriver protocol.
* [SlimerJS](https://github.com/laurentj/slimerjs) ⭐ 2,996 | 🐛 164 | 🌐 JavaScript | 📅 2023-03-09 - Scriptable browser like PhantomJS, based on Firefox.
* [Cypress.io](https://www.cypress.io/) - An automation framework that runs in-browser.

## Tools and frameworks (a-z↓)

* [Puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 93,828 | 🐛 295 | 🌐 TypeScript | 📅 2026-03-15 - Headless Google Chrome Node API.
* [Playwright](https://github.com/microsoft/playwright) ⭐ 84,315 | 🐛 616 | 🌐 TypeScript | 📅 2026-03-15 - Node library to automate Chromium, Firefox and WebKit with a single API.
* [Nightmare](https://github.com/segmentio/nightmare) ⭐ 19,966 | 🐛 203 | 🌐 JavaScript | 📅 2024-04-20 - High-level browser automation library based on Electron.
* [Nightwatch](https://github.com/nightwatchjs/nightwatch) ⭐ 11,953 | 🐛 337 | 🌐 JavaScript | 📅 2026-02-13 - Automated testing and continuous integration framework based on Node.js and using the Webdriver protocol.
* [TestCafe](https://github.com/DevExpress/testcafe) ⭐ 9,910 | 🐛 25 | 🌐 JavaScript | 📅 2026-03-12 - Automated browser testing for the modern web development stack.
* [Protractor](https://github.com/angular/protractor) ⚠️ Archived - E2E test framework for Angular apps.
* [BackstopJS](https://github.com/garris/BackstopJS) ⭐ 7,111 | 🐛 574 | 🌐 JavaScript | 📅 2024-09-07 - Config-driven automated screenshot test framework.
* [ResembleJS](https://github.com/Huddle/Resemble.js) ⭐ 4,607 | 🐛 29 | 🌐 JavaScript | 📅 2024-02-06 - Analyse and compare images with Javascript and HTML5.
* [CodeceptJS](https://github.com/codeception/codeceptjs/) ⭐ 4,222 | 🐛 209 | 🌐 JavaScript | 📅 2026-03-11 - Modern Era Acceptance Testing Framework for NodeJS.
* [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) ⭐ 3,909 | 🐛 37 | 🌐 JavaScript | 📅 2026-03-14 - Jest matcher that performs image comparisons using [pixelmatch](https://www.npmjs.com/package/pixelmatch)
* [Selenide](https://github.com/selenide/selenide) ⭐ 1,911 | 🐛 30 | 🌐 Java | 📅 2026-03-12 - Framework powered by Selenium WebDriver for writing easy-to-read and easy-to-maintain automated tests in Java.
* [Loki](https://github.com/oblador/loki) ⭐ 1,894 | 🐛 140 | 🌐 JavaScript | 📅 2024-10-12 - Visual regression testing for Storybook using Chrome in docker et al.
* [Lost Pixel](https://github.com/lost-pixel/lost-pixel) ⭐ 1,646 | 🐛 66 | 🌐 TypeScript | 📅 2026-03-13 - Holistic visual regression testing for full pages, components (via Storybook and Ladle integration), and custom shots (e.g. via Cypress).
* [Galen](https://github.com/galenframework/galen) ⭐ 1,416 | 🐛 171 | 🌐 Java | 📅 2022-07-15 - Java framework based on [Selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,127 | 🐛 195 | 🌐 Java | 📅 2026-03-16.
* [reg-suit](https://github.com/reg-viz/reg-suit) ⭐ 1,254 | 🐛 66 | 🌐 TypeScript | 📅 2026-03-13 - Visual regression testing suite which compares images, stores snapshots, and notifies the difference to your GitHub repo.
* [Chimp](https://github.com/xolvio/chimp) ⭐ 802 | 🐛 9 | 🌐 TypeScript | 📅 2023-11-10 - Develop acceptance tests & end-to-end tests with realtime feedback.
* [Differencify](https://github.com/NimaSoroush/differencify) ⭐ 636 | 🐛 27 | 🌐 JavaScript | 📅 2020-06-02 - A library for visual regression testing using [Puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 93,828 | 🐛 295 | 🌐 TypeScript | 📅 2026-03-15.
* [Needle](https://github.com/python-needle/needle) ⭐ 594 | 🐛 20 | 🌐 Python | 📅 2022-11-05 - Needle is a tool for testing visuals with Selenium and nose (Python).
* [FuncUnit](https://github.com/bitovi/funcunit) ⭐ 571 | 🐛 64 | 🌐 JavaScript | 📅 2021-04-01 - A functional test suite based on jQuery
* [Touca](https://github.com/trytouca/trytouca) ⭐ 509 | 🐛 7 | 🌐 TypeScript | 📅 2024-08-04 - Open source continuous regression testing without the hassle of managing snapshot files.
* [CSSCritic](https://github.com/cburgmer/csscritic) ⭐ 490 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-28 - Lightweight CSS regression testing.
* [Spectre](https://github.com/wearefriday/spectre) ⚠️ Archived - Provides image comparison capabilities and an admin interface for managing screenshots.
* [Creevey](https://github.com/wKich/creevey) ⭐ 425 | 🐛 42 | 🌐 TypeScript | 📅 2026-02-12 - Cross-browser visual testing with magic. Feature-rich tool with UI Runner, Tests Hot Reloading, Docker and Storybook integration.
* [reg-cli](https://github.com/bokuweb/reg-cli) ⭐ 399 | 🐛 40 | 🌐 JavaScript | 📅 2026-03-14 - Visual regression test tool which output easy-to-read single file html report.
* [Hardy](https://github.com/thingsinjars/Hardy) ⭐ 324 | 🐛 10 | 🌐 JavaScript | 📅 2015-03-27 - Selenium-driven, cucumber-powered CSS testing.
* [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) ⭐ 278 | 🐛 3 | 🌐 Smarty | 📅 2016-06-13 - Plugin to prevent your project of broken layout via screenshot photo sessions of your site.
* [AyeSpy](https://github.com/newsuk/ayespy) ⭐ 218 | 🐛 43 | 🌐 JavaScript | 📅 2025-10-06 - 44 image comparisons in 90 seconds.
* [Happo](https://github.com/happo/happo.io) ⭐ 205 | 🐛 25 | 🌐 JavaScript | 📅 2026-02-17 - Visual diffing in CI for user interfaces.
* [OSnap](https://github.com/eWert-Online/osnap) ⭐ 168 | 🐛 5 | 🌐 OCaml | 📅 2025-08-30 - The speedy and easy to use Snapshot Testing tool for your project (1200 snapshots will run in under 3 minutes).
* [Wendigo](https://github.com/angrykoala/wendigo) ⭐ 152 | 🐛 21 | 🌐 JavaScript | 📅 2024-03-08 - Test-oriented browser automation library based on Puppeteer.
* [AET](https://github.com/Cognifide/aet) ⭐ 150 | 🐛 112 | 🌐 Java | 📅 2024-01-15 - Scalable testing tool providing visual regression testing, accessibility and performance validation, markup analysis and more.
* [jest-puppeteer-react](https://github.com/Hapag-Lloyd/jest-puppeteer-react) ⚠️ Archived - Visual regression testing with Jest and puppeteer for React components
* [Muppeteer](https://github.com/HuddleEng/Muppeteer) ⚠️ Archived - Visual regression testing framework for Chrome using [Mocha](https://mochajs.org/) and [Puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 93,828 | 🐛 295 | 🌐 TypeScript | 📅 2026-03-15.
* [gatling](https://github.com/gabrielrotbart/gatling) ⭐ 57 | 🐛 2 | 🌐 Ruby | 📅 2013-08-01 - Integrated visual RSpec matcher which makes real visual testing easy (Ruby).
* [Shoov](https://github.com/shoov/shoov) ⭐ 40 | 🐛 56 | 🌐 PHP | 📅 2018-12-07 - UI regression and functional testing focused on Drupal 7 sites.
* [Look-alike](https://github.com/kdzwinel/Look-alike) ⭐ 35 | 🐛 2 | 🌐 JavaScript | 📅 2018-08-07 - Chrome Extension for taking and comparing screenshots.
* [test-crawler](https://github.com/apiel/test-crawler) ⭐ 33 | 🐛 69 | 🌐 TypeScript | 📅 2022-02-18 - Visual regression testing, by crawling a website and providing snapshot comparison reports.
* [ember-visual-test](https://github.com/Cropster/ember-visual-test) ⭐ 26 | 🐛 28 | 🌐 JavaScript | 📅 2024-01-17 - Simple visual regression testing for [Ember](https://emberjs.com/).
* [vrtest](https://github.com/nathanmarks/vrtest) ⭐ 16 | 🐛 6 | 🌐 JavaScript | 📅 2017-04-19 - JavaScript library for running visual regression tests on your components cross browser via selenium.
* [wdio-visual-regression](https://github.com/ennjin/wdio-visual-regression) ⭐ 3 | 🐛 17 | 🌐 TypeScript | 📅 2023-11-06 - Visual regression tool for webdriver.io
* [Wraith](https://github.com/BBC-News/wraith) ⭐ 0 | 🐛 0 | 📅 2025-09-30 - Easy to use ruby tool with docker support.
* [basset](https://basset.io) - Open source platform for generating and reviewing visual differences. Supports multiple browsers, integrations for github and slack.
* [BitDive](https://bitdive.io/) - BitDive is a zero-code regression testing tool for Java/Kotlin applications. It captures real runtime behavior (methods, SQL, HTTP) and enables Live Context Replay with automatic mocking to detect semantic drift between versions.
* [BFFless](https://bffless.app) - Self-hosted platform for hosting and viewing visual regression screenshots from CI/CD pipelines with GitHub Actions integration.
* [Karma](http://karma-runner.github.io/latest/index.html) - A test runner by the AngularJS team, that fits all our needs.
* [qd\_screenshottests](https://www.drupal.org/project/qd_screenshottests) - CasperJS-based UI regression and functional testing focused on Drupal 8 sites.
* [Zombie.js](http://zombie.js.org/) - Insanely fast, headless full-stack testing using Node.js.

## Online services (a-z↓)

* [BrowserStack](https://www.browserstack.com) - Free for Open Source. Supports [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver) ⭐ 34,127 | 🐛 195 | 🌐 Java | 📅 2026-03-16.

* [Visual Regression Tracker](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker) ⭐ 677 | 🐛 58 | 🌐 Shell | 📅 2026-01-09 - Open Source selfhosted service for visual regression testing

* [Micoo](https://github.com/Mikuu/Micoo) ⭐ 194 | 🐛 9 | 🌐 JavaScript | 📅 2023-03-05 - Open source service for all UI application visual regression solution

* [Testomat.io Reporter](https://github.com/testomatio/reporter) ⭐ 145 | 🐛 33 | 🌐 JavaScript | 📅 2026-03-14 - Allows to collect tests to a Test Case Management System (TCMS) like testomat.io and sync manual and automated tests in one place.

* [Sherlo](https://github.com/sherlo-io/sherlo) ⭐ 75 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-16 - Visual testing platform for React Native Storybook. Captures screenshots on iOS and Android simulators in the cloud and detects visual changes automatically.

* [applitools](https://applitools.com) - Cloud base visual tests.

* [Argos](https://argos-ci.com) - The open source visual testing platform for modern engineering teams.

* [Axcept](https://axcept.io) - Testing for the whole team. Up to 100 tests in parallel. Endpoint Mocking. Code Coverage.

* [Browser Shots](http://browsershots.org) - Screenshots only.

* [browserling](https://www.browserling.com) - LIVE interactive cross-browser testing.

* [BugBug.io](https://bugbug.io/) - Lightweight test automation tool for web applications. Easy to learn and doesn't require coding. It's free, with unlimited tests. For an additional monthly fee, you also get cloud monitoring and CI/CD integration.

* [Chromatic](https://www.chromatic.com/) - Visual testing and UI review for component libraries. Cloud-based. [Video](https://youtu.be/6KDLJBcutQE)

* [CrossBrowserTesting](https://crossbrowsertesting.com) - Manual & exploratory testing on 1500+ real browsers and mobile devices.

* [Diffy](https://diffy.website) - Cloud based visual regression tool that focuses on Drupal and WordPress. Full page screenshots and minimal number of false positives. Just provide URLs of your sites to get started. No coding required.

* [Fluxguard](https://fluxguard.com) - Screenshot pixel and DOM change comparisons and regressions.

* [Ghost Inspector](https://ghostinspector.com) - See [introduction video](https://vimeo.com/ghostinspector/intro).

* [Happo](https://happo.io/) - Cloud-based screenshot testing service with support for multiple browsers.

* [HeadSpin](https://www.headspin.io/) - HeadSpin's Regression testing gives you a powerful comparison tool for analysing degradation across new app builds, OS releases, feature additions, locations, and more.

* [Keploy](https://keploy.io) - Open-source regression testing tool that automatically generates test cases and mocks from real API calls.

* [LambdaTest](https://www.lambdatest.com/) - Perform Automated and Live Interactive Cross Browser Testing on 2000+ Real Browsers and Operating Systems Online.

* [Meticulous.ai](https://meticulous.ai) - Easily create frontend tests without writing code. Use Meticulous to record workflows on your web app. You can then replay those flows on new frontend code, and create a test by diffing two replays.

* [percy.io](https://percy.io) - Continuous visual reviews for web apps.

* [Pixeleye](https://pixeleye.io/home) - Open-source, multi-browser visual review and testing platform with the option to self-host. It has first-class support for Storybook, Cypress, Playwright & Puppeteer.

* [Preflight: Cypress Recorder](https://cypress.preflight.com) - Create AI-powered Cypress Tests/POM models in your browser and automate Email & Visual testing for Cypress.

* [Preflight](https://preflight.com) - Easiest Visual regression testing and Automated Web Testing tool. (Limited) free use.

* [Reflect](https://reflect.run) - Visual regression testing and test automation tool.

* [screener.io](https://screener.io) - For React, looks open source.

* [screenster.io](http://screenster.io) - Cloud based automation testing platform for web and mobile UI.

* [TestGrid](https://www.testgrid.io/) - Perform End to End test automation be it cross browser testing, mobile app testing, performance testing or API testing on cloud or on-premise.

* [TestingBot](https://testingbot.com) - Provides +3600 browsers to run automated visual tests. Free for Open Source.

* [testRigor](https://testrigor.com) - E2E functional test automation tool for web, mobile, and desktop tests.

* [Vidiff](https://vidiff.com) - Cloud-based visual regression testing across stages.

* [Visual Knight](https://visual-knight.io/) - Cloud-based visual testing platform with realtime results for testing tools.

* [VisWiz.io](https://www.viswiz.io) - Flexible visual regression testing service.

* [VRTs - Visual Regression Tests](https://bleech.de/en/products/visual-regression-tests/) – WordPress plugin auto-updating screenshots on content updates, preventing false positives.

## Blog posts  (a-z↓)

* [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) - Introduction to [Differencify](https://github.com/NimaSoroush/differencify) ⭐ 636 | 🐛 27 | 🌐 JavaScript | 📅 2020-06-02 and how to use it.
* [Visual regression testing using Jest, Chromeless and AWS Lambda](https://github.com/novemberfiveco/visual-regression-testing-jest-chromeless) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2017-11-09 - Tutorial using Chromeless and jest-image-snapshot.
* [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - Tutorial using BackstopJS.
* [Automated screenshot comparison tests with headless Chrome, Puppeteer and Pixelmatch, in Bitbucket pipeline](https://jakobzanker.de/blog/automated-screenshot-comparison-test-with-headless-chrome-in-bitbucket-pipeline/)
* [Automatic visual diffing with Puppeteer](https://meowni.ca/posts/2017-puppeteer-tests/)
* [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Headless Chrome is shaking up traditional approaches to test automation.
* [CodeLift: Introduction to Diffy for Visual Regression Testing](https://codelift.ai/resources/tech-articles/introduction-diffy-visual-regression-testing) - Catch visual and functional issues before they reach production.
* [Everything you need to know about Visual Regression Testing in 2022](https://david-x.medium.com/the-state-of-visual-regression-testing-in-2022-5de10ffe8f6f) - Intro to visual regression testing with tools updated as of 2022.
* [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - Tutorial using BackstopJS.
* [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) -  Tutorial using BackstopJS.
* [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) - Using percy, and jest puppeteer to visually test a React component library.
* [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - Compares: Wraith, PhantomCSS, Gemini, WebdriverCSS and Spectre.
* [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) - Introduction to PhantomCSS.
* [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) - Why you should use BackstopJS.
* [Poor man's visual regression testing](https://idkshite.com/posts/compare-visual-changes) - Improved manual visual regression testing with the PerfectPixel chrome plugin.
* [theheadless.dev](https://theheadless.dev) - Blog with practical guides and runnable examples on Playwright and Puppeteer.
* [UI Visual Regression Testing with Micoo](https://mikuu.medium.com/ui-visual-regression-testing-with-micoo-12c7a4a036b9) - Introduction about how to do visual regression testing with Micoo service
* [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) - Tutorial using WebdriverIO and WebdriverCSS with Spec Reporter
* [Visual regression testing for Hugo with Github-CI and BackstopJS](https://jameskiefer.com/posts/visual-regression-testing-for-hugo-with-github-ci-and-backstopjs/) - How to automate regression testing for Hugo with BackstopJS
* [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) - Tutorial to setup visual testing with Puppeteer, Jest and VisWiz.io.

## Slideshows, talks and videos  (a-z↓)

* [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) - Screencast: Basic introduction to wraith, a screenshot comparison tool.
* [Cypress in 100 Seconds](https://www.youtube.com/watch?v=BQqzfHQkREo\&ab_channel=Fireship) - Introduction video by Fireship.
* [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) - Demo what the Look-alike Chrome extension is, how it works and how and why it was build.
* [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) - How to write your first CSS test with CSS critic, make it pass, break it, and make it pass again.
* [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) - Tutorial on how to create visual automated tests with Screenster.
* [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) by Nikhil Verma - How the Mobile Web team in Badoo converted and integrated PhantomCSS into their workflow and connected it to their CI process.
* [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) - Talk by Jon Bellah on how to use PhantomCSS during wordpress development.
* [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) - How to setup shoov and get your first test written.
* [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) - Screencast with code demo and best practices.

## Deprecated  (a-z↓)

The following projects are no longer maintained actively but are still worth mentioning because of their user base.

* [PhantomJS](https://github.com/ariya/phantomjs) ⚠️ Archived - Scriptable Headless WebKit. No longer maintained since 2 June 2018.
* [Chromeless](https://github.com/graphcool/chromeless) ⚠️ Archived - Chrome automation made simple. Runs locally or headless on AWS Lambda. (archived 2018)
* [CasperJS](https://github.com/casperjs/casperjs) ⚠️ Archived - Navigation scripting and testing utility for PhantomJS and SlimerJS. (archived 2018)
* [Huxley](https://github.com/facebookarchive/huxley) ⚠️ Archived - Python framework based on [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver) ⭐ 34,127 | 🐛 195 | 🌐 Java | 📅 2026-03-16.
* [Gemini](https://github.com/gemini-testing/gemini) ⚠️ Archived - Feature rich framework with support for [Selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,127 | 🐛 195 | 🌐 Java | 📅 2026-03-16 and  [CasperJS](https://github.com/casperjs/casperjs) ⚠️ Archived. Gemini is deprecated, use hermione instead.
* [dpxdt](https://github.com/bslatkin/dpxdt) ⭐ 1,443 | 🐛 29 | 🌐 Python | 📅 2016-12-05 - End-to-end testing with Python.
* [Navalia](https://github.com/joelgriffith/navalia) ⚠️ Archived - Browser Automation based on headless Chrome and GraphQL. (archived 2018)
* [trifleJS](https://github.com/sdesalas/trifleJS) ⚠️ Archived - Headless automation for Internet Explorer. (last update 2016)
* [DalekJS](https://github.com/dalekjs/dalek) ⭐ 692 | 🐛 89 | 🌐 JavaScript | 📅 2020-04-03 - Automated cross browser testing with JavaScript. No longer maintained since 4 Jun 2017.
* [WebdriverCSS](https://github.com/webdriverio/webdrivercss) ⚠️ Archived - WebdriverCSS sits on top of [Webdriver.io](https://github.com/webdriverio/webdriverio/) ⭐ 9,751 | 🐛 281 | 🌐 TypeScript | 📅 2026-03-15 and hooks into [Selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,127 | 🐛 195 | 🌐 Java | 📅 2026-03-16.
* [Visual Review](https://github.com/xebia/VisualReview) ⚠️ Archived - A human-friendly tool for testing and reviewing visual regressions.
* [OcularJS](https://github.com/mmacartney10/ocularjs) ⭐ 7 | 🐛 4 | 🌐 JavaScript | 📅 2017-02-22 - uses [PhantomJS](https://github.com/ariya/phantomjs) ⚠️ Archived.
* [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with PhantomJS or SlimerJS. No longer maintained since 22 Dec 2017.
* [PhantomFlow](https://github.com/Huddle/PhantomFlow) - Experimental approach to UI testing, based on Decision Trees.

## Miscellaneous

### Contributing

See the [Contribution Guide](origin/.github/CONTRIBUTING.md) for details on how to contribute.

### Code of Conduct

See the [Code of Conduct](origin/.github/CODE-OF-CONDUCT.md) for details. Basically it comes down to:

> In the interest of fostering an open and welcoming environment, we as
> contributors and maintainers pledge to making participation in our project and
> our community a harassment-free experience for everyone, regardless of age, body
> size, disability, ethnicity, gender identity and expression, level of experience,
> nationality, personal appearance, race, religion, or sexual identity and orientation.

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
License holders are [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors) ⭐ 2,374 | 🐛 8 | 📅 2026-03-01.
