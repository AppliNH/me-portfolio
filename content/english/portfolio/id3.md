---
title: "ID3 form webApp"
date: 2020-11-12T12:14:34+06:00
image: "https://static.thenounproject.com/png/1870030-200.png"
categories: ["Personal","OpenSource"]
description: "WebApp implementing ID3 algo"
draft: false
project_info:
- name: "Stack"
  icon: "fas fa-layer-group"
  content: "
  . ReactJS
  <br />
  . Python
  <br />
  . NestJS (NodeJS framework)
  <br />
   . Golang
  <br />
  . PostgreSQL
  <br />
  . AWS Translate
  <br />
  . Docker
  <br />
  . Docker Swarm
  "
- name: "Project Link"
  icon: "fas fa-link"
  content: "https://github.com/s-henr/ID3"
---

The webApp offers a form with multiple questions to complete, in order to provide a final answer to the question : "Will you play football ?" that the user answers with yes or no. 

Behind the curtains, we're using the ID3 algorithm to build a decision tree and reduce the number of asked questions in the form, in order to determine which questions are determinant regarding the answer of the final question.

The system can also learn from his wrongful predictions : if the final predicted answer is incorrect, the user has the ability to tell the system.

The webApp also provides a translating service, backed by AWS, which translates the form. To make some saves by not querying too much the AWS Translate API, we made the choice to cache the translations.

This project was conducted in the context of my exchange semester at Riga, Latvia, in the Master CS program.

My personal role in this project was : Project manager, Tech lead, Architect and fullstack dev.

You can read more about this project in the repo's Readme, [here](https://github.com/s-henr/ID3)