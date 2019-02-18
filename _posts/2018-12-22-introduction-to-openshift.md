---
layout: post
title:  "A Jenkins Slave MultiBranch Pipeline in Openshift"
subtitle: "For Continuous Building, Testing, and Deploying your Applications"
date:   2019-02-22 23:15:00
categories: [tutorial]
---

We now live in an era where there are lots of online services a DevOps team can utilise for CI/CT/CD. However there may be some vital services that your enterprise wants to keep internal. The difficulty with this is that most internal enterprise procedures to *live* are not as good as the services built for streamlining the process.

> Introducing Openshift

I won't go into the details of what Openshift is but you are probably here beyond reasonable doubt to gain some insight into it's usuages. It will require the reader to have a basic understanding of Openshift/Kubernetes terminology.

## Setting up Jenkins In Slave Mode

- Jenkins Persistent Mode  
- Choosing Jenkins Slaves and Configuring them
- Useful Jenkins Plugins to Install
- Multi Branch Pipeline
- Initialising Jenkinsfile

## Basic Application

- Create a basic application that reads from rabbit and persists it into mongo/cassandra db
- Create a basic test harness that runs an example feature file
- Put these in a monorepo and shape Jenkinsfile to run agents in parallel
- Talk about openshift dsl commands
- Talk about moving between openshift environments environments
