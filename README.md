[item]: # (slide)

![](http://imapex.io/images/imapex_standing_text_sm.png)

# Module: Application Quickstart

[item]: # (/slide)

## Abstract 

You have an idea for an amazing application but you aren't sure how to get started.  That's totally expected... getting the idea, and even writing the code isn't actually the difficult part in building an application.  The challenge comes in developing with discipline, keeping in mind an application isn't successful unless people use it.  In imapex our applications are designed to be easy to deploy, use and contribute code to.  This means you need to focus up front on questions like "How will others deploy my application?", "How can I quickly and easily test application changes?", and "What is my MVP and how can I build it fast!"  In this module we'll explore what makes a great imapex application, and our suggested "Code Sprint" plan.  

[item]: # (slide)

## Topics

* What makes an **imapex Application**?
* Think Small, Micro-service and MVP
* Application Pipeline Setup
* Handling Infrastructure Needs

[item]: # (/slide)

[item]: # (slide)
## What Makes an imapex Application?

* Easy Reproducabilty
* Clear Documentation
* Integrats Multiple Platforms (ideally)
* OpenSource 

[item]: # (/slide)

[item]: # (slide)

## Easy Reproducability

Building personal demos is an excellent use of time, but building a demo that can be easily leveraged by anyone extend the works value exponentially.  To be a complete imapex application until anyone can take the code and replicate it on their own.  

[item]: # (/slide)

[item]: # (slide)

## Clear Documentation 

A key to easy reproducability is clear and accurate documentation, both within the code as well as in installation and usage instructions.  Details on what the demo shows, prereqs, how to install and demo, and how to develop all need to be included in the code README file.  

[item]: # (/slide)

[item]: # (slide)

## Integrates Multiple Platforms 

Though not an absolute requirement, an imapex application should try to show how multiple architectures, platforms, or products can be brought together to provide increased value targeting the business problem being addressed.  There are many efforts spawned from individual products teams showcasing individual products, in imapex we look to showcase the concept of "the whole is greater than the sum of it's parts" 

[item]: # (/slide)

[item]: # (slide)

## OpenSource

imapex Applications are **NOT** products.  They are examples of how Cisco platforms can be developed on, and integrated together, or with other platforms to offer valuable capabilities.  Anyone is welcome to extend, change, or contribute to each and every imapex application.  

[item]: # (/slide)

[item]: # (slide)

## Application Pipeline Setup

* GitHub Repository
* Docker Hub Repository 
* Drone Build Files
* Spark Room
* Development Instance
* Production Instance

[item]: # (/slide)

[item]: # (slide)

## boilerplate examples

A few (and growing), number of boilerplate repositories are provided within the [imapex GitHub](https://github.com/imapex?utf8=✓&query=boilerplate) that can be leveraged as starting points for applications.  

[item]: # (/slide)

[item]: # (slide)

## README Standards and Expectations

A good README file is important for outlining the motivation behind a particular project repository, as well as providing the reader with an overview of how to effectively utilize the project repository.

[http://stackoverflow.com/questions/2304863/how-to-write-a-good-readme](http://stackoverflow.com/questions/2304863/how-to-write-a-good-readme)

[item]: # (/slide)

[item]: # (slide)

### Some README Guidelines

* ASCII characters only, if the README is written in English
* write it in English if possible, and ship translated version with two-letter
  language code extension like README.ja
* 80 characters or less per line
* single empty line between paragraphs
* indent using whitespace (0x20) not tab

[item]: # (/slide)

[item]: # (slide)

## imapex Development Process Suggestions

* Production deployments will be done from the master branch
* All feature development should be done via the developers fork / branch
* All feature development should have an open issue tagged enhancement for tracking purposes
* All bug fixes should have an open issue for tracking purposes

[item]: # (/slide)

[item]: # (slide)

## Sample Workflow

1. Fork an existing repository
2. Clone your fork
3. Add 'upstream' remote
4. Create a feature branch
5. develop cool feature
6. incorporate any upstream changes to your fork / branch
7. merge your feature branch
8. Open pull request to existing repostiory

[item]: # (/slide)

[item]: # (slide)

# imapex Sprint Plan

[item]: # (/slide)

[item]: # (slide)

> “By failing to prepare, you are preparing to fail.” Benjamin Franklin

[item]: # (/slide)

[item]: # (slide)

## Sprint Overview

* 3 Week Long Sprint
* Kickoff on Friday Before 
* Close down Monday After
* Spark Check-ins Every Tuesday
* 30 Min WebEx Stand-Ups Every Friday

[item]: # (/slide)

[item]: # (slide)

## Week 1 Goals

* Identify User Stories in Scope
* Plan and Design the Micro-Services to be built
* What infrastructure and external services will be used/needed
* Divide up workload across dev team
* Design and construct pipeline

[item]: # (/slide)

[item]: # (slide)

## Week 2 Goals

* Do actual coding of individual services and components
* Test and Integrate elements together
* Repeat until Sprint stories are complete

[item]: # (/slide)

[item]: # (slide)

## Week 3 Goals

* Ensure Code is well documented and packaged
* Create Install and Use Documentation
* Record 5 Minute or Less “Marketing Video"
* Have someone outside of the Dev Team test installation and deployment

[item]: # (/slide)
