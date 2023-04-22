---
title: "Level 1 - 构建"
description: >
  您已经完成了一个基础的云原生实现，并处于预生产阶段。
---

## <i class="fas fa-users"></i> 人员

### 人员概览

云原生框架正在成为您实现业务和技术目标的驱动力。对您和您的团队来讲，这项技术还很新，但是已经具备一些基本的技术知识和一些现有的资质。您的业务领导已经了解云原生的好处。

### 组织变革

在您进行转型时，您将有限的组织支持，可能处于概念验证（POC）阶段或仅专注于一个应用程序。

### 团队和分权化

团队正在探索云原生工具，主要是Kubernetes。然而，这并不仅仅是为了探索，而是为了达到生产目标。所有的工作通常都是在一个正式的MVP计划中进行。

### 安全

实施云原生的人员需要重视安全问题。将使用默认安全设置，并在预生产中发挥作用。您将花费时间确定开放源代码的安全态势，并对预生产环境进行安全性POC (概念验证)，以便开发、运维和安全人员了解云原生工作负载所需的条件。

### 开发者敏捷性

您的组织致力于分权化，并将设置“teams of teams”组织架构。这是对您的组织成员的一个基本要求。在不同的成熟度水平上，人们将实施自动化测试、指标和反馈工具。

开发人员可能已经了解敏捷宣言并采用了Scrum框架，但并未必然包括运维。开发人员可能会尝试自行解决外部依赖关系，从而减缓反馈速度，并导致每个迭代中的功能不完整。


### 提升开发人员的技能

您的团队成熟度将包括提升开发团队的技能。

您的应用团队将接受12-factor-app、微服务和云原生模式的培训。您还需要拥有对云原生概念和工具（如kubectl）非常熟悉的开发人员来启动您的开发团队。

### CNCF 认证

云原生计算基金会（CNCF）是许多增长最快的开源项目（包括Kubernetes、Prometheus和Envoy）的独立于供应商的中心。

为了构建云原生基础设施的可持续生态系统，您投资于团队的CNCF认证至关重要。您很可能不会在Level 1阶段获得所有认证。


## <i class="fas fa-cogs"></i> 流程

### 流程概述  

您将会描述应用程序要求，包括功能性（应用程序特征和代码）和非功能性要求，如性能、容量和可用性，并定义组织如何扩展。反馈将是手动的，例如通过Slack、电子邮件和电话，您还将手动进行修正。您将开始通过定义Git工作流程来实现可重复性，定期根据应用平台和技术生命周期进行更新，特别是安全更新，因为易受攻击的系统会带来特定的风险。您很可能会按需手动应用这些更新，或使用发行版中包含的更新系统。


### CI/CD 

在您的云原生转型过程中，CI/CD的采用至关重要。CI/CD可以帮助您基于现代软件开发实践构建、测试和部署应用程序。随着时间的推移，您的CI/CD流程将会不断成熟。

如果您正在使用CI/CD，您需要采用现有的最佳实践的基础上将其转换到您的云原生环境。

### Change Control

Change control will need to be implemented to control your deployments.
You have no change control process in place. Instead changes are performed based on ad-hoc requests.

### Security

Incorporating security tooling and practices into your cloud native environment, whether through a practice or a process, as early as possible is crucial to keeping your cloud native environment secure. We often use the term ‘shift left’ to refer to bringing a practice, whether relating to testing or security, into a process as early as possible. Security is covered in all sections of the Cloud Native Maturity Model and each section with People, Process, Policy and Technology can be combined to support the security team as they seek to mature the organization’s cloud native security.

Take action: your security journey starts here. Consider security in all aspects of implementation and make it a first class citizen.
 
### Audit and Logs

Your process will include logging and auditing. This can be based on internal requirements or support your compliance mandates.

Manual log scraping is likely ad-hoc and you may not have a central logging point or SIEM.

## <i class="fas fa-edit"></i> Policy

### Policy Overview

We recognize policy adoption is a gradient. Every organization has a different risk appetite. Use this document as a guide to how you can define and enforce policy. By level 5, you will have achieved full policy maturity, however your mileage may vary.

You will have a limited set of documented policies in place to support services you're building in the cloud.

### Policy Creation

You will need to translate your organization’s policies and compliance requirements to your cloud native environment.

Spend time understanding your application's functional and architectural requirements.

### Compliance

You will need policies in place to achieve compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve.

Spend time understanding your compliance requirements: CIS, NIST, PCI for example. Design SLOs and priorities for compliance. This will take time and may not be a pre-production requirement, but will increase as you move to production.

## <i class="fas fa-server"></i> Technology

### Technology Overview

You’ll have your initial experimentation and adoption of Kubernetes. You’ll start with relatively basic tools and technology. You’ll assess your existing toolset to see how they fit within the new landscape (what plays well with cloud native, and what doesn’t?). You’ll have limited automation, but don’t worry, it’s coming! Your focus is on getting the baseline technology implemented, and you won’t be in production yet.

