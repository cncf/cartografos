---
title: Level 2 - 运营
description: 云原生基础已经建立，您正在转向生产。
---

## <i class="fas fa-users"></i> 人员

### 人员概述

个人积极投入培训和提高技能。结果是出现了少数精通某一领域或主题的专家（SME）和专业知识团队。DevOps已经开始出现，包括云技术工程师和开发人员团队提供平台技能。云原生的努力也由组织领导成员主导。

### 组织变革

组织变革正在发生。您将确定项目团队，建立敏捷项目组，并拥有快速反馈/测试回路。

### 团队和去中心化

我们开始正式集中服务和责任，包括工具的整合，以及淘汰或消除非云原生工具。

### 安全

您的团队需要关注谁负责Kubernetes集群的安全以及如何管理它。这将需要让安全团队参与其中。

### 开发人员敏捷性

团队能自如对待技术上具有挑战性的问题以及利用云原生帮助解决这些问题。这是在组织架构上致力于在某些环境里构建去中心化的自动化测试，自动部署。

### 开发人员技能提升

您更广泛的开发团队能够熟悉Kubernetes基本操作，包括：

- 将operator连接到Kubernetes API
- 熟悉Kubectl命令
- 了解如何列出和查看资源
- 执行基本操作（机械操作，对其工作原理的理解有限）

### CNCF 认证

组织可能希望在 2 级和 3 级左右考虑 CKA 和 CKAD 认证考试。

#### 认证 Kubernetes 管理员 (CKA)

该计划确保 CKAs 具备执行 Kubernetes 管理员职责所需的技能、知识和能力。

#### 认证 Kubernetes 应用开发者 (CKAD)

该考试证明用户可以为 Kubernetes 设计、构建、配置和公开云原生应用程序。


## <i class="fas fa-cogs"></i> 流程

### 流程概述

您将专注于基本应用程序的生产推广。这包括熟练掌握 Git 和 CI。您还将制定结构化的构建和部署流程，展示云和容器原生 CI/CD 系统的特点。

### CI/CD（持续集成/持续交付）

对于您的应用程序，您将制定结构化的构建和部署流程，展示云和容器原生 CI/CD 系统的特点。

### 变更控制

在这里，您将建立对从源代码管理（scm）到部署的工作流程的基本知识，并可以访问合并/标记提交以触发部署。

### 安全

将安全性纳入您的CI过程中，包括容器扫描和配置扫描。

### 审计和日志

花时间定义日志聚合

## <i class="fas fa-edit"></i> 策略

### 策略概述

当您的服务逐渐进入生产阶段时，您需要制定初始政策作为标准，并且大多数这些政策都需要有文件记录。

### 策略创建

定义初始资源指标并开始收集数据。

### 合规性

初始审计，可以通过手动或简单脚本进行。

## <i class="fas fa-server"></i> 技术

### 技术概述

这标志着您迈入生产阶段的第一步。您在 Level 1 中努力构建了基础，现在正在进入生产阶段。您可能从相对较小和简单的东西开始，但是这次跃升到生产阶段肯定需要您解决一些重要的步骤。您可能已经将监控和可观察性纳入您的工作负载中。您将引入关键的可观察性工具，并开始监控集群的标准指标，例如RAM、CPU等。虽然您可能刚开始评估应用程序跟踪，但是如果您已经开始收集核心指标，不要过于担心。您的重点是使应用程序在生产环境中运行，并拥有足够的平台资源、可观察性和运营能力来支持它在您的组织内运行。


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

## <i class="fas fa-building"></i> Business Outcomes

Cloud native is now established and your technologists are moving to production. While the technical outcome of Level 2 is a fully functional application or group of applications migrated to cloud native tools and practices, the business outcomes are the ability to evaluate the benefits of the migrations. This is also the level that most customers/corporations get to and plateau. This is when a cloud native maturity model shows its true value.

With your established KPIs from Level 1, you will measure success and communicate this to stakeholders.

In the operation phase, you will be focused on moving to production. You’ll have established standards around technology, your people will be operating it and implementing policy and process. Your business outcome will be around production migration. The business leadership of your organization will want to understand what applications are being moved and why. Be able to clearly communicate the plans to your business leaders. Repeatable patterns will also emerge as teams operate in Level 2. These will be applied to your business outcomes so that benefits you see in one migrated application can be applied to another without as much as a heavy lift. These patterns will help streamline operations across your dev, sec and ops teams.

Your KPIs can also include your return on investment ROI, but know that in Level 2, your ROI will be lower than when you reach Level 5. This is because you are investing a lot in acquiring tools, establishing the right team and skill set, whereas in Level 5 you are optimizing.
