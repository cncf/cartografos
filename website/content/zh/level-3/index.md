---
title: 级别 3 - 规模
description: 您的能力正在不断增强，并且您正在定义规模化流程。
---

## <i class="fas fa-building"></i> 业务成果

第三层，规模，是**“混乱的中间层”** 。您的组织——包括业务和技术——已经接受了云原生。您看到了业务目标的实现。您已经解决了大多数组织面临的共同挑战，了解了事情是如何发生的，不再把时间花在已经发现/创建/学习的东西上。你们还对人员、流程和技术进行了改革。您将拥有可重复的模式。

虽然这一切听起来都很不错，但这是一个混乱的中间环节，因为虽然人们对云原生技术已经驾轻就熟，但事情发展得更快，新的需求也在不断涌现。团队正在采用新技术来支持您的业务目标。

但随着规模的扩大，新的要求也随之而来。你需要新的工具来满足安全性、合规性和可用性要求。你可能会有多个团队使用不同的工具。工具会大量增加，其中一些来自现有或遗留的基础架构和系统，一些来自一级和二级，还有一些新工具，因为新工具的引入增加了最初选择的工具不一定具备的功能或能力。这也是系统蔓延最严重的时期。 此外，还可能出现效率严重低下的情况，例如，部署的平台尺寸不正确，从而进一步增加了成本。所有这些都需要加以解决，企业需要明白，随着规模的扩大，技术团队需要解决的问题也会变得复杂。

例如，在第三级，可能有多个日志系统在收集用于归档的审计事件--一个用于现有平台，一个用于新的云本地平台。这些系统最终将进行整合，并可能合并和归档重复数据。此时，您可能会对 "技术债务 "的概念有所了解。这是指为了实现新功能或提供新服务而采取的短期行为，但会导致未来的返工。无论一项任务是通过战略解决方案全面完成，还是通过需要返工的短期战术解决方案完成，都需要花费时间和人力，因此，请务必认识到，现在的短期修复需要有人在日后进行回访和整理。

无论如何，都不要中途放弃。虽然有些应用程序可能运行得很好，但并非所有应用程序都是如此。成功的应用程序需要用来展示可以实现的目标。继续推动这些应用向前发展，使其成为公司内部的 "灯塔"。小型企业可能会游过第三级，而拥有大量遗产和传统的大型企业可能会在这里停留数年。

虽然规模内有专门的人员部分，但在第三级，企业需要认识到团队必须如何发展。随着云原生扩展到几个项目、应用程序或服务之外，将有更多的人加入到新的工作方式中。企业应该预料到用户在接受云原生时会遇到一些阻力。这是企业需要预料到的一个过程，但也要尽早让用户参与进来，这样当你进入第三级时，团队才不会感到惊讶。应尽早在整个组织内开展培训，展示某些应用在实验阶段（第一级）和迁移阶段（第二级）的积极成果。不要让云原生被视为工作的障碍，也不要让抵触的用户成为采用的阻碍。

企业需要鼓励帮助员工学习技术、流程和政策，从而实现业务目标。企业需要保护领导者，即率先开展云原生运动的人员，同时鼓励其他人加入并成为专家。

### 成本

As you scale your cloud native infrastructure, you’ll now start to scale down your legacy system. This is where your costs will start to even out and/or reduce. The chart below shows how you would expect to see your costs change over time.

![cloud native vs legacy cost](/images/cloud-native-vs-legacy-cost.svg)

At this level you’ll also, particularly in the case of a migration to public cloud from traditional on-premise or co-located systems, see a change in the types of costs faced by the organization.  OPEX expenses will have increased, but CAPEX such as fixed assets and associated depreciation, as well as long term data center contracts, may be reduced or come to an end.  The financial benefits of a reduced on-premise footprint should be becoming apparent.

When cost issues occur in the ‘messy middle’ which are particularly urgent, for example a proliferation of Kubernetes clusters rather than a consolidation onto a fewer number of clusters through more advanced resource usage patterns, maintain a strategy of working to resolve the issue and consider relevant options, rather than abandoning the transition to cloud native. Your technical team will likely have a solution but they may need to invest time to realize gains. They will also be addressing this as part of level four.


## <i class="fas fa-users"></i> 人

### People Overview

The team’s competency is growing and there is commitment from Dev, Ops and security. You are formalizing expertise around a cloud native center of excellence. Cloud Native becomes a first-class citizen for strategy.

### Organizational Change

As your people’s competency grows, the organization structure is now in place to support best practices. You will have formalized responsibilities. A common pattern used for this structure often embraces agile and scrum.

### Teams and Decentralization

You’re really starting to see a high degree of centralisation, with clear and understood responsibilities. There may however be a decrease in velocity and chokepoints in the process. Things may start to slow down.

### Security

Your risk tolerance will impact at what level you are focused on cloud native security training so you are actively skilling people.

### Developer Agility

Your people have implemented continuous delivery for all environments, including for complex releases and with built-in compliance testing. The ops team is now integrated into cross-functional teams, though individuals may not necessarily be able to do all functions.

### Upskilling Developers

Implement a repeatable cycle of troubleshooting so changes and iterations are done quickly.

### CNCF Certifications

Organizations may wish to consider the CKA and CKAD exams around level 2 and 3.

#### Certified Kubernetes Administrator (CKA)

This program provides assurance that CKAs have the skills, knowledge, and competency to perform the responsibilities of Kubernetes administrators.

#### Certified Kubernetes Application Developer (CKAD)

This exam certifies that users can design, build, configure, and expose cloud native applications for Kubernetes.

## <i class="fas fa-cogs"></i> 流程

### Process Overview

You will implement standardization across the organization with the benefit of improving onboarding and expanding your cloud native footprint and awareness. You will create a feedback loop. You will invest in repeatability. Do you have the tools in place that are accessible to everyone? Do you have Git services? Have you implemented workspace collaboration to save time, labor or avoid duplication? Finally, what is your process for measuring resource usage? In level three, you should be measuring your container usage, CPU and memory (runtime and uptime). Automation and processes associated with software release will also be extended to platforms. Lifecycle operations such as upgrades and patching, particularly CVEs and critical updates will benefit from further automation and the introduction of Infrastructure-as-code technologies.

### CI/CD

You are implementing a center of excellence around your CI/CD process.

### Change Control

Your code quality is improving as measured with automated tooling and you are seeing CI and test success frequently.

### Security

Implement automatic continuous scanning to flag misconfigurations or security issues.

### Audit and Logs

Start to audit and implement initial alerts. Filter noise.

## <i class="fas fa-edit"></i> 制度

### Policy Overview

You will implement policy-as-code and build this into your CI pipeline.

### Policy Creation

Create policies based on metrics refined around security, efficiency and reliability.

### Compliance

Policy compliance and auditing carried out through automated means on Kubernetes. This will likely include initial development of policy-as-code.

## <i class="fas fa-server"></i> 技术

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
