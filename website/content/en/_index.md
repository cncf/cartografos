---
title: "Cloud Native Maturity Model"
---



![woman at a conference](/images/woman-at-conference.jpg)

It’s no secret the world has gone cloud native! The authors of this body of work have seen many organizations start their cloud native journey with no real framework on how to adopt these new applications and platforms. The authors want to provide a framework for success.

The intent of this model is to help you move from inception through to full adoption of cloud native technologies using the CNCF landscape to achieve the full benefits of running scalable applications in modern, dynamic environments in public and hybrid clouds.

## The Cloud Native Maturity Model 3.0 (updated in Autumn 2023)

The Cloud Native Maturity Model, launched in 2021, has been primarily focused on the People, Process, Policy and Technology sections and the related activities undertaken by organizations. Business Outcomes were later added as a section, as a peer to the other categories. The latest iteration of the Cloud Native Maturity Model 3.0 places Business Outcomes at the top of the model.  The original four sections become the pillars upon which Business Outcomes are designed, developed, and delivered. 

The maturity model has been further enhanced with references to resources throughout the CNCF that you can read to gain further insight and understanding.

The drive to go cloud native, and to scale, improve and adapt i.e. mature, must result from a business requirement.  No organization can become cloud native without business goals informing the decision. As a result, the maturity model now emphasizes what the business must consider to get the benefit of cloud native. 

Too often as an industry, cloud native professionals default to discussing the technology in depth. This can cause a misalignment between “the business” and technologists. The “business” doesn’t care about the technology. It cares about managing risk, meeting compliance obligations, customer satisfaction and trust, and cost effectiveness. In the Cloud Native Maturity Model, we talk a lot about the technology, but we need to translate all the technology into language meaningful to the business. 

As you read through the Maturity Model, each Level now discusses first what the business and technologists need to focus on before getting into how that impacts People, Process, Policy and Technology. For the purposes of this exercise, the business is anyone who is not a member of a DevOps team, an infrastructure or platform engineering group, or product and service development. If you are on the technology side, this content should help as you bridge the gap between cloud native language and technology with business goals and requirements. Also of note, in the lower levels of the model, technology does dominate, however when you bring policy, process and enforcement into play earlier, you’ll achieve goals faster. This is an example of how cloud native adoption can enable organizations to shift left their business strategy.
Cost
Finally, cloud native isn’t a cost reduction “sure-thing”. Over time, it will provide many financial benefits, but there is a cost journey the organization needs to undertake. Cost will need to be viewed differently and an easy example of this is the difference between CAPEX (long term capital and fixed asset costs such as compute equipment and depreciation) vs. OPEX (operating costs that are typically treated as expenses as a result of pay-as-you-go type arrangements) if an organization moves to more public cloud consumption. But it isn’t a like-for-like comparison and in the first few levels of maturity, your costs may go up as you maintain “legacy” infrastructure and launch “cloud native” platforms. For those enterprise size organizations, FinOps needs to be adopted and become a fiscal ally on this journey.

### Example KPIs

The cloud native maturity model has four dimensions:
1. People
2. Process
3. Policy 
4. Technology

These all manifest within them a specific business goal. The following chart illustrates example overriding business and technology goals and how they translate across the dimensions. It includes some example business KPIs.

|                      | Business to Business                                                                                                                                                                                                                       | Business to Business                                                                                                                                                                                                                     | Business to Consumer                                                                                                                                                             |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business  model**  | ACME software sells to the enterprise market.                                                                                                                                                                                              | Anville Enterprise provides data to financial service organizations using ACME software.                                                                                                                                                 | ABC Company purchases data from Anville Enterprise.                                                                                                                              |
| **Business goal**    | To sell to the enterprise, ACME must demonstrate security and compliance within the supply chain.<br>*KPI: Zero policy violations*                                                                                                         | To meet its customers' demands, it must scale to deliver services to 20,000 locations.<br>*KPI: Scalability*                                                                                                                             | To hit its revenue targets, it must improve customer retention through improved satisfaction rates.<br>*KPI: eg. High Availability*                                              |
| **Technology goal**  | ACME software must ensure that all software is signed and has Software Bill of Materials (SBOM) as part of its deliverables, and meets all PCI, NIST and SOC2 standards for software delivery.                                             | Anville must rely on a cloud native platform that is able to deliver capacity as required. It must be able to ensure compliance with policy at all times.                                                                                | ABC must ensure that it has modern applications accessible from all platforms at all times, with frequent updates, and can be trusted by customers with their financial details. |
| **Process goals**    | Implement a pipeline for delivering software with all relevant metadata attached and signed.                                                                                                                                               | Anville must have a strong delivery process for its software and platforms.                                                                                                                                                              | ABC must understand the data it is purchasing with the assurance it meets all standards and can be audited i.e. how did we get the data and how did Anville process it.          |
| **Policy goals**     | ACME will understand what requirements it needs to meet to sell to customers, including customers’ own policy requirements                                                                                                                 | Business dictates what regulatory requirements it must meet. Outcome will be a documented completed checklist of achieved standards for the business to review.                                                                          | ABC must meet (and all vendors meet) PCI compliance standards and pass PCI audits.                                                                                               |
| **People goals**     | People will follow all security and policy requirements. People will adopt a security first approach to all activities. ACME will invest in a security center of excellence and train developers on secure software development processes. | Developers responsible for integration of ACME’s software, and DevOps teams responsible for operating platforms will be well skilled on cloud native and have adopted an agile approach with quick feedback/testing loops to meet scale. | Development teams are getting new features to market faster as they are enabled with guardrails.                                                                                 |
| **Example KPIs**     | Count of software vulnerabilities<br>Time to patch<br>Code coverage testing<br>SOC 2 Audit Report                                                                                                                                          | Uptime measurement<br>SLAs<br>Response times<br>Time to patch<br>Release frequency                                                                                                                                                       | Baseline customer retention rate (CRR)<br>Net Promoter Score (NPS)<br>Customer effort score (CES)<br>Customer satisfaction score (CSAT)<br>Customer churn rate                   |


