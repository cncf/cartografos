---
title: Level 4 - 改进
description: 您正在改进跨环境的安全、策略和治理。
---

## <i class="fas fa-users"></i> 人员

### 人员概述

随着您的改进，您正在将能力转移给开发团队，让他们能自助服务。领导层将全力支持。

### 组织变革

云已成为所有服务的默认基础架构。现在业务部门要求的是DevSecOps（开发、安全和运维）服务，而不是要求传统的服务器。

### 团队和分权化

随着平台的日趋成熟，您可以真正开始分权化的过程。您可以致力于开发一个自助门户，将您组织的策略和流程融入其中，以便开发人员能够拥有服务所有权。

### 安全性

到了这个层级，安全性已经涉及到设计和部署，您将在云原生环境中加强安全。您的组织致力于安全，对组织内外的政策和法规有全面的理解。

### 开发者敏捷性

反馈从应用程序指标延伸到平台和非功能需求，同时将价值流映射到技术实现上。开发人员能够快速测试具有许多未知因素的复杂情况，云和应用程序风险很容易且快速地被识别和修复。


### 提升开发者技能

开发者更加老练，Kubernetes被多个不同业务领域的多个团队广泛采用，正在发展并积极分享一套包括集成和发布流程的知识体系。开发人员和集群所有者正在积极根据其特定的业务和技术需求扩展Kubernetes的应用。

### CNCF Certifications

Organizations may wish to consider the CKS around level 4.

#### Certified Kubernetes Security Specialist (CKS)
This program provides assurance that a CKS has the skills, knowledge, and competence on a broad range of best practices for securing container-based applications and Kubernetes platforms during build, deployment and runtime. CKA certification is required to sit for this exam.

## <i class="fas fa-cogs"></i> Process

### Process Overview

The governance model in place will support DevSecOps. You have guardrails in place to support agile software development. You will establish an application services library. You will also set policy around container usage for example auto-scaling policies or HPC.

### CI/CD

You will measure your release velocity and cadence to make improvements.

### Change Control

You have continuous delivery, but no continuous deployment to production - you still have a gate to production that requires operator approval.

### Security

Ensure security remediation is automated and/or identified automatically with remediation advice.

### Audit and Logs

Audit and alerts become mainstream and are made mandatory across applications.

## <i class="fas fa-edit"></i> Policy

### Policy Overview

You now have defined SLAs around policies and remediation.

### Policy Creation

Customize policies based on your business needs and minimize exceptions.

### Compliance

Expansion of policy tooling to include applications such as traffic proxies, service mesh, message buses and Linux. This will broaden the scope of managed policies, but it will also help in having them under control by way of declarative configurations.

## <i class="fas fa-server"></i> Technology

### Technology Overview

You’ve got full control over your environment, and you’ve built your confidence, with rapid adoption of cloud native patterns for new applications and platforms. You’ve also gained organizational commitment to cloud native and this is adding to your momentum. You’re starting to feel like you’ve “crossed the chasm.”

### Infrastructure

Kubernetes and its API has become extremely familiar to you. With your infrastructure and IaC tooling, you’ll likely find yourself investigating ClusterAPI and using that for deploying and managing the lifecycle of your clusters. As you also look to further refine control of your platforms, you’ll work to implement policy for your infrastructure control plane and other infrastructure controllers.

### Container and Runtime Management

With your sources of information you've gained from Level 3, your goal is to further integrate your data sources and gain visibility along with alerting. This closes the feedback loop on runtime and operations and allows you to respond quickly to unplanned events.

### Application Patterns and Refactoring

Microservices have become the preferred pattern for applications. The use of APIs is expanding within the organization, and other internal systems may be exposed and consumed, and they are available for general consumption, open across the organization via a service mesh. The organization becomes data-centric and API-centric, and data can be more easily consumed.

### Application Release and Operations

Not only are you using GitOps operators for rapid deployment, but you may also be using them for development and test purposes. You’ll be expecting most of your software to be packaged with Helm with the feedback loop being closed as quickly as possible to reduce configuration drift.

### Security and Policy

Apply your policy against production in case you haven’t already. You’ll continue to tune your policies in production.

### Testing and Issue Detection

As your environment becomes more complex in production, some issue remediation may require adjusting your policy-as-code or components of your Infrastructure as Code, as well as your application. Issues may relate to more than one application so you will aggregate across applications to determine trends. These may relate to bugs such as memory leaks, as well as security or policy issues. Your remediation may be to fix them at source, ideally as ‘far left’ as possible, or otherwise building automation capable of fixing them when they occur, and tuning it over time.

## <i class="fas fa-building"></i> Business Outcomes

Level 4 is focused on improvements around security, policy and governance across your environment. The team can focus more of their time on your business instead of maintaining Kubernetes. Level 4 is also the next level where clients and customers plateau. And most customers can stay at this level as they further mature.

Your team has cloud native confidence and now it’s time to take that knowledge and apply it more thoroughly to your business goals.You have continued to measure yourself against established KPIs in Level 1 and provided those to the business. You’ll have alignment on goals because you can demonstrate outcomes. The business should expect to see:

- Established protocols and procedures
- Policy enforcement of compliance standards
- Comparison of cloud native apps vs. non-cloud native
- The business should expect more reporting in this phase. Reporting should cover compliance, security, performance and cost. These should be easily aligned to the business goals established in Level 1.

At this point, you may start to migrate your other applications and have a better understanding of what you want to achieve and where you will see value during each level of maturity.
