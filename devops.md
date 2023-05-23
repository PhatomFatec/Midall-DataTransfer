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



## Gitflow

GitFlow is a popular branching model for Git repositories that streamlines collaborative software development. It defines long-lived branches like main and development, with feature branches created from the development branch for implementing specific tasks. Completed features are merged back into the development branch, promoting frequent integration. Release branches allow for final bug fixes before deployment, while hotfix branches address critical production issues. The main branch represents stable code, only updated when releases or hotfixes are merged. GitFlow ensures structured workflows, encourages collaboration, and facilitates scalability and traceability in managing complex software projects. Other models like GitHub Flow and GitLab Flow offer alternative approaches to version control.

Follow the link to get more information about [Gitflow](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow)

## Continuos Integration

Continuous Integration (CI) is a software development practice that involves automatically integrating code changes from multiple developers into a shared repository frequently. It aims to catch integration issues early by regularly merging code and running automated builds, tests, and analyses. CI detects problems like compilation errors or test failures caused by code conflicts or compatibility issues. By integrating changes frequently, CI promotes collaboration, provides immediate feedback to developers, and ensures a more reliable and stable software development process. CI tools like Jenkins or Travis CI automate the build and test processes, enhancing productivity and quality while enabling faster software delivery.

## Github Actions

## Unit Tests

## Backend Tests

## Frontend Tests

