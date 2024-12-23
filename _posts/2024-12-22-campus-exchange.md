---
layout: post
tags: [Java, Vue, Docker]
title: Campus Exchange
---
<img src="assets/images/screenshot-campusExchange.png" alt="screenshot of campus exchange">
<hr/>

This is a second-hand goods trading app that targeting student from Boston University. It allow user to login with their BU email. User after login can post goods or purchase goods. Also user can search for goods no matter they are logged in or not.

I worked on this project with 5 other developers. I was responsible to built part of the APIs on the backend and handled the CI using GitHub Action and Docker. The project was built using Java Spingboot as backend and mapped to a MYSQL database using Mybatis. The backend was constructed as a RESTful API, and the frontend which was built using Vue could access the API using HTTP requests. For CI/CD, code would be test and deployed after merge. If the build was success, a docker image would be created and upload to Docker Hub, and after the image is uploaded, it would deploy to cloud using Kubernetes with Alicould.


[GitHub Link](https://github.com/BUMETCS673/seprojects-cs673f24a2team2/)