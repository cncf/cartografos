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

## 云原生成熟度模型的先决条件


在采用云原生技术时，首先（也可以说是最重要的）要做的事情是明确您的业务和技术目标，尤其是您的业务希望从这个过程中获得什么。

很少有组织从完全的空白状态开始（通常称为绿田地）。您可能有以下情况：

*您的组织可能存在几个月、几年、几十年甚至更长时间的存在，并且可能存在技术债务的积累。
*您可能拥有相当数量的应用程序、平台和基础设施资产。
*您甚至可能已经开始迁移到云服务提供商，也许是采用“提升和迁移”的方法来处理您现有的资产。

您应该拥有的最重要的东西是对您期望实现的业务成果的清晰理解。这些将是您的“北极星”，帮助指导您的决策过程。


## 什么时候是合适的时机

如果您符合以下标准，则可能已经准备好开始云原生之旅：

### 人员

*您明确的区分开发和运维，基础设施、云、应用程序运维和开发都有不同的团队。

*您通常将运维和基础设施部门与应用程序开发部门分开。这可能是由监管要求造成的。

*这种分割可能对您很有效，甚至可能是被迫的。但是，随着您的平台变得越来越以代码和应用为导向，您可能会面临额外的挑战。您可能会发现您需要在平台领域具备传统上属于应用领域的技能。


### 流程

*您的应用程序部署可能在许多情况下都是手动完成的，或者您的发布流程可能需要很长时间才能完成，通常需要多次尝试。

*您可能支持同一软件的多个发行版，并且在不引起重大停机时间的情况下升级或评估过程中存在问题。


### 政策

*政策可能以公约和规则的形式存在于应用程序和平台之外，并且不会在应用程序和运行时环境内部本地执行。

*政策可能是分散的，并在孤立的组织中制定；深度防御的一致性可能更多地是偶然而非有意为之。

### 技术

*您可能会有随选VM。

*有一些分散的自动化。

*您将拥有基线安全组件，例如SIEM、RBAC概念和某种类型的目录。

*您会有一些软件包装，但这可能不一致。

*您会有周边安全性，也许在1-4层有一些网络分区，但您可能会对安全实践感到一些焦虑。

*您的加密经验可能有所不同 - 您可能有一些证书颁发机构，但它们可能不会被广泛使用，并且对许多人来说具有很高的准入门槛。

*您的应用程序可能依赖于基础架构解决方案来实现高可用性，这反过来可能比您想要的更昂贵

*您的服务器集群可能从单个物理或虚拟服务器开始，可用性水平较低，到高可用性集群。扩展可能是一个真正的挑战，可能需要大量的投资资金，时间和策划。

*您可能已经开始涉足“一切都是代码”的模式。也就是说，开始使用Terraform编写基础架构脚本。

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

