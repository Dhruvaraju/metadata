- [Learning plan](#learning-plan)
  - [General for all](#general-for-all)
    - [Note Taking](#note-taking)
    - [Version Control](#version-control)
    - [Tracking / Planning learning on own](#tracking--planning-learning-on-own)
    - [What is an Ideal Application](#what-is-an-ideal-application)
  - [User Interface Specific Learning](#user-interface-specific-learning)
    - [HTML](#html)
    - [Styling Pages](#styling-pages)
    - [Validating User inputs](#validating-user-inputs)
    - [Type script](#type-script)
    - [Jquery why you might need it](#jquery-why-you-might-need-it)
    - [Nodejs](#nodejs)
    - [NPM](#npm)
    - [Frameworks for UserInterface](#frameworks-for-userinterface)
    - [Unit Testing](#unit-testing)
    - [Integration testing](#integration-testing)
    - [Logging and Monitoring](#logging-and-monitoring)
    - [Deployment Options](#deployment-options)
  - [Services and Middleware specific learning](#services-and-middleware-specific-learning)
    - [Programming Languages](#programming-languages)
    - [Object oriented programming](#object-oriented-programming)
    - [Java understanding JVM, JRE, JDK](#java-understanding-jvm-jre-jdk)
    - [Creating console applications](#creating-console-applications)
    - [Other JVM languages](#other-jvm-languages)
    - [Dependency Management and Build Automation Tools](#dependency-management-and-build-automation-tools)
      - [System Arch](#system-arch)
    - [Frame-works](#frame-works)
    - [What is Dependency Injection and Inversion of Control](#what-is-dependency-injection-and-inversion-of-control)
    - [Service](#service)
    - [Spring and Spring boot](#spring-and-spring-boot)
    - [Spring Cloud](#spring-cloud)
      - [Config Server](#config-server)
      - [Service Discovery](#service-discovery)
      - [Circuit Breakers](#circuit-breakers)
    - [Logging and Monitoring](#logging-and-monitoring-1)
    - [Deployment Options](#deployment-options-1)
  - [Common for UI and Services](#common-for-ui-and-services)
    - [Containers](#containers)
    - [Cloud Providers](#cloud-providers)
    - [Orchestration](#orchestration)
    - [Legacy Systems](#legacy-systems)
    - [Micro-service](#micro-service)
    - [Serverless](#serverless)
  - [Full Stack Learning Sequence](#full-stack-learning-sequence)
  - [Random Information](#random-information)
  - [Discussion topics](#discussion-topics)

# Learning plan

- Determine Aim
- Find out interests
- Identity familiar tech-stack

## General for all

- Consider a simple topic and explain
- (Preferred topic) Data-formats XML.
- Break (preferably one-day).
- Ask Questions about the explained topic.

### Note Taking

- Importance of Note taking
- Digital Note taking
  - Tools / Apps available.
- Why markdown?
- Explain usage and syntax markdown.

### Version Control

- What is version control, why is it important.
- VCS systems available
- Introduction to git
  - Creating github account
  - Creating first repo
  - Visual Code IDE, Git integration with VS code

### Tracking / Planning learning on own

- Explain Agile rituals without saying its agile process.
- Follow scrum rituals
- Agile boards (Options available)

### What is an Ideal Application

- Collect Assumptions
- Twelve Factors
  - Code Base
    - One codebase tracked in revision control, many deploys
  - Dependencies
    - Explicitly declare and isolate dependencies
  - Config
    - Store config in the environment
  - Backing Services
    - Treat backing services as attached resources
  - Build, Release, Run
    - Strictly separate build and run stages
  - Processes
    - Execute the app as one or more stateless processes
  - Port Binding
    - Export services via port binding
  - Concurrency
    - Scale out via the process model
  - Disposability
    - Maximize robustness with fast startup and graceful shutdown
  - Dev / Prod Parity
    - Keep development, staging, and production as similar as possible
  - Logs
    - Treat logs as event streams
  - Admin Processes
    - Run admin/management tasks as one-off processes

## User Interface Specific Learning

> Topics are expected to be covered in same sequence order

### HTML

- Versions of HTML
- HTML5
- Semantic elements
- Micro-Data

> Should create HTML pages in the way browser understands it, not just for visual purpose.

### Styling Pages

- CSS
- Embedded and imported
- SCSS, SASS
- Selectors

> Concentrate more on selectors and SCSS

### Validating User inputs

- What is scripting.
- Scripts available.
- Javascript
- Standards of Javascript
- ECMA 6 or ES5

### Type script

- Why it is required?
- Advantages over Javascript
- Babel

> Other scripting languages, usage based on need.

### Jquery why you might need it

- What is DOM
- DOM manipulation with Selectors
- What is Ajax why do we need it

> Explain a service call using Ajax, Explain Async

### Nodejs

- What is Node
- Difference between Javascript implementation and node implementations
- Script engines
  - Internet explorer: Chakra
  - Firefox, Opera: Spider Monkey
  - Chrome: V8
  - Edge: Chromium (V8 based implementation)
- What are shim or shiv

### NPM

- What is a package manager.
- What is build automation
- Alternatives for NPM (Yarn)

### Frameworks for UserInterface

- Frameworks
- Angular, React, Vue
- Angular
  - Installation
  - Angular CLI
  - Code generation using CLI
  - Project Boot-strap
  - Explain Each file usage
  - Directives
  - Pipes
  - Decorators
  - Routing
  - Service
  - RXJS
  - State management / NGRX

### Unit Testing

- Why is it needed?
- Available frame works
- Karma
- Jest

### Integration testing

- Why is it needed?
- Available frame works
- WDIO
- Cypress

### Logging and Monitoring

- What is logging why do we need it?
- Logging tools
- Monitoring
- Monitoring Tools

### Deployment Options

- What is hosting
- Hosting options available
- What is Deploying

## Services and Middleware specific learning

> Topics are expected to be covered in same sequence order

### Programming Languages

- Different languages available
- How programing languages evolved.
- Advantages
- Options available

### Object oriented programming

- What is it?
- Why do we need it?

### Java understanding JVM, JRE, JDK

- JVM
  - How it provides platform independence
- JRE
  - Why?
- JDK
  - What is it?
  - WHy do we need it.

### Creating console applications

- Syntax
- Sample programs
- Taking user input

### Other JVM languages

- Kotlin
- Scala
- What is domain specific language

### Dependency Management and Build Automation Tools

- Dependency Management
- Build Automation
- What problem they solved.
- Maven
- Gradle

#### System Arch

- System streams
  - Input
  - Output
  - Error

### Frame-works

- Spring
- Apache Frameworks
- CRM Frame works

### What is Dependency Injection and Inversion of Control

> Explain only bare minimum about below topics

- Dependency Injection
- Inversion of control

### Service

- What is a service
- What is HTTP
- Types of services
  - SOAP
  - REST

### Spring and Spring boot

- Advantages
- How to create a project
- DIfference between Spring and spring boot
- What is JPA, ORM
- Spring DATA
- Create a sample service with spring
- SPring Initialzr
- Explain each and every file why do we need it

### Spring Cloud

- Why do we need Spring cloud?

#### Config Server

- What is configuration
- What is the need of externalization
- Create a sample project.

#### Service Discovery

- What is it why do we need it?
- Create a sample project.

#### Circuit Breakers

- What is it?
- TPS
- Why do we need Circuit breakers.

### Logging and Monitoring

- Logging
- Tools available for logging
- Log collectors
- Log visualizers.

### Deployment Options

- What is hosting
- Why do we need it.
- Options available.

## Common for UI and Services

### Containers

- How can be resources utilized effectively.
- What is Virtualization
- What are containers
- Docker
- Container alternatives
- Container repository

### Cloud Providers

- Why do we need them
- Available options
  - Azure
  - AWS
  - GCP
- Difference between cloud management and provider
- PCF

### Orchestration

- What is it.
- What is a pipe line
  - Single task
  - Multistage
- What is a job
- Jenkins
- Azure devops
- Github Actions
- Circle CI

### Legacy Systems

- Monolith
- Why do we still need them?
- System effectiveness

### Micro-service

- What is a micro-service
- Is it feasible for all purposes?
- API
- Micro Apps

### Serverless

- What does it really mean
- Creating a server less environment
- Providers

## Full Stack Learning Sequence

> Learn UI specific first then learn Service and Middleware specific

> Common for UI and Service after completing above Learn them.

## Random Information

- Chat-bots
- Straight through processing
- Cloud-first mobile first, why it is no longer actively sought off.

## Discussion topics

- Developer forums
- Conferences and developer events
- Presentations and preparing for them
  - Story telling
