---
title: "云原生成熟度模型"
---



![woman at a conference](/images/woman-at-conference.jpg)

世界已经进入云原生时代，这已经不是什么秘密了！作者看到许多企业在开始云原生之旅的时候，并没有关于如何采用这些新应用程序和平台的真正框架，因此作者希望提供一个成功的框架。

此模型旨在帮助您使用 CNCF 构架从开始到全面采用云原生技术，从而在公有云和混合云的现代动态环境中运行可扩展应用程序时充分受益。

## 云原生成熟度模型 3.0（2023年秋更新）

云原生成熟度模型于 2021 年推出，主要侧重于人员、流程、制度和技术部分以及企业开展的相关活动。后来又增加了 "业务成果 "部分，作为其他类别的补充。云原生成熟度模型 3.0 的最新版本将业务成果置于模型的顶端。 原来的四个部分成为设计、开发和交付业务成果的支柱。

该成熟度模型参考 CNCF 中的资源得到了进一步加强，您可以通过阅读这些资源获得更深入的洞察和理解。

推动云原生以及扩展、改进和适应（即成熟）必须源于业务需求。 如果没有业务目标作为决策依据，任何企业都无法成为云原生企业。因此，成熟度模型现在强调企业必须考虑哪些因素，才能从云原生中获益。

作为一个行业，云原生专业人士往往默认深入讨论技术。这可能会导致 "业务 "与技术人员之间的错位。业务 "并不关心技术，它关心的是管理风险、履行合规义务、客户满意度和信任度以及成本效益。在云原生成熟度模型中，我们谈论了很多技术，但我们需要将所有技术转化为对业务有意义的语言。

在阅读成熟度模型时，每个级别都会首先讨论业务和技术人员需要关注的问题，然后再讨论这些问题对人员、流程、制度和技术的影响。在本练习中，业务人员指的是任何不属于 DevOps 团队、基础设施或平台工程小组或产品和服务开发部门的人员。如果您是技术人员，这些内容将有助于您在云原生语言和技术与业务目标和要求之间架起一座桥梁。另外值得注意的是，在该模型的较低层次中，技术确实占据主导地位，但如果您能更早地将制度、流程和执行纳入其中，就能更快地实现目标。这就是采用云原生技术如何使企业实现业务战略左移的一个例子。
最后的成本，云原生并非降低成本的 "万全之策"。随着时间的推移，它将带来许多经济效益，但企业需要面对成本之旅。一个简单的例子是，如果企业转向更多的公共云消费，CAPEX（长期资本和固定资产成本，如计算设备和折旧）与 OPEX（运营成本，通常作为“即收即付”类型安排的支出）之间的差异就需要以不同的方式来看待成本。但这并不是同类比较，在成熟度的最初几个阶段，随着“传统”基础设施的维护和“云原生”平台的推出，成本可能会上升。对于这些企业规模的组织而言，需要采用 FinOps，并作为这段旅程中的财务盟友。

### 示例 KPI

云原生成熟度模型有四个维度：
1. 人
2. 流程
3. 制度
4. 技术

这些都体现了特定的业务目标。下图举例说明了凌驾于业务和技术之上的目标，以及这些目标如何在各个维度之间转化。其中包括一些业务 KPI 示例。

|                      | Business to Business                                                                                                                                                                                                                       | Business to Business                                                                                                                                                                                                                     | Business to Consumer                                                                                                                                                             |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business  model**  | ACME software sells to the enterprise market.                                                                                                                                                                                              | Anville Enterprise provides data to financial service organizations using ACME software.                                                                                                                                                 | ABC Company purchases data from Anville Enterprise.                                                                                                                              |
| **Business goal**    | To sell to the enterprise, ACME must demonstrate security and compliance within the supply chain.<br>*KPI: Zero policy violations*                                                                                                         | To meet its customers' demands, it must scale to deliver services to 20,000 locations.<br>*KPI: Scalability*                                                                                                                             | To hit its revenue targets, it must improve customer retention through improved satisfaction rates.<br>*KPI: eg. High Availability*                                              |
| **Technology goal**  | ACME software must ensure that all software is signed and has Software Bill of Materials (SBOM) as part of its deliverables, and meets all PCI, NIST and SOC2 standards for software delivery.                                             | Anville must rely on a cloud native platform that is able to deliver capacity as required. It must be able to ensure compliance with policy at all times.                                                                                | ABC must ensure that it has modern applications accessible from all platforms at all times, with frequent updates, and can be trusted by customers with their financial details. |
| **Process goals**    | Implement a pipeline for delivering software with all relevant metadata attached and signed.                                                                                                                                               | Anville must have a strong delivery process for its software and platforms.                                                                                                                                                              | ABC must understand the data it is purchasing with the assurance it meets all standards and can be audited i.e. how did we get the data and how did Anville process it.          |
| **Policy goals**     | ACME will understand what requirements it needs to meet to sell to customers, including customers’ own policy requirements                                                                                                                 | Business dictates what regulatory requirements it must meet. Outcome will be a documented completed checklist of achieved standards for the business to review.                                                                          | ABC must meet (and all vendors meet) PCI compliance standards and pass PCI audits.                                                                                               |
| **People goals**     | People will follow all security and policy requirements. People will adopt a security first approach to all activities. ACME will invest in a security center of excellence and train developers on secure software development processes. | Developers responsible for integration of ACME’s software, and DevOps teams responsible for operating platforms will be well skilled on cloud native and have adopted an agile approach with quick feedback/testing loops to meet scale. | Development teams are getting new features to market faster as they are enabled with guardrails.                                                                                 |
| **Example KPIs**     | Count of software vulnerabilities<br>Time to patch<br>Code coverage testing<br>SOC 2 Audit Report                                                                                                                                          | Uptime measurement<br>SLAs<br>Response times<br>Time to patch<br>Release frequency                                                                                                                                                       | Baseline customer retention rate (CRR)<br>Net Promoter Score (NPS)<br>Customer effort score (CES)<br>Customer satisfaction score (CSAT)<br>Customer churn rate                   |