## Target audience

The main target for this model is broad and encompasses the following groups:

* Businesses that are embarking or starting down the path of digital transformation
* Those who want to navigate the massive CNCF landscape to hone in on a framework model you can implement and trust
* Open source and CNCF projects and practitioners wishing to use or contribute to the model
* Leadership teams looking to understand the benefits of cloud native, scope of effort, and level of investment
* Technologists wishing to get started with moving towards cloud native technologies who are keen to understand in more detail the journey ahead of them, as well as have further areas for investigation highlighted

## How the model is divided up

Developing a cloud native maturity is not just a technology journey, but one which is influenced by five major areas:

1. Business outcomes - What can the business expect to achieve from cloud native? How are you going to communicate the benefits to the CXO and/or business leadership?
2. People - How do we work, what skills do we require, what does our organization look like as we move through this process, and how do we weave security into how people work?
3. Process - What processes do we need, what technology is required and how do we map workflows and CI/CD using infrastructure as code (IaC) and how do we shift security as "far left" as possible?.
4. Policy - What internal and external policies are required to achieve security and compliance mandates? Do these policies reflect your business’s operating environment?
5. Technology - What technology is required for you to deliver on the benefits of cloud native and support people, processes and policy as well as the technology for CI/CD, adoption of GitOps, observability, security, storage, networking, etc.

## But what if we don’t fit this model…

Relax! No project, organization or person is expected to match all of the details contained within the model, perfectly. It’s deliberately designed to cover many different scenarios; everything from startups to Fortune 100 companies. Take what is most relevant to you and your situation, and if this helps inspire you in (or indeed account for, but then rule out) any items or areas, then we consider this to be a success for you!

*The aim of this model is not to be overly prescriptive, but rather to be a tool to help guide you on your journey. Cloud native transformation is not an exact science, but rather lives within your project, your organization, and of course takes place in a specific time and place.*

## Prerequisites for the Cloud Native Maturity Model

The first, and arguably most important, thing to do when adopting cloud native is to outline your business and technology goals, particularly what your business expects to gain from the exercise.

Few organizations start out with an entirely blank slate (often known as a greenfield).  You may have something like the following:

* Your organization may range in age from a few months, years, decades or even longer. And may have a collection of technical debt.
* You may have a considerable application, platform and infrastructure estate.
* You may even have started a migration to cloud service providers, perhaps adopting a ‘lift and shift’ approach with your existing estate.

The most important thing you should have is a clear idea of the business outcomes you expect to achieve. These will be your ‘north star’, helping guide your decision making process.

## When is the right time

You may be ready to start your cloud native journey if you meet the following criteria:

### Business Outcomes

* Whether you are a startup choosing to build on the cloud or an enterprise organization adopting cloud native, there must be long term business goals that require the investment in cloud native. These goals may be derived internally from corporate strategy, or from outside from industry trends, or competitive market pressures.
* Prioritized business goals must drive the decision making with all stakeholders aligned.
* Organizations should have established meaningful processes for sharing information and results between business units.


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

* **[Level 5 - Adapt]({{< ref "/level-5" >}})**
You are revisiting decisions made earlier and monitoring applications and infrastructure for optimization.

In each of the following sections, we will highlight core concepts and discuss what this means in each stage of your maturity across people, process, policy and technology.

We welcome feedback from the community on the Cloud Native Maturity Model!


## Position on Included Technologies
The Cloud Native Maturity model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software.
