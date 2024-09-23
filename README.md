# Sample HTML test reports


## Summary

Sample HTML reports for web pages and REST api tests.

https://qa-demo.gitlab.io/reports


## Test targets

The web pages under test:
- https://www.selenium.dev/selenium/web/web-form.html
- http://qa-demo.gitlab.io/reports/web/ajax.html

The REST api under test:
- https://petstore.swagger.io/


## Automation test tools

The test report tool: [Allure](https://allurereport.org/)

The web automation test tools:
- [Selenium](https://www.selenium.dev/)
- [Playwright](https://playwright.dev/)
- [Cypress](https://www.cypress.io/)
- [Karate](https://www.karatelabs.io/)
- [Serenity BDD](https://serenity-bdd.info/)
- [Robot Framework](https://robotframework.org/)

The REST api test tools:
- [Cucumber](https://cucumber.io/)
- [REST-assured](https://rest-assured.io/)
- [Karate](https://www.karatelabs.io/)
- [Serenity BDD](https://serenity-bdd.info/)
- [Robot Framework](https://robotframework.org/)


## Detail of tools and frameworks

| Category              | Python        | Java          | Node.js       |
|-----------------------|---------------|---------------|---------------|
| Web test tools | <ul><li>Playwright</li> <li>Selenium </li> <li>Robot Framework</li></ul> | <ul><li>Playwright</li> <li>Selenium</li> <li>Karate</li> <li>Serenity BDD</li></ul> | <ul><li>Playwright </li> <li>Cypress</li></ul> |
| REST API test tools   | <ul><li>Behave (Cucumber)</li> <li>Robot Framework</li></ul> | <ul><li>REST-assured</li> <li>Karate</li> <li>Serenity BDD</li></ul> | <ul><li>Cucumber-js (Cucumber)</li></ul> |
| Unit test framework   | Pytest        | JUnit5        | Mocha         |
| Package manager       | pip           | Maven         | npm           |
| Test Reporting Tool   | Allure report | Allure report | Allure report |
| Code repository       | Gitlab        | Gitlab        | Gitlab        |
| Continuos integration | Gitlab-CI     | Gitlab-CI     | Gitlab-CI     |
| Test environment      | Docker        | Docker        | Docker        |


## Source code of tests

https://gitlab.com/qa-demo/tests
