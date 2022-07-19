---
title: "Projects"
date: "2020-06-16"
author: "Andy Delso"
path: "/projects"
---

# Professional Projects

## Currently: M1
### Android Automation Framework

Uses [Kotlin](https://kotlinlang.org/) and [Espresso](https://developer.android.com/training/testing/espresso/) to provide a test framework for our Test Engineers to build [Cucumber](https://cucumber.io/) test scripts on top of. It utilizes a combination of [test robots](https://medium.com/android-bits/espresso-robot-pattern-in-kotlin-fc820ce250f7) (actions collection) and [UI test components](https://dev.to/ddaypunk/how-we-use-a-component-model-in-selenium-to-increase-maintainability-1nk0) to increase mantainability and readability while providing a simpler API to work with.

### Playwright Tests
Uses [Playwright](https://playwright.dev/) and [Javascript](https://developer.mozilla.org/en-US/docs/Web/javascript) along with [Cucumber](https://cucumber.io/) for high level scripting. Our project utilizes a centralize repository of Cucumber features, that all client testing tools leverage, including the Android framework above. This allows us to keep all the tests in alignment from UI to integration.

## Prevously: Hyatt Hotels Corporation
### Data Mocking

Uses [Kotlin](https://kotlinlang.org/) and [Wiremock](http://wiremock.org/) to provide mocked responses to our mobile app. Allows for easier testing of error states and such.

### Mobile automation

Contributions to our automation framework that uses [Geb](https://gebish.org/), [Spock](http://spockframework.org/), [Appium](https://appium.io/) and [SpringBoot](https://spring.io/projects/spring-boot). All tests are written using [Groovy](https://groovy-lang.org/) and run using [SauceLabs](https://saucelabs.com/). All tests are setup in [Jenkins](https://www.jenkins.io/) using job dsl style.

# Personal Projects

## [Selenium Framework](https://github.com/ddaypunk/dupage)

A reusable [Selenium](https://www.selenium.dev/) framework built using the newest version of Selenium at the time, SpringBoot, and [JUnit5](https://junit.org/junit5/) amongst other things. Uses component based page object model as described and improved upon in my [blog article](/selenium-component-model).

## [React Playground](https://github.com/ddaypunk/playground)

A very simple [React](https://reactjs.org/) based website with an [Express](https://expressjs.com/) server backend. Intended to be used in testing above selenium project over using solutions in order to have better control over the selectors available in the front end implementation. I used `create-react-app` to set up the project and express serves the site.

## [Card Shuffle](https://github.com/ddaypunk/card-shuffle)

Simple object-oriented programming exercise using [Java](https://docs.oracle.com/en/java/) for an interview I did a while ago that shuffles a common deck of playing cards.

## [Fragments of Palladium](https://github.com/BedfordWest/fragmentology)

A game developed by a team of folks from work using Java and the [LibGDX](https://libgdx.badlogicgames.com/) library. Project lead was [Bedford West](https://github.com/BedfordWest). I personally worked on some pixel art and the programming for the controls. This was never completed, but restarted using Godot engine in 2020.
