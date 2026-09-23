# TABLE OF CONTENTS

## [Part 1 — Fundamentals](#part-1--fundamentals)
- [1. Big Picture of Software Development](#1-big-picture-of-software-development)
- [2. Programming Languages](#2-programming-languages)
- [3. Framework vs Library](#3-framework-vs-library)
- [4. Runtime](#4-runtime)

## [Part 2 — Java](#part-2--java)
- [5. Java](#5-java)
- [6. JVM](#6-jvm)
- [7. JDK](#7-jdk)
- [8. JRE](#8-jre)
- [9. Spring](#9-spring)
- [10. Spring Boot](#10-spring-boot)

## [Part 3 — Python](#part-3--python)
- [11. Python](#11-python)
- [12. Django](#12-django)
- [13. Flask](#13-flask)
- [14. FastAPI](#14-fastapi)
- [15. Pandas](#15-pandas)
- [16. BeautifulSoup](#16-beautifulsoup)

## [Part 4 — JavaScript & Frontend](#part-4--javascript--frontend)
- [17. JavaScript](#17-javascript)
- [18. Node.js](#18-nodejs)
- [19. Express.js](#19-expressjs)
- [20. HTML](#20-html)
- [21. CSS](#21-css)
- [22. React](#22-react)

## [Part 5 — Backend & APIs](#part-5--backend--apis)
- [23. API](#23-api)
- [24. HTTP](#24-http)
- [25. HTTPS](#25-https)
- [26. HTTP Methods](#26-http-methods)
- [27. JSON](#27-json)

## [Part 6 — Web Scraping](#part-6--web-scraping)
- [28. Web Scraping](#28-web-scraping)
- [29. BeautifulSoup](#29-beautifulsoup)
- [30. Selenium](#30-selenium)

## [Part 7 — Databases](#part-7--databases)
- [31. Database](#31-database)
- [32. SQL](#32-sql)
- [33. MySQL](#33-mysql)
- [34. MongoDB](#34-mongodb)

## [Part 8 — Cloud & Deployment](#part-8--cloud--deployment)
- [35. Cloud Computing](#35-cloud-computing)
- [36. AWS](#36-aws)
- [37. Docker](#37-docker)
- [38. Kubernetes](#38-kubernetes)
- [39. CI/CD](#39-cicd)

## [Part 9 — Version Control](#part-9--version-control)
- [40. Git](#40-git)
- [41. GitHub](#41-github)

## [Part 10 — Architecture](#part-10--architecture)
- [42. Monolith](#42-monolith)
- [43. Microservices](#43-microservices)

## [Part 11 — Security](#part-11--security)
- [44. Authentication](#44-authentication)
- [45. Authorization](#45-authorization)
- [46. Basic Application Security](#46-basic-application-security)

## [Part 12 — Testing & Networking](#part-12--testing--networking)
- [47. Testing](#47-testing)
- [48. Networking](#48-networking)

## [Part 13 — Development Methodologies](#part-13--development-methodologies)
- [49. Waterfall](#49-waterfall)
- [50. Agile](#50-agile)
- [51. Scrum](#51-scrum)
- [52. Kanban](#52-kanban)

## [Part 14 — Learning Roadmaps](#part-14--learning-roadmaps)
- [53. Complete Mental Map](#53-complete-mental-map)
- [54. Java Backend Roadmap](#54-java-backend-roadmap)
- [55. Python Backend Roadmap](#55-python-backend-roadmap)
- [56. Web Scraping Roadmap](#56-web-scraping-roadmap)

- [FINAL REVISION MAP](#final-revision-map)

---

# Part 1 — Fundamentals

### 1. Big Picture of Software Development

Software development includes programming languages, frontend, backend, databases, APIs, deployment, cloud, testing, security, and networking. Each technology has a specific role in the overall system.

The important thing is to understand how the pieces connect rather than memorizing them individually.

Basic flow:

Language → Framework/Library → Application → API → Database → Deployment → Production

### 2. Programming Languages

A programming language is used to write instructions that a computer can execute. Different languages are commonly associated with different types of development, although many languages can be used for multiple purposes.

Examples include Java, Python, and JavaScript.

Basic idea:

Java / Python / JavaScript → Applications

### 3. Framework vs Library

A library provides reusable functionality that your program calls when needed. Examples include Pandas, NumPy, Requests, and BeautifulSoup.

A framework provides a larger structure for building an application. Examples include Spring Boot, Django, Flask, and FastAPI.

Remember:

Library → Your code calls it

Framework → Your application is built within it

### 4. Runtime

A runtime is the environment or software that allows a program to execute. Different programming languages use different runtime environments.

For example, Java commonly runs through the JVM, while server-side JavaScript can run through Node.js.

# Part 2 — Java

### 5. Java

Java is a general-purpose programming language commonly used for backend development, enterprise applications, large-scale systems, and distributed systems.

Java itself is not a framework or library. It is the language on which technologies such as Spring and Spring Boot can be used.

### 6. JVM

JVM stands for Java Virtual Machine. It is the environment that runs Java bytecode after Java source code has been compiled.

Flow:

Java Code → Compiler → Bytecode → JVM → Program Runs

The JVM is an important part of Java's platform-independent approach.

### 7. JDK

JDK stands for Java Development Kit. It provides the tools required to develop Java applications.

Conceptually:

JDK → Development Tools + JRE → JVM

A Java developer normally works with the JDK when developing applications.

### 8. JRE

JRE stands for Java Runtime Environment. It provides the environment required to run Java applications.

Conceptually:

JRE → JVM + Runtime Libraries

The JRE is therefore focused on running Java applications rather than developing them.

### 9. Spring

Spring is a Java application framework/ecosystem that provides infrastructure for building Java applications.

It provides functionality related to dependency injection, web applications, database integration, security, configuration, and application architecture.

### 10. Spring Boot

Spring Boot is built on top of Spring and makes it easier to create and run Spring applications.

It provides conventions and automatic configuration, reducing the amount of configuration developers need to handle manually.

Typical connection:

Java → Spring Boot → REST API → Service → Repository → Database

# Part 3 — Python

### 11. Python

Python is a programming language used for backend development, automation, data analysis, AI/ML, scripting, and web scraping.

Python has a large ecosystem of libraries and frameworks, which makes it useful across many different areas of software development.

### 12. Django

Django is a Python web framework used to build web applications.

It provides functionality such as URL routing, database interaction, authentication, forms, admin interfaces, and security-related protections.

Connection:

Python → Django → Web Application → Database

### 13. Flask

Flask is a lightweight Python web framework.

It provides the basics needed to create web applications and APIs while leaving more architectural decisions to the developer.

Connection:

Python → Flask → Route → Function → Response

### 14. FastAPI

FastAPI is a Python framework designed for building APIs, particularly HTTP APIs.

It uses modern Python features such as type hints and provides automatic API documentation and validation.

Connection:

Python → FastAPI → HTTP Endpoint → Business Logic → Database

### 15. Pandas

Pandas is a Python library for data manipulation and analysis.

It is useful for working with structured data, including filtering, cleaning, transforming, and analyzing datasets.

Flow:

CSV → Pandas → DataFrame → Analysis

### 16. BeautifulSoup

BeautifulSoup is a Python library for parsing HTML/XML.

It makes it easier to locate HTML elements and extract information from webpages.

Flow:

HTML → BeautifulSoup → Find Elements → Extract Data

# Part 4 — JavaScript & Frontend

### 17. JavaScript

JavaScript is a programming language commonly used for web development.

It can run inside a browser for frontend development and can also run outside the browser using Node.js.

Connection:

JavaScript → Browser → Frontend

or

JavaScript → Node.js → Backend

### 18. Node.js

Node.js is a JavaScript runtime environment that allows JavaScript to run outside the browser.

It can be used to create backend applications and servers.

Connection:

JavaScript → Node.js → Backend → API → Database

### 19. Express.js

Express.js is a web framework for Node.js.

It makes it easier to create web servers, routes, REST APIs, and middleware.

Remember:

JavaScript = Language

Node.js = Runtime

Express.js = Backend Framework

### 20. HTML

HTML is a markup language used to structure web pages.

It defines elements such as headings, paragraphs, buttons, images, links, and forms.

Simple idea:

HTML = Structure

### 21. CSS

CSS is a stylesheet language used to control the appearance and layout of webpages.

It controls things such as fonts, spacing, colors, layouts, responsive design, and animations.

Simple idea:

CSS = Presentation

### 22. React

React is a JavaScript library for building user interfaces.

It allows developers to create reusable components and build complex interfaces by combining those components.

For example:

Application → Navbar + Login + ProductList + Footer

React manages the UI based on application state.

# Part 5 — Backend & APIs

### 23. API

API stands for Application Programming Interface. It provides a defined way for different software components to communicate.

A common web application flow is:

Frontend → API → Backend → Database

### 24. HTTP

HTTP stands for Hypertext Transfer Protocol. It defines how requests and responses are exchanged between clients and servers.

Flow:

Client → HTTP Request → Server → HTTP Response → Client

### 25. HTTPS

HTTPS is HTTP protected using TLS encryption.

It helps protect communication between a client and server against interception and tampering.

Flow:

Browser ⇄ Encrypted HTTPS Connection ⇄ Server

### 26. HTTP Methods

HTTP methods describe the operation a client wants to perform.

| Method | Purpose |
|---|---|
| GET | Retrieve data |
| POST | Create/submit data |
| PUT | Replace/update a resource |
| PATCH | Partially update a resource |
| DELETE | Delete a resource |

### 27. JSON

JSON is a data-interchange format commonly used by APIs.

It allows applications to exchange structured information.

Connection:

Frontend → JSON → API → Backend

# Part 6 — Web Scraping

### 28. Web Scraping

Web scraping is the process of programmatically collecting information from websites.

A simplified process is:

Website → Request → HTML → Parse → Extract Data → Save Data

### 29. BeautifulSoup

BeautifulSoup is useful when you have HTML and want to find elements and extract information from that HTML.

It is especially useful for parsing webpages where the required information is already present in the HTML.

### 30. Selenium

Selenium is a browser automation framework/tool.

It can automate browser actions such as opening webpages, clicking buttons, entering information, navigating pages, and reading page content.

It is also widely used for automated browser testing.

# Part 7 — Databases

### 31. Database

A database is a system used to store, organize, and retrieve data.

Applications use databases to persist information such as users, products, orders, and payments.

Connection:

Application → Database → Persistent Data

### 32. SQL

SQL stands for Structured Query Language.

It is used to interact with relational databases, including retrieving, inserting, updating, and deleting data.

Example idea:

SELECT → FROM → WHERE

### 33. MySQL

MySQL is a relational database management system (RDBMS) that uses SQL.

It is useful when applications have structured data and relationships between entities such as users, products, and orders.

### 34. MongoDB

MongoDB is a NoSQL document database.

Instead of organizing data primarily into relational tables, it stores information in document-oriented structures.

Basic idea:

Application → MongoDB → Documents

# Part 8 — Cloud & Deployment

### 35. Cloud Computing

Cloud computing means using computing resources provided through cloud platforms rather than managing all physical infrastructure yourself.

Cloud platforms can provide servers, storage, databases, networking, and computing resources.

### 36. AWS

AWS stands for Amazon Web Services. It is a cloud platform that provides many different infrastructure and application services.

Examples include EC2 for compute, S3 for storage, RDS for relational databases, Lambda for serverless functions, and IAM for access management.

### 37. Docker

Docker is a platform for building and running containers.

A container packages an application and its dependencies so the application can run consistently across different environments.

Flow:

Application + Dependencies → Docker Image → Container

### 38. Kubernetes

Kubernetes is a container orchestration platform.

It helps manage many containers, including scaling them, handling failures, and coordinating how they run.

Remember:

Docker → Containers

Kubernetes → Orchestrates Containers

### 39. CI/CD

CI/CD refers to practices that automate software building, testing, and delivery/deployment.

Typical flow:

Git Push → Build → Test → Deploy → Production

# Part 9 — Version Control

### 40. Git

Git is a distributed version-control system.

It tracks changes to code and allows developers to maintain versions, create branches, commit changes, merge work, and collaborate.

### 41. GitHub

GitHub is a platform for hosting and collaborating on Git repositories.

It provides features such as repositories, pull requests, issues, code reviews, and GitHub Actions.

Remember:

Git = Version Control

GitHub = Collaboration/Hosting Platform

# Part 10 — Architecture

### 42. Monolith

A monolith is an architectural approach where an application is organized as one main application.

For example:

One Application → Users + Orders + Payments

A monolith is simply an architectural choice; it is not automatically good or bad.

### 43. Microservices

Microservices is an architectural approach where an application is divided into multiple relatively independent services.

For example:

Application → User Service + Order Service + Payment Service

The services can communicate through APIs or messaging systems.

# Part 11 — Security

### 44. Authentication

Authentication answers:

"Who are you?"

For example:

Username + Password → Authentication → Identity Confirmed

Authentication establishes the identity of a user.

### 45. Authorization

Authorization answers:

"What are you allowed to do?"

For example:

User → Authorization → Permission Check → Action

Remember:

Authentication = Identity

Authorization = Permissions

### 46. Basic Application Security

Important security concepts include password hashing, HTTPS/TLS, sessions, JWT, OAuth, CORS, CSRF, SQL injection, XSS, input validation, and secrets management.

You do not need to become a cybersecurity specialist immediately, but a backend developer should understand the basic purpose of these concepts.

# Part 12 — Testing & Networking

### 47. Testing

Testing checks whether software behaves as expected.

Common levels include:

Unit → Integration → System → End-to-End

Unit tests check small pieces of code, while integration tests check whether components work together.

### 48. Networking

Networking explains how computers and applications communicate.

A useful high-level flow is:

Internet → IP → DNS → TCP → HTTP/HTTPS → API → Backend

Important concepts include IP addresses, DNS, ports, TCP/IP, headers, cookies, sessions, and TLS.

# Part 13 — Development Methodologies

### 49. Waterfall

Waterfall is a more sequential development model.

Flow:

Requirements → Design → Development → Testing → Deployment

### 50. Agile

Agile emphasizes iterative development, feedback, and adaptation.

Instead of treating development as one large sequence, work is generally delivered and adjusted through repeated cycles.

### 51. Scrum

Scrum is a framework commonly used to organize Agile development.

Important concepts include Sprints, Backlog, Daily Scrum, Sprint Review, and Retrospective.

### 52. Kanban

Kanban is a workflow-management approach that visualizes work through different stages.

The goal is to make work visible and manage its movement through the workflow.

# Part 14 — Learning Roadmaps

### 53. Complete Mental Map

The overall structure to remember is:

Programming Language

↓

Framework / Library

↓

Frontend / Backend

↓

API

↓

HTTP / HTTPS

↓

Database

↓

Docker

↓

Cloud

↓

CI/CD

↓

Production

Around everything:

Git + Testing + Security + Networking + Monitoring + System Design

### 54. Java Backend Roadmap

A Java backend learning path can be organized as:

Java → OOP → Collections/Exceptions/Generics → JVM/JDK → SQL → Spring → Spring Boot → REST APIs → HTTP/HTTPS → Database → JPA/Hibernate → Testing → Git/GitHub → Docker → AWS → CI/CD → System Design → Security

### 55. Python Backend Roadmap

A Python backend learning path can be organized as:

Python → OOP → Modules/Packages/Exceptions → Virtual Environments/pip → SQL → Django/FastAPI → REST APIs → HTTP/HTTPS → Database → ORM → Testing → Git/GitHub → Docker → AWS → CI/CD → System Design → Security

### 56. Web Scraping Roadmap

A web-scraping path can be organized as:

Python → HTTP → HTML → CSS Selectors → Requests → BeautifulSoup → Selenium/Playwright → Data Cleaning → Pandas → CSV/Database

## FINAL REVISION MAP

The entire subject can be remembered as one connected system:

Languages
Java | Python | JavaScript

↓

Frameworks & Libraries
Spring Boot | Django | FastAPI | Express | React | Pandas | BeautifulSoup

↓

Frontend / Backend

↓

APIs
HTTP | HTTPS | JSON

↓

Databases
SQL | MySQL | MongoDB

↓

Deployment
Docker | Kubernetes | Cloud | AWS

↓

Delivery
Git | GitHub | CI/CD

↓

Professional Development
Testing | Security | Networking | System Design

This is the structure you should use for studying: first the Table of Contents, then each topic, with a short 2–3 line explanation of what it is, why it matters, and where it connects.
