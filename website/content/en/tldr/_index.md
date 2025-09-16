---
title: "TL;DR - Maturity Model Focus Areas"
weight: 20
description: >
  If you’re just looking for a quick overview of where to start, this is the tl;dr.
---

Developing cloud native maturity is not just a technology journey, but one which is influenced by five major areas. This The Cloud Native Maturity Model is packed with detail, but if you’re just looking for a quick overview of where to start, this is the tl;dr. Instead of diving deep into every dimension, use this summary as a starting point to understand the progression and decide where your organization fits today.

# People Introduction

As you adopt cloud native technologies, your team's expertise will grow. The Cloud Native Maturity Model spans five key dimensions: People, Process, Policy, Technology and Business Outcomes. This introduction focuses on People—the foundation of a successful deployment.  

Progressing from level one to five, your team starts with basic technical knowledge. Over time, they invest in training, build competency, and shift responsibilities to developers. Maturity is reached when DevOps and DevSecOps are fully integrated, and your team confidently explores new technologies. Leadership embraces cloud native as the future, recognizing its business value and driving agile transformation.

* Level 1: Your business aligns with cloud native goals, and leadership understands its benefits. The team is new to the technology but has basic technical knowledge and relevant qualifications.  
    
* Level 2: Individuals actively train and build skills, creating small groups of subject matter experts (SMEs). DevOps emerges as cloud engineers and developer groups contribute platform skills. Leadership begins taking ownership of cloud native initiatives.  
    
