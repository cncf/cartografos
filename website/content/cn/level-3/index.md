---
title: Level 3 - 规模
description: 您的能力正在增长，您正在为扩展定义流程。
---

## <i class="fas fa-users"></i> 人员

### 人员总览 

团队的能力正在增长，并且Dev、Ops和安全方面都有承诺。您正在围绕云原生卓越中心正式形成专业知识。云原生成为战略的一等公民。

### 组织变革

随着您的团队成员能力的提升，组织结构现在已经可以支持最佳实践。您将拥有正式的责任分工。常用于这种结构的常见模式通常采用敏捷和Scrum框架。

### 团队和分权化

您真正开始看到了高度的集中化，具有明确和明确的责任分工。然而，在这个过程中可能会出现速度下降和新瓶颈的情况。事情可能会开始变慢。

### 安全性

您的风险容承受成度将影响你关注云原生安全培训的程度，所以您在积极培养人员的技能。

### 开发人员的敏捷性

你的团队已经实现了所有环境的持续交付，包括复杂的发布和内置的合规性测试。运维团队现在已经整合到跨职能团队中，尽管个人可能并不一定能够执行所有职能。

### 提升开发者技能

实施可重复的故障排除循环，以便快速完成更改和迭代。

### CNCF 认证

组织可能希望在第二级和第三级左右考虑 CKA 和 CKAD 考试认证。

#### 认证 Kubernetes 管理员 (CKA)

该认证项目确保 CKAs 具备执行 Kubernetes 管理员职责所需的技能、知识和能力。

#### 认证 Kubernetes 应用程序开发人员 (CKAD)

该考试认证用户能够为 Kubernetes 设计、构建、配置和搬出云原生应用程序。

## <i class="fas fa-cogs"></i> 流程

### 流程概述

您将在整个组织中实施标准化，以改善载入过程，扩大您的云原生印记和认知度。您将创建一个反馈循环。您将投资于可重复性。您是否已经为所有人提供了可用的工具？您是否有 Git 服务？您是否实施了工作空间协作以节省时间、劳动力或避免重复？最后，您的资源使用量测量过程是什么？在第三级，您应该测量容器使用量、CPU 和内存（运行时间和在线运行时间）。与软件发布相关的自动化和流程也将扩展到平台。生命周期操作（例如升级和修补程序，特别是 CVE 和关键更新）将受益于进一步的自动化和基础架构即代码技术的引入。


### CI/CD

You are implementing a center of excellence around your CI/CD process.

### Change Control

Your code quality is improving as measured with automated tooling and you are seeing CI and test success frequently.

### Security

Implement automatic continuous scanning to flag misconfigurations or security issues.

### Audit and Logs

Start to audit and implement initial alerts. Filter noise.

## <i class="fas fa-edit"></i> Policy

### Policy Overview

You will implement policy-as-code and build this into your CI pipeline.

### Policy Creation

Create policies based on metrics refined around security, efficiency and reliability.

### Compliance

Policy compliance and auditing carried out through automated means on Kubernetes. This will likely include initial development of policy-as-code.

## <i class="fas fa-server"></i> Technology

### Technology Overview

Here you start to scale. Your suite of tools is more standardized. You're getting your release tooling, secrets management and policy tooling in place. You’re also starting to get a level of buy-in across your organization, which is helping to propel you forward. This is where you will be running the largest number of tools as you will be in the thick of evaluating, implementing, and running in production.

### Infrastructure

As part of building confidence in your cloud infrastructure, you need to gain visibility into what your infrastructure is doing. Developing your monitoring, alerting and resource usage capabilities is going to be your focus. An important consideration here is that where previously you may have considered machine-specific properties such as CPU, RAM etc, you’ll also want to factor in cluster resource metrics also. Additionally, you’ll replace components when they fail rather than spending time remediating issues in production. This builds on Level 2. Furthermore, you may also look to manage infrastructure with Kubernetes like you would software.

### Container and Runtime Management

Whereas in Level 2 you’ve been experimenting, in Level 3, as you increase your workload, and as you scale, you need consistent tooling across clusters to gain continuous visibility into your Kubernetes clusters. This should include automatic scanning and having runtime observability of what is occurring within your containers and your cluster. CNCF projects are good options here. You will have alerting and dashboards in place.

### Application Patterns and Refactoring

Culturally, your organization has started to think about services rather than “servers”. Microservices are embraced within the organization and are now used by default where appropriate.

### Application Release and Operations

Because consistency is important, you may be starting to write Helm Charts for your application releases. You may also be starting to take your first steps into GitOps with Flux and Argo, introducing controllers to manage your release and operations.

### Security and Policy

It’s now time to step up and automate your deployment guardrails and security best practices with policy as code. Determine your strategy for enforcement. Begin adopting third party benchmarks and standards where relevant. Consider also adopting anomaly and threat detection technologies.

### Testing and Issue Detection

On the basis of your experiments in the previous level, you’ll be implementing this in production, and including good alerting and good dashboards, building out your observability capabilities.

## <i class="fas fa-building"></i> Business Outcomes

In Level 3, your competency is growing and you are scaling. Up to this point, your teams have been focusing on learning cloud native. In this stage, your business outcomes are dependent on your team’s experience. As the team builds confidence, their competency around security, efficiency and reliability grows and they will implement defined processes for scale. All of these will impact your services and applications as the team improves. Your business should start to notice operations are more scalable and if not you will need to improve lines of communication to demonstrate this scale, or review the actual scaling results, so they can be optimized further.

You will have safeguarded your application or service from a single point of failure or disappointing performance in Level 3.

Monitoring is implemented. This will help the business get reports on what’s working and what isn't working. While the monitoring may be very specific, it will also provide insights into resource utilization to control costs and performance to ensure availability.

Finally, you should be observing the flexibility and scalability of cloud native by comparing old vs. new:

- Deploying a server takes minutes with Infrastructure as Code instead of days. Business translation: faster time to market.
- Monitoring for security attacks. Business translation: less risk, stolen data.
- Observability: Logging, metrics and tracing. Business translation: quicker responsiveness to changes in application behavior or business demand. Better customer experience and reduction in lost sales due to service degradation.
- Improved Reusability: containers and microservices make it easier to reuse components already available from previous projects. Business translation: 1. guarantee of brand image consistency and standardized functionalities throughout the multiple apps; 2. a lower learning curve for customers using those apps.

