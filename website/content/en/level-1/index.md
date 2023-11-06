---
title: "Level 1 - Build"
description: >
   You have a baseline cloud native implementation in place and are in pre-production.
---

## <i class="fas fa-building"></i> Business Outcomes

### Business Outcomes

*“For many business leaders, the migration and continuing adoption of cloud native technology are not as clear-cut as migrating workloads as-is from on-premises to hybrid/public clouds. They are unlikely to sign off on major technological shifts, which inevitably create process and cultural change, without understanding the tangible benefits to them.”* [CTO Summit](https://www.cncf.io/reports/cto-summit-na-2022/)

Prior to arriving at level one of the model, your business should have agreed the goals for the move. These business goals need to inform adoption of cloud native technologies. Goals will center around managing risk, meeting compliance, customer satisfaction and trust and cost effectiveness. While the technologist might translate this into avoiding vendor lock-in, capacity and availability planning, disaster recovery, response times, etc, ensure that whenever discussing decisions to root the conversation in the business goal.

In level one, the organization must prioritize its top business goals/issues. This is an important step as prioritization/ranking of business goals will help technologies factor in tradeoffs. Compliance and disaster recovery will no doubt be important, but for some organizations, that might not be the main driver. Business scenario planning is essential. For example, in the case where a company has decided to use public cloud, if customer satisfaction is the priority goal and needs faster website response times, then the technology team will select cloud regions close to the customer. If cost reduction is a primary goal however, then a more cost-effective cloud region might be selected. Another example might be that it is cheaper to host data in the US, but due to EU data privacy laws, that isn’t an option. This is a very high level example, but should showcase how the prioritization of all business goals must inform decision making.

At this level, the organization is experimenting with cloud native. This should also translate into business expectations. Technologies should be given the freedom to try different experiments to achieve goals. Experiments should be documented, OKRs (Objectives and Key Results) or KPIs (Key Performance Indicators) created and provided to the business during this phase. The business should expect to see the outcomes of these experiments before continuing to embark on its cloud native journey. This helps to build confidence between the technology and business teams and is absolutely a vital step particularly as cloud native changes the way an organization operates.

### Cost

In level one, the finance, technology and business teams need to be aligned. Technology needs to understand resourcing and the finance team needs to understand change fees. The organization must make allowances for running both the legacy systems and new cloud environments. In level one, costs will not go down, however as it is just the build/experimentation phase, the costs should not be exorbitant.


## <i class="fas fa-users"></i> People

### People Overview

Cloud native framework is driving your business and technical goals. You and your team are new to the technology, however do have some basic technical understanding and some pre-existing qualifications. Your business leaders understand the benefits of cloud native.

### Organizational Change

As you transform, you will have limited organizational support and will be in a proof of concept (POC) phase or be focused on only one application.

### Teams and Decentralization

Teams are exploring cloud native tooling, primarily Kubernetes. However, this is not just for the sake of exploring, but rather it is with the goal of reaching production. All work is generally taking place within a formal MVP program.

### Security

The people implementing cloud native will need to focus on security. Default security settings will be used and will work in pre-production. You’ll spend time identifying your open source security posture and conduct a security POC of the pre-production environment so that both Dev, Ops and security understands what is required in cloud native workloads.

### Developer Agility

Your organization is committed to decentralization and will employ “teams of teams”. This is an essential requirement of your people. Across the different levels of maturity, people will be implementing tools for automated testing, metrics and feedback.

Developers may have learned about Agile Manifesto and adopted Scrum Framework without necessarily including Operations. Developers may attempt to resolve external dependencies themselves, slowing down feedback, with incomplete features per sprint.

### Upskilling Developers

The maturity of your people will include upskilling the development team.

Your application team will be trained in 12 factor applications, microservice and cloud native patterns. You will also require developers who are quite comfortable with cloud native concepts and tooling such as kubectl in order to bootstrap your development team.

### CNCF Certifications

Cloud Native Computing Foundation (CNCF) serves as the vendor-neutral home for many of the fastest-growing open source projects, including Kubernetes, Prometheus, and Envoy.

In order for you to build a sustainable ecosystem for cloud native infrastructure is it important to have your team invest in the CNCF Certifications. It is unlikely you’ll achieve certifications in level 1.

## <i class="fas fa-cogs"></i> Process

### Process Overview

You will map application requirements, both functional (application features and code) and non-functional, such as performance, capacity, and availability, and define how your organization will scale. Feedback will be manual such as by Slack, email, and phone, and you’ll also remediate manually also. You will start to implement repeatability by defining your Git workflow. Platform and technology lifecycle and updates, particularly security updates, need to be applied on a regular basis as vulnerable systems pose specific risks. You will likely be applying these updates by hand on an adhoc basis, or using update systems included in distributions.

### CI/CD

Central to your cloud native transformation is the adoption of CI/CD. CI/CD helps you build, test and deploy applications based on modern software development practices. Your CI/CD process will mature over time.

If you do CI/CD, you need to transform this into your cloud native environment. That includes taking existing best practices and building upon them.

### Change Control

Change control will need to be implemented to control your deployments.
You have no change control process in place. Instead changes are performed based on ad-hoc requests.

### Security

Incorporating security tooling and practices into your cloud native environment, whether through a practice or a process, as early as possible is crucial to keeping your cloud native environment secure. We often use the term ‘shift left’ to refer to bringing a practice, whether relating to testing or security, into a process as early as possible. Security is covered in all sections of the Cloud Native Maturity Model and each section with People, Process, Policy and Technology can be combined to support the security team as they seek to mature the organization’s cloud native security.

Take action: your security journey starts here. Consider security in all aspects of implementation and make it a first class citizen.

### Audit and Logs

Your process will include logging and auditing. This can be based on internal requirements or support your compliance mandates.

Manual log scraping is likely ad-hoc and you may not have a central logging point or SIEM.

## <i class="fas fa-edit"></i> Policy

### Policy Overview

We recognize policy adoption is a gradient. Every organization has a different risk appetite. Use this document as a guide to how you can define and enforce policy. By level 5, you will have achieved full policy maturity, however your mileage may vary.

You will have a limited set of documented policies in place to support services you're building in the cloud.

### Policy Creation

You will need to translate your organization’s policies and compliance requirements to your cloud native environment.

Spend time understanding your application's functional and architectural requirements.

### Compliance

You will need policies in place to achieve compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve.

Spend time understanding your compliance requirements: CIS, NIST, PCI for example. Design SLOs and priorities for compliance. This will take time and may not be a pre-production requirement, but will increase as you move to production.

## <i class="fas fa-server"></i> Technology

### Technology Overview

You’ll have your initial experimentation and adoption of Kubernetes. You’ll start with relatively basic tools and technology. You’ll assess your existing toolset to see how they fit within the new landscape (what plays well with cloud native, and what doesn’t?). You’ll have limited automation, but don’t worry, it’s coming! Your focus is on getting the baseline technology implemented, and you won’t be in production yet.

### Infrastructure

You are building your cloud infrastructure either on-prem or off. It will pay dividends to consider early your supporting technology such as your network, firewalls and IAM, access controls and policies (and if you need to change them). Many topics will come out of your initial experimentation with Kubernetes, so ensure you keep track of these - they are the ‘breadcrumbs’ you will follow as you move towards cloud native. This will include RBAC policies, load balancer and/or ingress configuration, cluster dashboards, privileged access (or lack thereof!) and container logging. Your aim is to move away from ‘pets’ to ‘livestock’ so you invest in declarative solutions for your Infrastructure as a Service with Infrastructure as Code (IaC) tooling. If you do not have a consolidated DevOps practice at this level, bring your future operations team in to build familiarity.

### Container and Runtime Management

Initially you’ll want to focus on just building containers. One of your first steps will be to add container builds to your CI for your application. You’ll also want to adopt a container registry for your images and you’ll need to consider versioning and tagging so that you can ensure you know exactly what code is in use.

### Application Patterns and Refactoring

Start with a canonical microservice application if you can and confirm that it runs and that people are familiar with it. Attempt to start with a microservice application on your cloud native journey if you can. You can try an existing or monolithic application if this makes sense, as this will flush out tooling and dependencies you'll have for your journey to cloud native, such as kubectl, network connectivity and other topics.

Your business needs to review microservice patterns and architecture and look to understand the specifics for your applications. Non-functional requirements such as latency, resilience, scaling and third party tooling should definitely be considered. If you're transforming a monolith, this may impose significant redesign on the application as existing needs may not have the technical resources available. Consider your state management, as refactoring a monolith may require effort here. Try to ensure that the knowledge stays with the code, so make sure an existing developer familiar with the code participates in its migration to the cloud. Minimize divergence between cloud and your existing estate. This exercise will ensure all understand that it's a commitment to move to cloud native.

### Application Release and Operations

Managing a cluster with Infrastructure as Code (IaC) is different to managing application release and deployment, however many of the same techniques and tools will be common to both.
When starting with Kubernetes, it is important that you start out with as much hands-on experience as possible. Initially you’ll be doing ad-hoc deployments with kubectl and kustomize.

### Security and Policy

Start building your secured CI-CD pipeline if you don’t have one already and don’t forget that what you are doing today with VMs will end up quite different in the future.

### Testing and Issue Detection

When just starting out, much of your testing will be conducted manually on your business application that you’ve identified as your initial production candidate. With Kubernetes you’ll be focussing on your general network connectivity, and ensuring you’re able to deploy your applications. You will have smoke tests, and UAT testing.

