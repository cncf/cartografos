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

### 变更控制

需要实施变更控制以调控您的部署。

您目前没有变更控制流程，而是根据临时请求执行更改。

### 安全
 
将安全工具和实践尽早地纳入到您的云原生环境中，无论是通过实践还是流程，对于保持您的云原生环境的安全至关重要。我们通常使用“shif left - 向左移动”这个术语，来指在流程的尽早阶段引入测试或安全等实践。安全涵盖了云原生成熟度模型的所有部分，每个部分包括人员、流程、政策和技术，都可以结合起来支持安全团队，使其在成熟组织的云原生安全方面取得进展。

采取行动：您的安全之旅从这里开始。在所有实施方面考虑安全，并使其成为一等公民。
 
### 审计和日志

你的流程将包括日志记录和审计。这可以基于内部要求或支持你的合规性要求。

手动的日志收集可能是临时的，你可能没有集中的日志记录点或安全信息和事件管理系统（SIEM）。

## <i class="fas fa-edit"></i> 策略

### 策略概述

我们意识到策略采纳是一个渐进的过程。每个组织的风险承受能力都不同。使用本文档作为指南，了解如何定义和执行策略。到达级别5，您将实现完全的策略成熟度，但实际情况可能有所不同。

您将制定有限的记录在案策略以支持您在云中构建的服务。

### 策略创建

你需要将你的组织策略和合规要求转化为云原生环境中的规则。

花时间了解你的应用程序的功能和架构要求。

### 合规性


您需要制定策略以实现合规性，特别是在高度监管的行业。对于合规性，您将实现的内容是渐进的。

花时间了解您的合规性要求：如CIS，NIST，PCI等。为合规性设计创建服务等级目标(SLO)和优先级。这需要时间，可能不是预生产的要求，但随着您进入生产，其重要性会增加。

、

## <i class="fas fa-server"></i> 技术

### 技术概述

您将开始测试并采用Kubernetes。您将着手使用相对基础的工具和技术。您将评估现有的工具集，看看它们在新的环境中适用程度（哪些工具能够很好地与云原生相容，哪些不能？）。您将实现有限的自动化，但不用担心，它即将到来！您的重点是实现基础技术，但还没有进入生产环境。

### 基础设施

您正在构建云基础架构，无论是在本地还是在云上。想得到好的效果，尽早考虑支持技术，如网络、防火墙、身分識別和存取管理 (IAM)、 访问控制以及策略（以及您是否需要更改它们）。在与 Kubernetes 的初始实验中，将涉及许多主题，因此请确保跟踪这些主题，它们是您朝着云原生发展的“面包屑”。这将包括 基于角色的访问权限控制(RBAC)策略、负载均衡器和/或入口配置、集群仪表板、特权访问（或缺乏访问）和容器日志记录。您的目标是把基础设施从当“宠物”变成当“家畜”，因此要使用基础设施即服务的声明性解决方案，并使用基础设施即代码（IaC）工具。如果在这个层面上您没有一个统一的 DevOps 实践，请让未来的运营团队参与并熟悉这个过程。

### 容器和运行时管理

初始阶段，你需要专注于构建容器。你的第一步将是将容器构建添加到应用程序的持续集成(CI)中。你还需要采用容器注册表来存储你的镜像，并需要考虑版本控制和贴标签，以确保你知道正在使用的代码的准确信息。


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
