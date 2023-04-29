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

您正在围绕您的 CI/CD 流程实施卓越中心。

### 变更控制

您的代码质量正在提高，使用自动化工具进行衡量，您经常看到 CI 和测试成功。

### 安全

实施自动连续扫描，以标记配置错误或安全问题。

### 审计和日志

开始审计并实施初始警报。过滤噪音。

## <i class="fas fa-edit"></i> 策略

### 策略概述

您将实施策略即代码，并将其构建到您的 CI 流水线中。

### 策略创建

根据围绕安全性、效率和可靠性精细化的度量创建策略。

### 合规性

在 Kubernetes 上通过自动化手段进行策略合规性和审计。这可能包括策略即代码的初始开发。

## <i class="fas fa-server"></i> 技术

### 技术概述

在这里，您开始扩展规模。您的工具套件更加标准化。您正在安装发布工具、密钥管理和策略工具。您还开始在整个组织中获得一定程度的认可，这有助于推动您前进步。这是您将运行最多工具的地方，因为您将处于评估、实施和生产运行的繁忙阶段。

### 基础架构

基于建立对云基础架构的信心，你需要获得对基础架构正在执行的操作的可见性。你的重点将是发展监控、警报和资源使用能力。一个重要的考虑因素是，在以前，你可能考虑了与机器特定属性相关的指标，如 CPU、RAM 等，但现在你也需要考虑集群资源指标。此外，你将在组件发生故障时进行替换，而不是在生产环境中花费时间修复已出现的问题。这是建立在 Level 2 基础上的。此外，你还可以像管理软件一样，使用 Kubernetes 管理基础架构。

、
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

