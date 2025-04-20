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
        Senior SRE position with responsibilities around reducing incidents MTTR and their blast radius, while improving overall platform’s reliability at low costs.
      
        \- **Designed and implemented a new multi-clusters Kubernetes platform** built from the ground up with PCI-DSS compliance, high resiliency, and a comprehensive disaster recovery (DR) strategy.

        \- **Led the design and implementation of Canary deployments**, enabling automatic rollbacks and significantly reducing incident MTTR and blast radius

        \- **Promote a "Platform as a Product" philosophy** to enhance self-service capabilities and minimize team intervention in repetitive tasks.

        \- **Reduced maintenance lead time by 60% around our Kubernetes clusters configuration** through innovative strategies involving Terraform, Helm and ArgoCD

        \- **Improved developer velocity and platform reliability** through initiatives around Kubernetes deployment workflows and internal APIs; using Helm Charts, ArgoCD, custom orchestration APIs, and Terraform modules.

        \- **Prevent incidents and help with their mitigation** with a on-point observability strategy (Prometheus, AlertManager, Grafana, Loki, ELK, etc)

    - name: DevSecOps Architect
      company: Respond.io
      duration: July 2023 - January 2024
      content: |-
        \[Unfortunately short experience as I had to resign due to personal matters.\]

        \- **In charge of the tooling strategy** to enhance platform's availability (AWS scale-in, scale-out and deployment strategies)

        \- **Spearheaded cloud cost optimization initiatives**, reducing monthly expenses by 10%

        \- **Architect of the IAC strategy** (Terraform, GitOps) enabling scalable and consistent deployments

        \- **Responsible for the platform security strategy**, focusing on audit logs and threat modeling

    - name: Cloud & DevOps Engineer
      company: Amadeus
      duration: September 2021 - August 2023
      content: |-
        Responsible for the app deployment strategy, Azure migration, and driving a team shift to develop reliable system-oriented tooling.

        \- **Spearheaded the Ansible project** and **Managed the migration from Tower to AWX**, cutting costs and enhancing automation flexibility.

        \- **Led the design and development of Deployment-as-Code solutions**, reducing deployment times and ensuring consistency.

        \- **Led a team-shift to develop reliable system-oriented tooling**, reducing toil and mainteance lead time.

        \- **Provided cloud architecture guidance during a major Azure migration**, reducing risks and ensuring best practices.

    - name: Project Leader & Solution Architect (Consultant)
      company: Primitivo
      duration: September 2022 - September 2023
      content: |-
        Architect and Project Manager for Hara on a CRM project intended for non-profits, leading a team of 3 developers.

        \-**Led product developmen**t by conducting business, marketing, and functional analysis to define the roadmap.

        \- **Established tech golden paths and built a dev-friendly platform** accelerating TTM while ensuring a secure and reliable solution.

        \- **Mentored junior developers on software engineering principles** (DDD, TDD, SOLID, CI/CD), which elevated the overall quality of backend services.

        \- **Designed a cost-effective and reliable AWS infrastructure** using React, Node.js, MongoDB, Docker, and Kubernetes.

    - name: "Solution Architect (Web, Mobile & Ops Consultant)"
      company: "Primitivo"
      duration: August 2021 - March 2022
      content: |-
        Responsible for both Dev & Ops strategy to improve products’ (web & mobile) reliability in terms of availability, costs and maintainability.

        \- **Improved performance and maintainability** of a legacy Ruby on Rails app with TDD and Hexagonal Architecture.

        \- **Led the migration** from native Android & iOS apps to a unified Flutter codebase, **speeding up releases**. 

        \- **Prototyped cloud deployment strategies** with automated CI/CD, improving deployments efficiency and reliability.

        \- **Modernized infrastructure management** using Ansible, Terraform, and Packer for better consistency.

    # experience item loop
    - name : "Co-Founder & CTO"
      company : "Primitivo"
      duration : "2019-2021"
      content : |-
        Project manager & FullStack developer on various application projects, targeting students and bars in Strasbourg.

        \- **Led the products development with a tailored methodology**, and a roadmap aligned with customer needs, **that allowed us to ship 3 products into beta phase in less than 6 months**.

        \- **Actively participated in software design and implementation decisions** to ensure code’s approachability and fasten releases lifecycle.

        \- **Designed and maintained the developer platform** to allow to safely develop, test and ship features.

        \- **Designed a cost optimized AWS architecture** while taking into account scale-in to ensure the best reliability at the lowest cost.

    - name : "R&D Engineer"
      company : "Divalto"
      duration : "2018-2021"
      content : |-
        \- **Design and implementation of cutting-edge features** on a legacy ERP project
        
        \- **Work on synergies** between the ERP and external payment services (PayPal, PayZen, Mollie, etc)
        
        \- **Architecture, design and implementation** of a complete solution involving an Outlook add-in that allows to to interact with the ERP remotely

        \- **Configuration and development** (from scratch) of a complete Jennkins CI/CD (Cloud + onPremise)


########################### Studies ##############################
studies:
  enable : true
  title : "STUDIES"
  experience_list:
    # experience item loop
    - name : "Software and System Engineer diploma"
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
My name is Thomas Martin, and I'm a 27 years old French CS engineer with 5+ years of experience working on diverse projects (Web, Mobile, System, Cloud, etc). 

I am dedicated to providing you with specialized expertise in areas such as deployment strategy, release management, and optimizing your infrastructure's ability to adapt cost-effectively to current and future demands.

Passionate about **Cloud**, **Solutions Architecture**, **Web & Mobile dev**, **DevOps philosophy**, **tech watch** and **music**.

I'm also [![AZ-900 Certified](https://img.shields.io/badge/-AZ%20900%20Certified-blue?style=for-the-badge&logo=microsoft-azure)](https://www.credly.com/badges/a0b37337-5e0d-4074-a4c7-36ace2b3b915) and [![CKA Certified](https://img.shields.io/badge/-CKA%20Certified-lightblue?style=for-the-badge&logo=kubernetes)](https://www.credly.com/badges/799e4d84-183a-482c-8f8a-5c9068c41d4d/public_url)
