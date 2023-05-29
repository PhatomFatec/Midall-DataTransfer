# Used DevOps concepts
DevOps is a software development approach that combines development and operations teams to streamline processes and deliver high-quality software more efficiently. It fosters collaboration, automation, and continuous improvement. The benefits of DevOps include increased collaboration and communication, continuous integration and delivery, faster time to market, improved software quality, enhanced reliability and stability, scalability and flexibility, continuous monitoring and feedback, and cost optimization. Overall, DevOps aligns teams, accelerates software delivery, improves quality, and enhances customer satisfaction.

## Table of contents

 - [Issue Control](#issue-control)
 - [Gitflow](#gitflow)
 - [Continuos Integration](#continuos-integration)
 - [Github Actions](#github-actions)
 - [Unit Tests](#unit-tests)
 - [Backend Tests](#backend-tests)
 - [Frontend Tests](#frontend-tests)


## Issue Control

Issue control in a DevOps project refers to the management and resolution of problems or difficulties that arise during the development, implementation, and continuous operation of a system or software. It involves the proactive identification of issues, registration and tracking of problems, prioritization, resolution, communication, and continuous learning. Effective issue control helps teams identify and address problems quickly, improving the quality of the delivered software and user satisfaction.
For issue control in this project, we used documentation methodologies and integration between software as a basis for documentation, in particular:

- Github -> We used github to create a board with the tasks defined for each sprint, in addition to documenting each one as issues within github. Which allows us to create assignments from the creation of a branch to the link in commits. [Board link](https://github.com/orgs/PhatomFatec/projects/5/views/1) 

- [Zube](https://zube.io/) -> We use zube in conjunction with github, promoting a very valuable integration for documentation and control of issues related to this project. From applying the agile methodology used ([Scrum](https://www.atlassian.com/br/agile/scrum) ) to creating dashboards and reports for task monitoring
 
<br>

You can see more information about our Issue Control on the following material: [IssueControl](https://www.canva.com/design/DAFkSjejDHU/45xN9H1R4W8JAcRQjU4I_Q/edit?utm_content=DAFkSjejDHU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)



## Gitflow

GitFlow is a popular branching model for Git repositories that streamlines collaborative software development. It defines long-lived branches like main and development, with feature branches created from the development branch for implementing specific tasks. Completed features are merged back into the development branch, promoting frequent integration. Release branches allow for final bug fixes before deployment, while hotfix branches address critical production issues. The main branch represents stable code, only updated when releases or hotfixes are merged. GitFlow ensures structured workflows, encourages collaboration, and facilitates scalability and traceability in managing complex software projects. Other models like GitHub Flow and GitLab Flow offer alternative approaches to version control.

<br>

<p align="left"> 
<img src="https://miro.medium.com/v2/resize:fit:800/1*u4dlEq4sqIT6iHL_Usvwnw.png" width=426 height=270/> <br>
</p> 

<br>

Follow the link to get more information about [Gitflow](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow)

## Continuos Integration

Continuous Integration (CI) is a software development practice that involves automatically integrating code changes from multiple developers into a shared repository frequently. It aims to catch integration issues early by regularly merging code and running automated builds, tests, and analyses. CI detects problems like compilation errors or test failures caused by code conflicts or compatibility issues. By integrating changes frequently, CI promotes collaboration, provides immediate feedback to developers, and ensures a more reliable and stable software development process. CI tools like Jenkins or Travis CI automate the build and test processes, enhancing productivity and quality while enabling faster software delivery.

<br>

## Github Actions

GitHub Actions is an automation tool provided by GitHub for continuous integration. It enables developers to create workflows, which are sequences of actions that automate tasks like building, testing, and deploying software projects. Workflows are triggered by events, such as code changes, ensuring a standardized process for integrating code.

Continuous integration in GitHub Actions involves automatically integrating code changes into a shared repository. Workflows can be triggered by code pushes or pull requests, allowing for early detection of issues or conflicts. GitHub Actions offers a wide range of pre-built actions and supports custom actions, enabling developers to create tailored workflows. It seamlessly integrates with other GitHub features, enhancing the development experience.

By utilizing GitHub Actions for continuous integration, developers can enhance software quality, reduce manual tasks, and boost productivity. 


<br>

An example on how we are using Github actions in this project:
```

name: Unit test back

on:
  push:
     branches: [ $default-branch ]
  pull_request:
    branches: [ main, develop ]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v1
    - name: Set up JDK 17
      uses: actions/setup-java@v1
      with:
        java-version: '17'
    - name: run tests with Maven
      run: mvn test
```

<br>

## Unit Tests

Unit tests in DevOps refer to automated tests that verify the functionality of individual software components. They play a crucial role in ensuring software reliability and stability. By automating these tests, developers can quickly identify and fix issues, promoting continuous integration and delivery. Unit tests contribute to shorter development cycles, improved code quality, and confidence in making changes. They are a fundamental component of the DevOps approach, facilitating collaboration and consistent software delivery.

<br>

## Backend Tests

Backend tests are automated tests that validate the functionality of the server-side components in a web project. They are important because they verify core functionality, ensure data consistency, test integration between components, handle errors and edge cases, assess performance, and prevent regressions. Backend tests provide confidence in the stability and reliability of the application's backend, improving overall quality and facilitating robust delivery to end-users.

<br>

An example on how we are using Back-end tests in this project, with JUnit:
```
@Test
	public void buscarHistoryPorId() {
		assertThrows(NullPointerException.class, () -> {
			service.findById(89L);
		});
	}
```
<br>

## Frontend Tests

Front-end tests are automated tests that validate the user interface, user interactions, and client-side logic of a web application. They are important because they ensure UI consistency, validate user interactions, verify client-side logic, ensure cross-browser and cross-device compatibility, validate responsive design, and prevent regressions. Front-end tests contribute to delivering a high-quality and bug-free user experience in a web project.

An example on how we are using Front-end tests in this project, with Jest:
```
describe('toHome', () => {
  test('deve mostrar a seção de home e esconder as outras', () => {
    document.body.innerHTML = `
    <div class="home"></div>
    `
    toHome()

    const home = document.querySelector('.home')

    expect(home.style.display).toBe('flex')

  })
})

```