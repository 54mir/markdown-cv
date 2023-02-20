---
layout: cv
title: CV of Samir Patel
---

# Samir Patel

*Software Engineer II*
*samirpatel@utexas.edu | 254.396.7295 | Seattle, WA | github.com/54mir*

  
## Experience


### Amazon

`10/2022 – Present`
*Software Development Engineer*
- Designed a serverless architecture for an operations website. Decoupled using API gateway, queues, lambdas, and containers.  
- Serves as a platform of modules that automate previously manual operations process; on-call developers who encounter a manual investigation task will be able to easily extend the toolbox with automations saving others from that work.  
- Provides access control at the module level, allowing admins to define which groups can access which modules. 

  
### FeatureBase 

`04/2022 – 10/2022`
*Software Engineer II*
- Designed and implemented support for variables in FeatureBase’s query language / executor 
- Owned the release of a community version of FeatureBase along with the associated metrics and monitoring 
- Maintained Go backend system with bug fixes and feature development   

`09/2021 – 04/2022`
*Software Engineer I*
- Added security layer to the database using the oAuth2 protocol to authenticate users against their identity provider.  
- Implemented authorization using user’s group membership within their identity provider 
- Built out a CI pipeline for a new code repository   


### Amazon

`06/2021 – 09/2021`
*Software Engineering Intern*
- Designed and implemented a security module for the internal audit team that perfomed scans of direct and transitive dependencies to identify vulnerabilities
- The module obtained the dependency closure of a package, intelligently matched each dependency against Common Platform Enumeration (CPE) name, cross referenced against multiple vulnerability databases, and generated a report with the findings 
- Improved performance by using a custom implementation of trie data structure for scanning version strings
- AWS services used: Lambda, S3, CloudFormation 

  
### FeatureBase

`03/2021 – 06/2021`
*Software Engineering Intern* 
- Owned the production of a plug-in that connected FeatureBase as a data source to Grafana using Go and React. 
- Implemented support for time-based datatypes in FeatureBase
- Implemented features and bug fixes for data ingestion. 

  

### University of Pennsylvania

`01/2021 – 05/2021`
*Graduate Teaching Assistant*
- TA for CIT 596: Algorithms and Computation course in the School of Engineering and Applied Sciences 

### Sankalpa Academy

`07/2018 – 01/2020`
*Curriculum Developer*
- Created software-based curriculum and assessment tools. This included a database application to assist teachers in monitoring each student’s learning plan; and a diagnostic app that let teachers measure students’ reading fluency in 80% less time. 

## Education

 
### University of Pennsylvania

`01/2020 - 05/2022`
*Master of Computer and Information Technology | GPA: 3.93*


  
### University of Texas: Austin

`09/2013 – 05/2016`
*Master of Educational Psychology | GPA: 3.88*
 

`01/2011 – 05/2013`
*Bachelor of Psychology with High Honors | GPA: 3.92*
  

## Skills 

  
### Languages, Protocols and Libraries:
- Go, Python, Java, Scala, C++, C, SQL, Terraform, Bash, LLVM, JavaScript, Docker 
- http, oAuth2, grpc, etcd, Chord, Raft, Pandas, NumPy, Matplotlib, Django, React 


## Projects 


### Distributed Search Engine on Chord protocol | C++ 

  

- Created a peer-to-peer search engine running over a distributed hash table using the Chord protocol 
- Supported lookup of documents based on keywords 
- Included consistent hashing and finger tables to improve efficiency  

  

### Dynamic Automated Software Analyzer | C++, C, LLVM IR 

  

- Implemented a dynamic symbolic execution engine that generated inputs guided by the branching behavior of the program.  Used LLVM passes to instrument C programs. Tool found assignments for input variables that would crash the input program. 
- Developed a fuzzer that discovered division-by-zero bugs in C programs; and a Delta Debugger that took those failing inputs and used binary search to minimize it to its 1-minimal form. 

  

### Database Design
`MySQL, Typescript, React, Python` 
- Designed a database with over 1.5M tuples across 21 tables using the entity-relationship model.  
- Scraped, cleaned, and normalized datasets for ingestion. 
- Built a web-application using React and Leaflet map API to offer a complex search interface to users.  
- Optimized query performance by building indices, materializing views, and pushing selections and projections. 

  

### Assembler / Reverse Assembler | C, Assembly  

  

- Created an interpreter to translate assembly code to machine code; and a reverse assembler to translate machine code to assembly as part of a Systems course project. Utilized knowledge of low-level computer architecture to interpret instruction set.