## 目标受众

The main target for this model is broad and encompasses the following groups:

* Businesses that are embarking or starting down the path of digital transformation
* Those who want to navigate the massive CNCF landscape to hone in on a framework model you can implement and trust
* Open source and CNCF projects and practitioners wishing to use or contribute to the model
* Leadership teams looking to understand the benefits of cloud native, scope of effort, and level of investment
* Technologists wishing to get started with moving towards cloud native technologies who are keen to understand in more detail the journey ahead of them, as well as have further areas for investigation highlighted

## 模型是如何划分的

Developing a cloud native maturity is not just a technology journey, but one which is influenced by five major areas:

1. Business outcomes - What can the business expect to achieve from cloud native? How are you going to communicate the benefits to the CXO and/or business leadership?
2. People - How do we work, what skills do we require, what does our organization look like as we move through this process, and how do we weave security into how people work?
3. Process - What processes do we need, what technology is required and how do we map workflows and CI/CD using infrastructure as code (IaC) and how do we shift security as "far left" as possible?.
4. Policy - What internal and external policies are required to achieve security and compliance mandates? Do these policies reflect your business’s operating environment?
5. Technology - What technology is required for you to deliver on the benefits of cloud native and support people, processes and policy as well as the technology for CI/CD, adoption of GitOps, observability, security, storage, networking, etc.

## 但如果该模型不适合我们呢 ... ...

Relax! No project, organization or person is expected to match all of the details contained within the model, perfectly. It’s deliberately designed to cover many different scenarios; everything from startups to Fortune 100 companies. Take what is most relevant to you and your situation, and if this helps inspire you in (or indeed account for, but then rule out) any items or areas, then we consider this to be a success for you!

*The aim of this model is not to be overly prescriptive, but rather to be a tool to help guide you on your journey. Cloud native transformation is not an exact science, but rather lives within your project, your organization, and of course takes place in a specific time and place.*

## 云原生成熟度模型的先决条件

The first, and arguably most important, thing to do when adopting cloud native is to outline your business and technology goals, particularly what your business expects to gain from the exercise.

Few organizations start out with an entirely blank slate (often known as a greenfield).  You may have something like the following:

* Your organization may range in age from a few months, years, decades or even longer. And may have a collection of technical debt.
* You may have a considerable application, platform and infrastructure estate.
* You may even have started a migration to cloud service providers, perhaps adopting a ‘lift and shift’ approach with your existing estate.

The most important thing you should have is a clear idea of the business outcomes you expect to achieve. These will be your ‘north star’, helping guide your decision making process.

## 何时才是正确的时机

You may be ready to start your cloud native journey if you meet the following criteria:

### 业务成果

* Whether you are a startup choosing to build on the cloud or an enterprise organization adopting cloud native, there must be long term business goals that require the investment in cloud native. These goals may be derived internally from corporate strategy, or from outside from industry trends, or competitive market pressures.
* Prioritized business goals must drive the decision making with all stakeholders aligned.
* Organizations should have established meaningful processes for sharing information and results between business units.


### 人

* You have significant separation between development and operations, with a clear staff delineation between infrastructure, cloud, application operations and development.
* You have traditionally split your operations and infrastructure divisions and your application development departments. This may have been enforced by regulatory requirements.
* This split may have worked well for you, and indeed may be mandated. But you may be finding additional challenges as much of your platforms become code and application oriented. You may find you require skills in your platform area that have traditionally belonged within your application area.

### 流程

* Your application deployments may be done manually in many cases, or your release processes may take a very long time to complete, often with multiple attempts.
* You may support multiple distributions of the same software and have trouble upgrading or evaluating without significant down-time.

### 制度

* Policy may be in the form of conventions and rules that are located external to the application and its platform, and are not enforced natively within your applications and runtime environment.
* Policies might be disparate and built in silos; defense in depth parity might be more of an accident than deliberate.

### 技术

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

## 云原生成熟度模型旅程

There are five stages within the cloud native maturity model. While you may be in stage five for one application, at the same time, you may be at stage 2 for another. Keep that in mind as you identify your stage of maturity.

* **[Level 1 - Build]({{< ref "/level-1" >}})**
You have a baseline cloud native implementation in place and are in pre-production.

* **[Level 2 - Operate]({{< ref "/level-2" >}})**
The cloud native foundation is established and you are moving to production.

* **[Level 3 - Scale]({{< ref "/level-3" >}})**
Your competency is growing and you are defining processes for scale.

* **[Level 4 - Improve]({{< ref "/level-4" >}})**
You are improving security, policy and governance across your environment.

* **[Level 5 - Adapt]({{< ref "/level-5" >}})**
You are revisiting decisions made earlier and monitoring applications and infrastructure for optimization.

In each of the following sections, we will highlight core concepts and discuss what this means in each stage of your maturity across people, process, policy and technology.

We welcome feedback from the community on the Cloud Native Maturity Model!


## 涉及到的技术立场
The Cloud Native Maturity model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software.
