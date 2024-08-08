---
title : "KNOW MORE <br> ABOUT ME"
image : "images/backgrounds/me-guitar.jpg"
button:
  button_list:
    - label : "MY CV"
      enable : true
      class: download-cv hvr-icon-hang
      link : "files/resume.pdf"
      # Mail
    - label : ""
      enable : true
      class: download-cv hvr-icon-up
      link : "mailto:tm.primitivo@protonmail.com"
      # Telegram
    - label : ""
      enable : true
      class: download-cv hvr-icon-grow
      link : "https://t.me/applinh"
      # Github
    - label : ""
      enable : true
      class: download-cv hvr-icon-rotate
      link : "https://github.com/applinh"
      # Linkedin
    - label : ""
      enable : true
      class: download-cv hvr-icon-push
      link : "https://www.linkedin.com/in/tmartin-me/"

########################### Experience ##############################
experience:
  enable : true
  title : "EXPERIENCE"
  experience_list:
    # experience item loop
    - name: Platform Reliability Engineer
      company: Qonto
      duration: January 2024 - Present
      content: |-
        \- **Enhance platform's reliability and usability by developers** by orchestrating tools that offer observability, scaling and workload protection capabilities (ArgoCD, Karpenter, Kyverno, Prometheus, etc) 
      
        \- **Eliminate toil with custom tooling (Golang)** under the form of APIs to enable self-service and Platform As A Product

        \- **Reduce maintenance lead time** around our Kubernetes Apps configuration through new strategies involving Helm and ArgoCD

        \- **Prevent incidents and help with their mitigation** with a on-point observability strategy (Prometheus, AlertManager, Grafana, Loki, ELK, etc)

        \- **Promote a "Platform as a Product" philosophy** to enhance self-service capabilities and minimize team intervention in repetitive tasks.
        
        \- **Enhance the Internal Developer Platform** by providing easy-to-use interfaces through Helm Charts, ArgoCD actions, custom infrastructure-orchestration APIs, and Terraform modules

    - name: DevSecOps Architect
      company: Respond.io
      duration: July 2023 - January 2024
      content: |-
        \- **In charge of the tooling strategy** to enhance platform's availability (AWS scale-in scale-out and deployment strategies)

        \- **Optimized cloud costs** to save 10% monthly

        \- **Architect of the IAC strategy** (Terraform, GitOps)

        \- **Responsible for the platform security strategy**, focusing on audit logs and threat modeling

    - name: Project Leader & Solution Architect
      company: Hara
      duration: September 2022 - September 2023
      content: |-
        \- **Product & Team management**

        \- **Business, marketing & functional analysis**
       
        \- **Defined technical golden paths & architecture** of the solution

        \- **Lead a dev team** around a Scrum-like methodology, with code reviews

        \- Implemented **tools** to ensure **clean code and good practices** (Lint, code coverage, TDD, SOLID, Jira, vulnerability scans, IAC, etc)

        \- **AWS architecture** with **optimized costs**

        \- **Defined Kubernetes** alternative **architecture** for scale-up

    - name: Cloud & DevOps Engineer
      company: Amadeus
      duration: March 2022 - July 2023
      content: |-
        \- **Maintaining and improving** a complete Ansible project (roles, playbooks, modules)

        \- **Led a migration from Tower to AWX**

        \- **Complete rework of the app deployment strategy** through the conception of Deployment As Code solutions with a GitOps & IAC state of mind

        \- **Design & dev of SysOps tooling** (Python CLIs) with the aim of replacing bash scripts. Always following **clean code principles** (SOLID, TDD) + tools for **better maintainability** (CI/CD, code coverage, etc)

        \- **Referent of the Azure cloud architecture strategy** (in the context of a migration)

    - name: "Web, Mobile & Ops Engineer"
      company: "MySofie"
      duration: August 2021 - March 2022
      content: |-
        \- **Fullstack Web developer** (RubyOnRails & Typescript React)

        \- **Mobile Software Architect** (Flutter/Dart/Kotlin/Swift), led a migration of a legacy app to Flutter, and implemented Clean Architecture from scratch.

        \- **Performed POCs at the request of the CTO** to evaluate technologies and support strategic technical decisions

        \- **Design and implementation of new deployment strategies** (CI/CD, Ansible, Terraform, Packer) and **cloud architecture** (AWS & Scaleway)

        \- Work on **automated disaster recovery** processes

    # experience item loop
    - name : "Co-Founder & CTO"
      company : "Primitivo"
      duration : "2019-2021"
      content : |-
        \- **Project manager & Solution Architect** on an ecosystem of 3 applications, targeting restaurants and bars in Strasbourg

        \- Three applications put into **production**

        \- Costs-optimized AWS cloud architecture
        
        \- **Scrum Master**, **Tech lead**, **FullStack Developer** role

        \- Participation in **openSource** projects
        
        \- **Architecture consulting** to third parties

    - name : "R&D Engineer apprentice"
      company : "Divalto"
      duration : "2018-2021"
      content : |-
        \- **Design and implementation of cutting-edge features** on a legacy ERP project
        
        \- **Work on synergies** between the ERP and external payment services (PayPal, PayZen, Mollie, etc)
        
        \- **Architecture, design and implementation** (from scratch) of a complete solution involving an Outlook add-in that allows to to interact with the ERP remotely

        \- **Configuration and development** (from scratch) of a complete Jennkins CI/CD (Cloud + onPremise)


