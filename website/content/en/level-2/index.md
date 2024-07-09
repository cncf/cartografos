---
title: Level 2 - Operate
description: The cloud native foundation is established and you are moving to production.
---

## <i class="fas fa-building"></i> Business Outcomes

At level two, you’ve experimented and made the decision to continue on the cloud native journey. Here you want to identify the projects that will uniquely benefit from cloud native. The business and technology needs to align on the project/service/application that makes the most sense to move. The decision could be focused on “where are we hurting the most” either internally or externally. While it may be easy to look at external “product or service” spend time considering internal requirements first.

Part of the decision making process should be based on seeing a return on investment (ROI). You should be moving an application that can serve as your speed boat.

> *Speed boat: transform to the cloud steadily and incrementally using speed boats to accelerate adoption and achieve extreme agility.*

Moving business essential applications (i.e. production workloads) will come with trade offs so selection is key. If you choose application A for example, you may need to worry about cloud costs. If you choose application B, you’ll need to worry about compliance audits. Ensure that the decision of what applications to move first considers key non-functional requirements such as capacity, backup, DR, performance (availability) as well as any governance topics such as compliance (and audits, including relevant logging), and risks such as that to reputation through downtime or security compromise.

Whatever application is selected will force the technology team to set standards and innovate for new ways of working. The technology team will design and establish new patterns based on the business goals. The project(s) that are moved first will help establish new policy, technology, process and people changes. Be aware that the first application may require prerequisites to be implemented to fulfill specific obligations. For example, you may need to extend your current concept for identity and access management to cater for public cloud use cases. Be prepared for a cascade of activities to deliver the minimally acceptable prerequisites to get your first applications into production.

*“Organizations must develop meaningful processes for sharing information and results between technology and business units, which might mean seeking out new talent with technical expertise and passion for sharing information.”* [CTO Summit](https://www.cncf.io/reports/cto-summit-na-2022/)

Measurement is key as we move through business outcomes. Each KPI and OKR must map to the overall business goal. It must be documented in a language that the business can understand.

Before moving to level three - scale - you must demonstrate business value. Lots of organizations get stuck at level two because they cannot demonstrate how the technology has helped achieve the goal. Going through this goal mapping exercise as early as possible is vital to your cloud native journey.

### Cost

When selecting what you are moving first, you must consider how you will deal with changes in cost. You will no longer be buying server and network hardware and software directly, but instead effectively leasing or paying as you go for capacity. While this brings with it flexibility, it will also require some work with cloud providers to get discounts. Ensure your technology team is in lock-step with finance to plan accordingly. The business should continuously ask for ways of optimizing infrastructure to save money and/or for evidence as to why more or less capacity is needed.  Cost control really does become everyone’s responsibility as real money exits the organization on a regular basis.

## <i class="fas fa-users"></i> People

### People Overview

Individuals are actively invested in training and skills. The outcome is that small pockets of SMEs and expertise are appearing. DevOps has started to appear with inclusion of cloud skill engineers and developer groups offering platform skills. Cloud Native efforts are also owned by members of leadership.

### Organizational Change

Organizational change is happening. You will define project teams, create agile project groups and have quick feedback/testing loops.

### Teams and Decentralization

We are starting to formalize central services and responsibilities, including the consolidation of tooling, as well as the culling or evaporation of non-cloud native tooling.

### Security

Your team needs to focus on who is responsible for Kubernetes cluster security and how it will be managed. That will require the inclusion of the security team.

### Developer Agility

The team is comfortable with technically challenging problems and how cloud native can help. There is an organizational commitment to decentralisation and automated testing of builds, with automated deployments to some environments.

### Upskilling Developers

Your wider development team is able to operate the fundamentals of Kubernetes including:
- Connecting an operator to the Kubernetes API
- Become comfortable with Kubectl commands
- Understanding how to list and view resources
- Performing basic actions (mechanical actions with limited understanding of how it works)

### CNCF Certifications

Organizations may wish to consider the CKA and CKAD exams around level 2 and 3.

#### Certified Kubernetes Administrator (CKA)

This program provides assurance that CKAs have the skills, knowledge, and competency to perform the responsibilities of Kubernetes administrators.

#### Certified Kubernetes Application Developer (CKAD)

This exam certifies that users can design, build, configure, and expose cloud native applications for Kubernetes.

## <i class="fas fa-cogs"></i> Process

### Process Overview

You’ll focus on production promotion of basic applications. This includes being well established with Git and CI. You are also instituting structured build and deployment processes that exhibit the qualities of a cloud and container native CI/CD system.

### CI/CD

For your application, you will institute structured build and deployment processes that exhibit the qualities of a cloud and container native CI/CD system.

### Change Control

Here you develop a fundamental understanding of the workflow from source control management (scm) to deployment and have access to merge/tag commits in scm to trigger deployments.

### Security

Build security into your CI process including container scanning and configuration scanning.

### Audit and Logs

Spend time defining log aggregation.


## <i class="fas fa-edit"></i> Policy

### Policy Overview
As your services approach production, you have initial policies agreed as standard and these are mostly documented.

### Policy Creation

Define initial resource metrics and start collecting data.

### Compliance

Initial auditing, carried out manually or through simple scripts.

## <i class="fas fa-server"></i> Technology

### Technology Overview

This marks your first step into production. You’ve worked hard to build your foundation in Level 1, and now you are moving to production. You might have started with something relatively small and simple, but this leap to production has certainly required you to address some significant steps. You’ll probably have had to incorporate monitoring and observability into your workloads. You’ll have brought key observability tooling in and started monitoring your clusters for standard metrics such as RAM, CPU etc. While you might be starting to evaluate application tracing, don’t worry about it too much if you have started to gather core metrics. Your focus here is on getting an application running in production and having enough platform resource, observability and operational capability to support it within your organization.

### Infrastructure

Because production is your goal, you’ve built Kubernetes clusters for production with a focus on reliability and security.

### Container and Runtime Management

You’re working in production now. You will experiment with tooling to augment the basics in production to help with security, policy management, workload misconfigurations, resource requests and limits. Key security practices for container hygiene are being incorporated.

### Application Patterns and Refactoring

You're in production, with your first APIs exposed. Consider developing a “microservices first” framework particularly if your first choice is always a microservices approach. If not, consider moving applications suitable for lift and shift or don't migrate the app until later.

### Application Release and Operations

For your initial steps into production, you’ll be using CI or release tooling, kubectl and kustomize to potentially deploy your first smaller applications. It’s really important by now that you develop key skills in Kubernetes configuration.

### Security and Policy

Ensure that your development and operations groups are following good practice with containers, secrets and security. Because you are in production, you will want to ensure that you have encryption as well and authentication and authorization addressed.

### Testing and Issue Detection

Now that you are in production, you’ll be experimenting with tooling to help with security, policy management, workload misconfigurations, resource requests, limits and observability, in your staging or development environment.
