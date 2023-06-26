---
layout: ../../layouts/project.astro
title: Shotshare
client: Self
publishDate: 2022-06-14 00:00:00
img: https://images.unsplash.com/photo-1668031772591-435d47be5f75?fit=crop&w=1400&h=700&q=75
description: |
  Final career project, small social network
tags:
  - design
  - dev
  - deploy 
  - documentation
---

For my final course project, I wanted to do something special to demonstrate to my tutors everything I had learned with them, for this I created Shotshare, a multiplatform social network application, consisting of three projects. 

1. - An ApiRest in [NodeJS](https://nodejs.org/en).
2. - A FrontEnd of the application made in [ReactJS](https://react.dev/).
3. - A mobile application made in [Cordova](https://cordova.apache.org/).

The APIRest served as a BackEnd where I stored user information in a relational database [MariaDB](https://mariadb.org/), I also used the [PM2](https://pm2.keymetrics.io/) tool, a redundancy system for my application, to always keep it active. In the BackEnd we stored high and low quality images, depending on the section of the application the user was in, we displayed one or the other. Additionally, this was hosted on a local machine and through [CloudFlare](https://www.cloudflare.com/es-es/) we did a proxy to redirect traffic to the application.

For the FrontEnd, I used [ReactJS](https://react.dev/), because I had already used it in class, so it was a framework that was already familiar to me. It was composed of Hooks and Classes, as an additional feature I took on the task of implementing a unique functionality that allowed users to publish games within the app, games based on [WebGL](https://en.wikipedia.org/wiki/WebGL).

For the mobile application, I used [Cordova](https://cordova.apache.org/) a cross-platform tool that allowed me to inherit everything previously done in the desktop application into a mobile application. For this, I developed the necessary modules that allowed me to embed my application in the app. In addition, I added security measures to ensure that the application complied with the standards that Android and iOS require for applications to be published.

In addition, I acquired the domain Shotshare.es through [IONOS](https://www.ionos.com/?ar=1).
