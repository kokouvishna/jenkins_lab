# Jenkins based projects

## [Project 1 - Build and deploy Java based application](/project_1/)
In this project we'll build and deploy a java based application. We build the application with maven
and deploy it using docker.
The java application is a fully fledged application with a frontent, backend and database.
 
We're going to build this application using maven. We'll also have stages for sonarqube, quality check, 
OS depedency check, and trivy file system scanning. In addition we'll be building the application using maven
and deploying the jar artifacts to nexus third party repository. Nexus is a third party repository manager tool that host
multiple versions of your artifacts.
We'll also be using docker to build the docker image, tag it and push it to a docker hub repository.
At least we'll be deploying the application inside a docker container.

## [Project 2 - Build and deploy multi-container NodeJS fullsatck application (frontend, backend and database)](/project_2/)
In this project using Jenkins we are going to provide Sonarqube analysis to perform code quality check, to see if there are
any issues/bugs/vulnerabilities with the code.
Next we're going to use OS dependency check with jenkins, using that we're going to perform vulnerability scan on
the source code.
Finally we are going to use trivy, which is another security tool. It uses multiple databases for matching issues in
the dependencies. Also trivy will do the file scanning.
Once all securities checks are done we'll be building our application and finally using docker compose we'll be
deploying the application. After the deployment it'll be accessed in a webbrowser.

## [Project x](/project_x/)
