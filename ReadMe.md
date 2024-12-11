
<p align="center">
  <img width="460" height="300" src="https://github.com/user-attachments/assets/1c3290f9-1996-413c-bee3-890289ba952a">
</p>

# TDTM-Tool

Welcome to the TDTM-Tool (Technical Debt Traceability Map) repository! This project is part of my Bachelor's Thesis research, and it is designed to provide a full-stack application for software quality analysis and technical debt traceability. The application leverages quality analysis tools and libraries to help users control and manage software's technical debt.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)


## Features

- React JS Client Layer application
- Spring Boot Server Layer application
- SonarQube quality analysis integration
- Neo4j graph database Data Layer service
- Dockerized services

## Installation

To set up the project locally, clone tool's repository :
   ```bash
   git clone --recurse-submodules https://github.com/kostasthomson/TDTM-Tool
   ```

## Usage

To start the dockerized full-stack application, run the following command:

```bash
docker compose up --build
```

This will start the following:
- React application at http://localhost:3005
- Spring Boot application at http://localhost:8085
- SonarQube service at http://localhost:9952
- Neo4j service at http://localhost:7474


This will create, build and run the application and all of its dependent containers.

**Services' credentials**

Αll necessary credentials are contained in the docker-compose file 
     

## Technologies
React: A JavaScript library for building user interfaces

vis.js: A JavaScript library for producing dynamic, interactive data visualizations in web browsers

Tailwind CSS: A framework for building responsive, mobile-first sites

MaterialUI: A library for react-ready, dynamic web page elements

Axios: A promise-based HTTP client for the browser and 

Node.js: A JavaScript runtime environment for hosting React applications

Java & Spring Boot: For building the backend application

Docker: For containerization of services

SonarQube: For code quality analysis

Neo4j: Graph database for storing analysis data

PostgreSQL: Relational database for SonarQube data storage

Maven: For dependency management and building the application
