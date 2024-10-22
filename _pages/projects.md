---
title:
layout: default
permalink: /projects/
published: true
---

## Research Projects
  
#### [Boa Python](https://github.com/boalang/compiler/tree/pydatagen){:target="_blank" rel="noopener"}

[Boa](https://boa.cs.iastate.edu/) is a [domain-specific language](https://en.wikipedia.org/wiki/Domain-specific_language) developed to facilitate mining software repositories (MSR) for research. It leverages the [MapReduce algorithm](https://en.wikipedia.org/wiki/MapReduce) to scale the mining process to hundreds of thousands of projects. Originally designed for Java-based projects, Boa eases MSR tasks significantly. 

In this project, I extended Boa to support Python-based projects, enabling large-scale program analysis for the rapidly growing field of Python, particularly in machine learning. This involved adapting the Eclipse Dynamic Language Toolkit (DLTK) for Python, which had long been unsupported. I extended the [DLTK Python](https://projects.eclipse.org/projects/technology.dltk) to accommodate new features introduced in Python 3.0 and beyond. Additionally, I added support for converting parsed Python sources into a language-independent [Abstract Syntax Tree (AST)](https://en.wikipedia.org/wiki/Abstract_syntax_tree) format for Boa and implemented advanced program analysis features such as [alias analysis](https://en.wikipedia.org/wiki/Alias_analysis) and [def-use chain analysis](https://en.wikipedia.org/wiki/Use-define_chain) for Python.



#### [Uncertainty Quantification for Deep Neural Network](https://github.com/sayemimtiaz/Uncertainty-Quantification-in-DNN){:target="_blank" rel="noopener"}

This research-based project was developed as part of a graduate-level course at *Iowa State University*. In this project, we introduce a novel probabilistic first-order type system, <i>Uncertain<T></i>, which allows programmers to explicitly represent the uncertainty of parameters involved in deep learning. This type system supports algebra over random variables, enabling the propagation of hyperparameter uncertainty through calculations, ultimately improving convergence speed and accuracy. By abstracting low-level statistical details, *Uncertain<T>* is designed to be user-friendly and accessible to a wide range of users. Developed in Python, our evaluation demonstrates that this approach helps in selecting hyperparameter values more effectively than traditional grid or random search methods.

#### [High-Resolution Traffic Data Analysis System](https://journals.sagepub.com/doi/abs/10.1177/0361198120918869){:target="_blank" rel="noopener"}


During my time at [Mississippi State University](https://www.msstate.edu/), I developed a comprehensive system for monitoring and analyzing the performance of the traffic signal system for the [Mississippi Department of Transportation](https://mdot.ms.gov/). This system provides an effective interface to analyze traffic data collected through Wi-Fi sensors placed at various road intersections. Notably, it enables the evaluation of traffic progressions on arterials using both the existing Purdue Coordination Diagram and a novel Multi-intersection Coordination Diagram. [The system](https://actionlab.uta.edu/UTAIM/) also forms the basis for addressing many other real-world traffic signal challenges, facilitated by [Dr. Pengfei Li's research group](https://actionlab.uta.edu/) at the [University of Texas at Arlington](https://www.uta.edu/).


## Industrial Projects

#### [Prison Inmate Database System](https://www.thedailystar.net/city/database-prisoners-launched-rab-hq-214240){:target="_blank" rel="noopener"}
As part of my role as a software engineer at [TigerIT Bangladesh Ltd.](https://www.tigerit.com/), I worked on a number of industrial-scale projects, including the prison inmate system. In this project, we developed a comprehensive system for efficiently indexing prisoners, overseen by the Rapid Action Battalion (RAB), a law-enforcing agency in Bangladesh. The project has three distinct modules: a [.NET](https://dotnet.microsoft.com/) desktop module to enroll prisoners, including biometric information; a backend that serves as a [Spring Web Service](https://spring.io/projects/spring-ws) operating with the SOAP protocol; and an administrative web portal that provides efficient searching and configuration of the system.

I was a lead developer in this project, primarily responsible for the administrative portal and backend web services. To develop this system, we leveraged frameworks such as Spring and Hibernate. The administrative portal was developed using an MVC pattern enabled by Spring MVC. Security in both the web service and the portal was tightened through Spring Security, and the front end was designed using Bootstrap and JavaScript.

#### [Machine Readable Passport System for Nepal Government](https://kathmandupost.com/valley/2015/11/24/machine-readable-passport-live-enrolment-service-begins){:target="_blank" rel="noopener"}


Similar to the Prison Inmate System, this project was also accomplished during my time at TigerIT Bangladesh Ltd. It had three distinct modules: a .NET desktop client, an administrative portal, and a backend web service. I was primarily involved in the development of the desktop client responsible for capturing the demographic and biometric information of users. To that end, I implemented this module using frameworks such as .NET and [NHibernate](https://nhibernate.info/). I also worked with the APIs of various biometric devices, including fingerprint scanners, iris scanners, document scanners, and signature pads, to integrate them with our enrollment system.




## Academic Projects
#### [Delta Debugging](https://github.com/sayemimtiaz/delta_debugging){:target="_blank" rel="noopener"}


As part of a class project at Iowa State University, I developed a tool that utilizes [delta debugging](https://en.wikipedia.org/wiki/Delta_debugging) to identify bug-inducing changes in C programs. This tool takes a set of changes and a test suite then employs a divide-and-conquer strategy to pinpoint the minimal set of changes that may have introduced a bug. The tool was implemented in Python.

#### [Hydrogen Web](https://github.com/sayemimtiaz/HydrogenWeb){:target="_blank" rel="noopener"}


This project provides a web wrapper for a [bug fixing patch verification tool](https://dl.acm.org/doi/abs/10.1145/2568225.2568304) called [Hydrogen](https://github.com/iowastateuniversity-programanalysis/hydrogen). Given a patch, it aims to identify whether it breaks existing functionality. I developed this web wrapper as part of a class project at *Iowa State University*. Given multiple versions of a file, it allows users to select which pairs to analyze and run analysis on a chosen pair of files by creating a Hydrogen Docker instance on-demand. It then allows users to visualize the analysis results interactively and produce relevant demographics for the patch. I used [Spring Boot](https://spring.io/projects/spring-boot) to develop the back end and [spotify docker-client](https://mvnrepository.com/artifact/com.spotify/docker-client) to manage on-demand Docker instances.

## Demonstrative Projects

#### [News App](https://github.com/sayemimtiaz/newsapp){:target="_blank" rel="noopener"}

This is a simple web application based on the Java Spring Boot framework for creating news stories and accessing them in different data formats for consumption. I developed this web application as part of an assessment for a Java Developer position at [Cefalo](https://www.cefalo.com/en/) in 2016, which led to a job offer from them. The application uses an [in-memory SQL database](https://hsqldb.org/) for persisting data and [Thymeleaf](https://www.thymeleaf.org/) for rendering the HTML. The application has been developed using an [MVC architectural pattern](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller), promoting a loosely coupled design of the different components, making it scalable and easily maintainable. This application can serve as a good starting point for aspiring full-stack web developers aiming to leverage an MVC architecture and the Java ecosystem.

#### [News App Again](https://github.com/sayemimtiaz/NewsApp-with-Angular-MongoDB){:target="_blank" rel="noopener"}

This is the *News App* redone using a different technology stack as a [single-page application (SPA)](https://en.wikipedia.org/wiki/Single-page_application). It uses a [NoSQL database](https://www.mongodb.com/) instead of an SQL one for its persistence system. The front end is built with [AngularJS](https://angularjs.org/) to render the view and design it as a SPA. Additionally, it automates both back-end and front-end dependency management using [Maven](https://maven.apache.org/) and [Bower](https://bower.io/).







