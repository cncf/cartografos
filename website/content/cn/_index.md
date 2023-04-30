---
title: "云原生成熟度模型"
---

![woman at a conference](/images/woman-at-conference.jpg)

毫无疑问，世界已经走向了云原生！这个工作团队的作者们见证了许多组织开始他们的云原生之旅，但并没有真正的框架可以采用来接受这些新的应用程序和平台。作者希望为成功提供这样一个框架。

这个模型的目的是帮助您通过使用CNCF的技术栈，从概念阶段到完全采用云原生技术，以在公有云和混合云中运行可扩展的应用程序，从而实现现代动态环境下的全部优势。

## 目标听众

这个模型的主要目标是广泛的，包括以下群体：

* 正在启动或踏上数字化转型之路的企业
* 希望在庞大的CNCF景观中寻找可实施并值得信赖的框架模型的人群
* 希望使用或为该模型做出贡献的开源和CNCF项目和从业者
* 领导团队，希望了解云原生的好处、工作范围和投资水平
* 希望开始转向云原生技术并渴望更详细地了解前方的旅程，以及有进一步研究重点的技术人员


##  这个模型是如何划分的


发展云原生成熟度不仅仅是一项技术之旅，还受到四个主要领域的影响：

1. 人员 - 我们如何工作，需要什么技能，随着我们在这个过程中前进，我们的组织会是什么样子，如何将安全措施融入人们的工作中？
2. 过程 - 我们需要哪些流程，需要什么技术，并如何使用基础架构即代码 (IaC) 来映射工作流程和 CI/CD，并如何尽可能向“最左侧”移动安全性。
3. 策略 - 为实现安全性和合规性，需要什么内部和外部政策？这些政策是否反映了您企业的运营环境？
4. 技术 - 您需要哪些技术才能提供云原生的好处，并支持人员、流程和策略以及 CI/CD 技术、GitOps 采用、可观测性、安全性、存储、网络等。
5. 业务成果 - 企业可以从云原生中期望实现什么？您将如何向 CXO 和/或业务领导层传达这些好处？
6. 
## 但是，如果我们不符合这个模型呢？


放心！没有任何项目、组织或个人能够完美地符合模型中包含的所有细节。该模型的设计是有意涵盖许多不同的情况；从初创公司到财富100强企业等一切组织。选择与您和您的情况最相关的内容，如果这有助于激励您（或者确实解决了一些问题，但是某些项目或领域除外），那么我们认为这对您来说就是一种成功！

*该模型的目的不是过度地描述每个细节，而是为了成为一个指导您旅程的工具。云原生转型并不是一门精确的科学，而是存在于您的项目、您的组织中，并在特定的时间和地点进行。

## Prerequisites for the Cloud Native Maturity Model

The first, and arguably most important, thing to do when adopting cloud native is to outline your business and technology goals, particularly what your business expects to gain from the exercise.

Few organizations start out with an entirely blank slate (often known as a greenfield).  You may have something like the following:

* Your organization may range in age from a few months, years, decades or even longer. And may have a collection of technical debt.
* You may have a considerable application, platform and infrastructure estate.
* You may even have started a migration to cloud service providers, perhaps adopting a ‘lift and shift’ approach with your existing estate.

The most important thing you should have is a clear idea of the business outcomes you expect to achieve. These will be your ‘north star’, helping guide your decision making process.

## When is the right time

You may be ready to start your cloud native journey if you meet the following criteria:

### People

* You have significant separation between development and operations, with a clear staff delineation between infrastructure, cloud, application operations and development.
* You have traditionally split your operations and infrastructure divisions and your application development departments. This may have been enforced by regulatory requirements.
* This split may have worked well for you, and indeed may be mandated. But you may be finding additional challenges as much of your platforms become code and application oriented. You may find you require skills in your platform area that have traditionally belonged within your application area.

### Process

* Your application deployments may be done manually in many cases, or your release processes may take a very long time to complete, often with multiple attempts.
* You may support multiple distributions of the same software and have trouble upgrading or evaluating without significant down-time.

### Policy

* Policy may be in the form of conventions and rules that are located external to the application and its platform, and are not enforced natively within your applications and runtime environment.
* Policies might be disparate and built in silos; defense in depth parity might be more of an accident than deliberate.

### Technology

* You’ll likely have VM’s on demand.
* Some automation scattered around.
* You will have baseline security components such as SIEM, RBAC concepts, and a directory of some type.
* You have some software packaging, but this could be inconsistent.
* You’ll have perimeter security and perhaps some coarse network zoning at layers 1-4, but you may feel some anxiety and security practices.
* Your experience with encryption may vary - you might have some certificate authorities for example, but they may not be used extensively, with a high barrier to entry for many.
* Your applications may rely on infrastructure solutions for high availability, which in turn may be more costly than you’d like
* Your server estate could range from single physical or virtual servers with low levels of availability, through to highly available clusters. Scaling could be a real challenge and may require considerable investment in money, time and planning.
* You may have started to dip your toe into a 'Everything as Code' model. i.e. started to script your infrastructure with Terraform.

![man at a conference](/images/man-at-conference.jpg)

### Business Outcomes

* Your business is growing and needs the ability to scale to meet demand.
* Your business needs to improve and/or deliver an exceptional customer experience.
* Your business needs to get features to market faster.

## The Cloud Native Maturity Model Journey

There are five stages within the cloud native maturity model. While you may be in stage five for one application, at the same time, you may be at stage 2 for another. Keep that in mind as you identify your stage of maturity.

* **[Level 1 - Build]({{< ref "/level-1" >}})**  
You have a baseline cloud native implementation in place and are in pre-production.

* **[Level 2 - Operate]({{< ref "/level-2" >}})**  
The cloud native foundation is established and you are moving to production.

* **[Level 3 - Scale]({{< ref "/level-3" >}})**  
Your competency is growing and you are defining processes for scale.

* **[Level 4 - Improve]({{< ref "/level-4" >}})**  
You are improving security, policy and governance across your environment.

* **[Level 5 - Optimize]({{< ref "/level-5" >}})**  
You are revisiting decisions made earlier and monitoring applications and infrastructure for optimization.

In each of the following sections, we will highlight core concepts and discuss what this means in each stage of your maturity across people, process, policy and technology.

We welcome feedback from the community on the Cloud Native Maturity Model!

## Position on Included Technologies
The Cloud Native Maturity model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software. 

