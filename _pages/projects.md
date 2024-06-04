---
title:
layout: default
permalink: /projects/
published: true
---

#### [Uncertainty Quantification for Deep Neural Network](https://github.com/sayemimtiaz/Uncertainty-Quantification-in-DNN){:target="_blank" rel="noopener"}

This research-based project was developed as part of a graduate-level course at *Iowa State University*. In this project, we introduce a novel probabilistic first-order type system, *Uncertain<T>*, which allows programmers to explicitly represent the uncertainty of parameters involved in deep learning. This type system supports algebra over random variables, enabling the propagation of hyperparameter uncertainty through calculations, ultimately improving convergence speed and accuracy. By abstracting low-level statistical details, *Uncertain<T>* is designed to be user-friendly and accessible to a wide range of users. Developed in Python, our evaluation demonstrates that this approach helps in selecting hyperparameter values more effectively than traditional grid or random search methods.

#### [News App](https://github.com/sayemimtiaz/newsapp){:target="_blank" rel="noopener"}

This is a simple web application based on the Java Spring Boot framework for creating news stories and accessing them in different data formats for consumption. I developed this web application as part of an assessment for a Java Developer position at [Cefalo](https://www.cefalo.com/en/) in 2016, which led to a job offer from them. The application uses an [in-memory SQL database](https://hsqldb.org/) for persisting data and [Thymeleaf](https://www.thymeleaf.org/) for rendering the HTML. The application has been developed using an [MVC architectural pattern](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller), promoting a loosely coupled design of the different components, making it scalable and easily maintainable. This application can serve as a good starting point for aspiring full-stack web developers aiming to leverage an MVC architecture and the Java ecosystem.

#### [News App Again](https://github.com/sayemimtiaz/NewsApp-with-Angular-MongoDB){:target="_blank" rel="noopener"}

This is the *News App* redone using a different technology stack as a [single-page application (SPA)](https://en.wikipedia.org/wiki/Single-page_application). It uses a [NoSQL database](https://www.mongodb.com/) instead of an SQL one for its persistence system. The front end is built with [AngularJS](https://angularjs.org/) to render the view and design it as a SPA. Additionally, it automates both back-end and front-end dependency management using [Maven](https://maven.apache.org/) and [Bower](https://bower.io/).

#### [Hydrogen Web Wrapper](https://github.com/sayemimtiaz/HydrogenWeb){:target="_blank" rel="noopener"}


This project provides a web wrapper for a [bug fixing patch verification tool](https://dl.acm.org/doi/abs/10.1145/2568225.2568304) called [Hydrogen](https://github.com/iowastateuniversity-programanalysis/hydrogen). Given a patch, it aims to identify whether it breaks existing functionality. I developed this web wrapper as part of a class project at *Iowa State University*. Given multiple versions of a file, it allows users to select which pairs to analyze and run analysis on a chosen pair of files by creating a Hydrogen Docker instance on-demand. It then allows users to visualize the analysis results interactively and produce relevant demographics for the patch. I used [Spring Boot](https://spring.io/projects/spring-boot) to develop the back end and [spotify docker-client](https://mvnrepository.com/artifact/com.spotify/docker-client) to manage on-demand Docker instances.



