# cypress
UI integration testing using [Cypress](https://www.cypress.io).

## How to install

```bash
$ npm install
```

### How to Run

```bash
Step to run the test with open cypress GUI: 
1. $ npm run cy:open
2. Find voila-check-test.js 
3. Click it

```

![cermati-test-cypress-gui](cypress/asset/cermati-test-cypress-gui.PNG)

```bash
Step to run test without open cypress GUI
1. npm run cy:run -- --spec "cypress/integration/tests/cermati-test.js"
2. after finish, check the video folder and screenshoot folder

```

### General Question

```bash

1.As a QA engineer, my passion lies in striving for excellence in the tech industry and making a meaningful impact through quality
  to ensure that every product we deliver meets the highest standards and exceeds customer expectations

2.I want to become a QA engineer because I am passionate about ensuring the quality and reliability of software applications. 
  I find great satisfaction in using code to uncover any potential bugs or vulnerabilities. 
  By leveraging my technical skills and attention to detail, I strive to contribute to the development of robust, bug-free applications that provide exceptional user experiences.

3.My goal is to make a positive impact through code to ensure the products we contribute to are delivered with the highest standards.


4.my plan to achieve my goal:
  Understand the Project
  Able to Identify Test Scenarios
  Able to Design Test Cases
  Setup Test Environment
  Implement Test Automation and Execute E2E Tests
  Collaborate and Communication with the Development Team
  Continuous Improvement

5.As a QA engineer joining this company, my primary expectation is to contribute to the delivery of high-quality software products. 
  I believe in the importance of a strong quality assurance process to ensure every product we deliver meets the highest standard, customer satisfaction and the success of the organization.
  With that in mind, I would expect the following:
  Clear and well-defined quality standards
  recognize the critical role of QA in the software development lifecycle and appreciate the efforts put into ensuring product quality
  access to the necessary testing tools, devices, and adequate infrastructure to support comprehensive testing
  Continuous learning and growth opportunities
  Collaboration and communication
```
### Expected result from finding
```bash
Use IDR currency on applied tag
```

### Actual result from finding
```bash
Use USD instead IDR currency on applied tag
```
![no1-fail-test](cypress/asset/no1-fail-test.PNG)
![no1-evidence](cypress/asset/no1-evidence.PNG)