* Level 3: Competency expands across Dev, Ops, and Security, with formalized expertise, standardized practices, and accelerators. You may have a platform engineering team (see [platform engineering maturity model](https://tag-app-delivery.cncf.io/whitepapers/platform-eng-maturity-model/)) Cloud-native is integrated into business strategy as a core principle.  
    
* Level 4: Competency shifts to development teams, enabling self-service infrastructure. Leadership fully commits, driving cloud native transformation across the organization.  
    
* Level 5: Your organization operates with fully integrated DevOps and Platform Engineering. Teams confidently experiment with new technologies and sandbox trials, continuously innovating and adapting to change.

# Process Introduction

This introduction addresses the process. Your process will affect your cloud native footprint, cluster topology and sizing. It will support your CI/CD maturity and help to improve your team's ability to ship applications faster.

As you start your transformation, you will lack process and consistency across implementations. However, that will change over time as you develop and document your processes and capability. Documentation should be close to code and potentially machine based. By the time you are achieving maturity, you will have a consistent and mature process with a template-based approach, and you will actively revisit your standards, identify configuration drift and adjust standards based on business requirements.

Process enables repeatability. In your ephemeral environment, you need to ensure that the processes implemented can be repeated across teams and clusters. This is core to your process implementation.

* Level 1: You will map both functional (application features and code) and non-functional (performance, capacity, availability) application requirements while defining how your organization will scale. Feedback will be handled manually through Slack, email, or phone and remediation will also be manual.  
    
  To introduce repeatability, you will begin defining your Git workflow. Keeping platforms and technology up to date, especially with security patches, is critical, as vulnerabilities pose significant risks. Updates will likely be applied manually on an ad-hoc basis or through built-in distribution update systems.  
    
* Level 2: The focus shifts to promoting basic applications into production. By this stage, you should have a well-established Git and CI workflow. You will implement structured build and deployment processes that align with cloud-native and container-native CI/CD principles.  
    
* Level 3: Standardization across the organization becomes a priority, streamlining onboarding and expanding cloud-native adoption. You will establish a feedback loop and invest in repeatability.  
    
  Key considerations include:  
  * Ensuring accessibility to necessary tools (e.g., Git services, workspace collaboration) to save time and reduce duplication.  
  * Implementing a process for measuring resource usage, including container utilization, CPU, and memory (runtime and uptime).  
  * Expanding automation to software release processes and platforms.  
  * Enhancing lifecycle operations, such as patching and upgrades, particularly for CVEs and critical updates, by incorporating Infrastructure-as-Code (IaC) tools.


* Level 4: Governance will fully support DevSecOps, with guardrails in place to facilitate agile software development. You will establish an application services library and set policies around container usage, such as auto-scaling or high-performance computing (HPC) policies.  
    
* Level 5: Achieving process maturity will see you build design capabilities for cloud native. You’ll also automate responses by using monitoring failures to restart or manage problematic and failing resources. Resource usage data will play a key role in cost optimization, and your processes will include providing business cost analysis, ensuring efficiency and financial accountability in cloud-native operations.

# Policy Introduction 

This introduction addresses policy, the critical implementation of internal requirements, and compliance to external regulations. 

The journey of adopting policy in cloud native environments parallels the learning curve of Kubernetes and cloud native technologies, transitioning from an imperative to a declarative approach. Rather than specifying the procedure, this dimension outlines outcomes and results you should anticipate. Understand that policy adoption is a gradient, every organization has a different risk appetite. 

Policy comes from both internal and external sources, forming a set of rules and requirements that the technical organization must interpret and comply with. In fast-changing environments, policy can be a contentious topic, often leading to disputes. Recognizing these challenges—and understanding how to mitigate them—is essential.

Policy input generally falls into three categories, each targeting different layers of the organization:

1. **Regulators (Business)** – Ensure the integrity of the industry, such as finance, healthcare, or utilities.  
2. **Legal (Compliance)** – Mandates like GDPR and EU DORA, enforced by regulators.  
3. **Technical (Standards & Guidelines)** – Frameworks from institutions like NIST and MITRE that provide technical guidance.

Not all policies carry the same weight, making it important to distinguish between regulatory, legal, and technical requirements.

## Policy Level Overview

* Level 1: You will have a limited set of documented policies in place to support services you're building in the cloud. You are working with compliance teams to evaluate policy obligations and how they may change with cloud native technology.  
    
* Level 2: As your services reach production, you have initial policies agreed upon and these are recorded.  
    
* Level 3: You will implement policy-as-code and build this into your processes.  
    
* Level 4: You now have defined SLAs around policies and remediation. Treating policy-as-code and enforcement as subject to a software development lifecycle.  
    
* Level 5: Based on your learnings, you will refine your policies as your organization achieves maturity, taking advantage of technologies such as machine learning in order to improve detection and enforcement. Your policy apparatus is constantly evolving with the changing cloud native threat landscape.

# Technology Introduction 

## Position on Included Technologies

***The Cloud Native Maturity Model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software.***

## Introduction

The Cloud Native Maturity Model covers five major dimensions \- People, Process, Policy, Technology and Business Outcomes. This paper addresses technology \- the practical tooling that makes up cloud native applications, platforms, and infrastructure. As well as referring to specific technologies, this paper aims to show the stages you may go through as you move from starting out all the way through to cloud native excellence.

This paper illustrates just one path, but all journeys differ. This is absolutely as it should be, as organizations all start out at different points and have different destinations (business outcomes). Different locations, sizes, starting points (greenfield or long established), regulatory environments, and of course people, all influence the cloud native journey.

The technology section of the Cloud Native Maturity Model is not exhaustive. We would love contributions to ensure the model is robust and useful for all users. All readers are encouraged to submit GitHub PRs with comments and suggestions.

## The Technology Overview

We anticipate you’ll have a reasonable understanding of why you want to adopt cloud native technology i.e. your expected business outcomes. Clarity on why you wish to undertake this journey to achieving full cloud native adoption is your largest asset. At a high level, the key steps in your cloud native journey will look something like this:

* Level 1: You’ll have your initial experimentation and adoption of Kubernetes. You’ll start with relatively basic tools and technology. You’ll assess your existing toolset to see how they fit within the new landscape (what plays well with cloud native, and what doesn’t?). You’ll have limited automation, but don’t worry, it’s coming\! Your focus is on getting the baseline technology implemented, and you won’t be in production yet.  
    
* Level 2: This marks your first step into production. You’ve worked hard to build your foundation in Level 1, and now you are moving to production. You might have started with something relatively small and simple, but this leap to production has certainly required you to address some significant steps. You’ll probably have had to incorporate monitoring and observability into your workloads. You’ll have brought key observability tooling in and started monitoring your clusters for standard metrics such as RAM, CPU etc. While you might be starting to evaluate application tracing, don’t worry about it too much if you have started to gather core metrics. Your focus here is on getting an application running in production and having enough platform resource, observability and operational capability to support it within your organization.  
    
* Level 3: Here you start to scale. Your suite of tools is more standardized. You're getting your release tooling, secrets management and policy tooling in place. You’re also starting to get a level of buy-in across your organization, which is helping to propel you forward. This is where you will be running the largest number of tools as you will be in the thick of evaluating, implementing, and running in production.  
    
* Level 4: You’ve got full control over your environment, and you’ve built your confidence, with rapid adoption of cloud native patterns for new applications and platforms. You’ve also gained organizational commitment to cloud native and this is adding to your momenting. You’re starting to feel like you’ve “crossed the chasm.”  
    
* Level 5: Your investment is now focused on automation in functional and non-functional areas such as scanning, policy, security and testing. You’ve got operators doing your operations for you and you’re fully automated.

Please note, technology is changing rapidly with AI developments. Within each section, you should consider how AI can help you improve or streamline actions. There is a huge opportunity with AI and while we want the Cloud Native Maturity Model to cover AI, we defer to the AI community within the CNCF for its expertise. You can read more in the [CNCF AI whitepaper](https://tag-runtime.cncf.io/wgs/cnaiwg/whitepapers/cloudnativeai/). 