### Infrastructure

You are building your cloud infrastructure either on-prem or off. It will pay dividends to consider early your supporting technology such as your network, firewalls and IAM, access controls and policies (and if you need to change them). Many topics will come out of your initial experimentation with Kubernetes, so ensure you keep track of these - they are the ‘breadcrumbs’ you will follow as you move towards cloud native. This will include RBAC policies, load balancer and/or ingress configuration, cluster dashboards, privileged access (or lack thereof!) and container logging. Your aim is to move away from ‘pets’ to ‘livestock’ so you invest in declarative solutions for your Infrastructure as a Service with Infrastructure as Code (IaC) tooling. If you do not have a consolidated DevOps practice at this level, bring your future operations team in to build familiarity.

### Container and Runtime Management

Initially you’ll want to focus on just building containers. One of your first steps will be to add container builds to your CI for your application. You’ll also want to adopt a container registry for your images and you’ll need to consider versioning and tagging so that you can ensure you know exactly what code is in use.

### Application Patterns and Refactoring

Start with a canonical microservice application if you can and confirm that it runs and that people are familiar with it. Attempt to start with a microservice application on your cloud native journey if you can. You can try an existing or monolithic application if this makes sense, as this will flush out tooling and dependencies you'll have for your journey to cloud native, such as kubectl, network connectivity and other topics.

Your business needs to review microservice patterns and architecture and look to understand the specifics for your applications. Non-functional requirements such as latency, resilience, scaling and third party tooling should definitely be considered. If you're transforming a monolith, this may impose significant redesign on the application as existing needs may not have the technical resources available. Consider your state management, as refactoring a monolith may require effort here. Try to ensure that the knowledge stays with the code, so make sure an existing developer familiar with the code participates in its migration to the cloud. Minimize divergence between cloud and your existing estate. This exercise will ensure all understand that it's a commitment to move to cloud native.

### Application Release and Operations

Managing a cluster with Infrastructure as Code (IaC) is different to managing application release and deployment, however many of the same techniques and tools will be common to both.
When starting with Kubernetes, it is important that you start out with as much hands-on experience as possible. Initially you’ll be doing ad-hoc deployments with kubectl and kustomize.

### Security and Policy

Start building your secured CI-CD pipeline if you don’t have one already and don’t forget that what you are doing today with VMs will end up quite different in the future.

### Testing and Issue Detection

When just starting out, much of your testing will be conducted manually on your business application that you’ve identified as your initial production candidate. With Kubernetes you’ll be focussing on your general network connectivity, and ensuring you’re able to deploy your applications. You will have smoke tests, and UAT testing.

## <i class="fas fa-building"></i> Business Outcomes

Level 1 of the Cloud Native Maturity Model is where your team has a baseline implementation in place and you are in pre-production. Here you will have completed a successful POC. Based on the POC, you should have initial findings on how cloud native will help improve your app. In a dev environment, you could, for example, have seen that:
- An app is using less resources (cost savings / more efficient use)
- A new feature shipped faster (faster time to market and thus increased revenue)
- There was no downtime (improved reliability for customers)
- Improved business continuity thanks to resilient cloud architectures

These are just examples, they are not a guarantee based on your environment as results may vary.

In this phase, you will determine how you’ll measure (your initial KPIs) the success of your cloud native journey; and just as important, how you will demonstrate it to stakeholders. This is a major outcome of Level 1 as the entire success of the journey should be mapped to this measurement. Remember it won't be immediate on day 1. Some quantitative and qualitative example KPIs may include:
- Reduced spend on app infrastructure by 25% by optimizing for cost
- Dev cost lowered by 10%
- Reduced team focus on app infrastructure by 15% by automating as much as possible
- Increased security for the application by automating CVE identification in containers
- Improve compliance as you can restrict and track access to the application; demonstrate compliance with SOC 2
- Accelerated development life cycles as you implement CI/CD pipelines shipping 10% more features per quarter
- Migrate plan - this will vary depending on your organization, but you should have a migration plan in place. Whether that’s to migrate one application first, or several, you should have this established.
- Improved customer experience measured by increased performance scores
- Elimination of information silos: departments no longer isolated; unique, integrated ecosystem in place.
- Alignment of business and IT goals: everyone is involved and aware, so that resources are better addressed to meet those goals efficiently.
- Increased internal communication: cross-pollination offers new perspectives with shared knowledge.

In this phase, it’s important that the business outcomes are examined and explained to business stakeholders. It should be a discussion with engineering leadership, the application owner (finance, marketing, etc), the CEO, and even the board. Without these discussions and alignment, maturing to the next phases will come with little appreciation and possibly even skepticism.
