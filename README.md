**Phantom Presents:** Integration Project, Fatec Prof. Jessen Vidal - 2022. 5th Semester <br>
**Client:** <a href="https://www.midall.com.br//">MidAll</a>

<br><p align="center">
 <a href="https://www.midall.com.br/"><img src="https://user-images.githubusercontent.com/80851038/163725778-498ec2e9-e8eb-45cf-a586-848e5bb1dd97.png" width="110"/></a>
</p>

<p align="center"> 
 <img src="https://img.shields.io/badge/Status%3A-Building-orange"/>
 <a href="https://www.java.com/pt-BR/"><img src="https://img.shields.io/badge/Language%3A-JAVA-red"/></a>
 <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Language%3A-VUE.js-green"/></a>
 <a href="https://www.midall.com.br/"><img src="https://img.shields.io/badge/Client%3A-MidAll-purple"/></a>
 <a href="http://fatecsjc-prd.azurewebsites.net/"><img src="https://img.shields.io/badge/Institution%3A-Fatec-red"/></a>
</p>

<p align="center">
 <a href="#executing-the-application">Executing the application</a> |  <a href="#technologies-used">Technologies</a> |  <a href="#timeline">Timeline</a> 
 |  <a href="#team-phantom">Team</a> |  <a href="#devops-concepts">DevOps</a> 
</p>

<h3 align="center">Problem</h3>
<p align="justify">
Automate the file download journey, stored on a video platform,
making this transfer to the cloud, through the development of an application like
service, having as functionality with the user only a configuration menu, which will have
the necessary parameters for the download service to process automatically, generating
alerts if processing errors occur. Save file metadata for building
a dashboard for monitoring the execution of the service and subsequent analysis of results and
indicators (e.g. number of files transferred, number of bytes transferred, time of
transfer, etc.).
</p>


<br>

## Table of contents

 - [Tecnology](#technologies-used)
 - [DevOps](#devops-concepts)
 - [Requirements](#requirements)
 - [Product Backlog](#product-backlog)  
 - [Executing the application](#executing-the-application)
 - [Timeline](#timeline)
 - [Team](#team-phantom)

<br>

## Technologies Used
<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D"/>
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=gold"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white"/>
</p>
 
<br>

## DevOps concepts

DevOps is a software development approach that combines development and operations teams to streamline processes and deliver high-quality software more efficiently. It fosters collaboration, automation, and continuous improvement. The benefits of DevOps include increased collaboration and communication, continuous integration and delivery, faster time to market, improved software quality, enhanced reliability and stability, scalability and flexibility, continuous monitoring and feedback, and cost optimization. Overall, DevOps aligns teams, accelerates software delivery, improves quality, and enhances customer satisfaction.

Used devops concepts and their authors:
----

| Concept   | Author |
|--------|-----|
| Organization of activation of continuous integration focused on the application   | [Lucas Guiraldelli](https://www.linkedin.com/in/lucasguiraldelli/)  |
| Back-end unit tests using JUnit and mockito | [Igor Ribeiro](https://www.linkedin.com/in/igor-ribeiro-8571a6210/)  |
| Front-end unit tests using Jest  | [Marcus Augusto](https://www.linkedin.com/in/mvarocha/) |
| Management and tracking of issues on the project  | [Lara Leal](https://www.linkedin.com/in/lara-leal-527b7020a/) |
| Ensure use of gitflow methodology for repository organization  | [All](https://github.com/PhatomFatec/)  |

<br>

 To see details about Used **DevOps** concepts, follow the [link](https://github.com/PhatomFatec/Midall-DataTransfer/blob/main/devops.md)
 
<br>

## Requirements

### 📌 Functional Requirements

#### Application 1:

 - Build an application that will run on a local server to configure and configure the service.
 - In this application, create a screen for system configuration (with all the settings that the current application already has) also including the limitation of network bandwidth consumption and time for checking new files for download
 - Also create a screen for setting up the api access account (keep it safe).
 - Issue an alert in the OS warning that new files have been downloaded
 - Create downloaded file history screen

#### Application 2:

 - Build an API that will be the service that will fetch the files that must be sent to the Cloud
 - Connect with the file API (use another provider, different from the one used in the previous requirement. It can be Google Drive, AWS S3, Dropbox, etc.)
 - Download the files, following the settings made in the application 1.
 - Create a dashboard to monitor executions (can be built in any BI tool, moving data from the local bank to another)

### 📌 Non-Functional Requirements

#### Application 1:

- Create authentication mechanism with application 2, hosted in the cloud (to not accept requests from unauthorized locations)

<br>

## Product Backlog

<p align="center"> 
<img src="https://media.discordapp.net/attachments/887890002741170176/1092600909663567962/Group_40.png?width=952&height=562" width="800"/> <br>
</p>
 
<br>

## Executing the application 
Access the step by step on how to run the program by clicking [Here](https://github.com/PhatomFatec/datatransfer-back/blob/main/Readme.md).

<br>

## Timeline

| Events          | Start    | End      | Status |
|-----------------|----------|----------|--------|
| **Kick off**    | 13/02/23 | 03/03/23 |   ✔️ Accomplished      |
| [Sprint 01](https://github.com/PhatomFatec/Midall-DataTransfer/blob/main/Sprints/Sprint01.md)   | 13/03/23 | 02/04/23 |   ✔️ Accomplished       |
| [Sprint 02](https://github.com/PhatomFatec/Midall-DataTransfer/blob/main/Sprints/Sprint02.md)   | 03/04/23 | 23/04/23 |   ✔️ Accomplished        |
| [Sprint 03](https://github.com/PhatomFatec/Midall-DataTransfer/blob/main/Sprints/Sprint03.md)   | 24/04/23 | 14/05/23 |   ✔️ Accomplished     |
| [Sprint 04](https://github.com/PhatomFatec/Midall-DataTransfer/blob/main/Sprints/Sprint04.md)   | 15/05/23 | 04/06/23 |   ✔️ Accomplished    |
| **Final presentation + Solutions Fair** | 13/06/23 | 14/06/23 |   ✔️ Accomplished  |

<br>

## Team Phantom

* **DEV** - Marcus Rocha &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/mvarocha/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/mvarocha)


* **DEV** - Igor Ribeiro Silva &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; 
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/igor-ribeiro-8571a6210/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/IgorRibeiro-S)

* **MASTER** - Lucas Guiraldelli da Silva &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/lucasguiraldelli/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/LucasGuiraldelli)

* **PO** - Lara Oliveira Leal &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/lara-leal-527b7020a/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/lara-leal)