########################### Studies ##############################
studies:
  enable : true
  title : "STUDIES"
  experience_list:
    # experience item loop
    - name : "CS Engineer diploma"
      company : "UTBM - Belfort, France"
      content : "Complete CS engineer school curriculum. Studies made in apprenticeship @ Divalto."
      
      
    # experience item loop
    - name : "Exchange semester (Mast. CS)"
      company : "RTU - Riga, Latvia"
      content : "
      . Service-Oriented Architecture
      <br />
      . Project Management
      <br />
      . Developments of Intelligent Software Systems
      <br />
      . Business Analytics / Data Mining
      <br />
      . Advanced Databases
      "
      
    # experience item loop
    - name : "Mechanical Engineering"
      company : "INSA - Strasbourg, France"
      content : "Lean Management, Fluid Mechanics, Thermodynamic & more"

############################### Skill #################################
skill:
  enable : true
  title : "KNOWLEDGE"
  skill_list:
    - name : "Solution Architecture (Cloud Native & Kubernetes)"
      badges: 
        - "[![AZ-900 Certified](https://img.shields.io/badge/-AZ%20900%20Certified-blue?style=for-the-badge&logo=microsoft-azure)](https://www.credly.com/badges/a0b37337-5e0d-4074-a4c7-36ace2b3b915)"
        - "[![CKA Certified](https://img.shields.io/badge/-CKA%20Certified-lightblue?style=for-the-badge&logo=kubernetes)](https://www.credly.com/badges/799e4d84-183a-482c-8f8a-5c9068c41d4d/public_url)"
      years: 4
      skill:
        value: 85
        text: Skillful +

    - name: "Software Architecture"
      years: 4
      skill:
        value: 70
        text: Skillful

    # skill item loop
    - name : "Project & Poduct Management"
      years: 4
      skill:
        value: 80
        text: Skillful +
    
        # skill item loop
    - name : "Fullstack Web Development"
      years: 5
      skill:
        value: 70
        text: Skillful

    # skill item loop
    - name : "Mobile Developement"
      years: 3
      skill:
        value: 60
        text: Proficient


# custom style
custom_class: "" 
custom_attributes: "" 
custom_css: ""
---

Hey and welcome !
My name is Thomas Martin, and I'm a 26 years old French CS engineer with 5+ years of experience working on diverse projects (Web, Mobile, System, Cloud, etc). 

I am dedicated to providing you with specialized expertise in areas such as deployment strategy, release management, and optimizing your infrastructure's ability to adapt cost-effectively to current and future demands.

Passionate about **Cloud**, **Solutions Architecture**, **Web & Mobile dev**, **DevOps philosophy**, **tech watch** and **music**.

I'm also [![AZ-900 Certified](https://img.shields.io/badge/-AZ%20900%20Certified-blue?style=for-the-badge&logo=microsoft-azure)](https://www.credly.com/badges/a0b37337-5e0d-4074-a4c7-36ace2b3b915) and [![CKA Certified](https://img.shields.io/badge/-CKA%20Certified-lightblue?style=for-the-badge&logo=kubernetes)](https://www.credly.com/badges/799e4d84-183a-482c-8f8a-5c9068c41d4d/public_url)
