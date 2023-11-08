---
title: Level 3 - Scale
description: Your competency is growing and you are defining processes for scale.
---

## <i class="fas fa-building"></i> Business Outcomes

Level three, scale, is the **“Messy Middle.”** Your organization - both business and technology - has bought into cloud native. You are seeing business goals achieved. You’ve resolved common challenges most organizations face, you understand how things are happening and are no longer spending time on what’s already been discovered/created/learnined. You’ve also made changes to people, process and technology. You’ll have repeatable patterns in place.

While this all sounds great, this is the messy middle because while people are comfortable with cloud native, things are happening much faster and there are new requirements emerging. Teams are adopting new technologies to support your business goals.

But with scale comes new requirements. You’ll have requests for new tooling to meet security, compliance, and availability requirements. You may have several teams working with different tools. There will be a proliferation of tooling - some of it from existing or legacy infrastructure and systems, some of it dating from level one, and level two, and new tooling as new tools are introduced to add functionality or capabilities that the initial tool choices may not necessarily have had. This is the time where there will be the most sprawl.  Furthermore, there may also be significant inefficiency where, for example, incorrectly sized platforms are being deployed, further driving up cost. All of this will need to be worked through and the business needs to understand that with scale can come complexity that the technology team needs to work through.

For example, at level three there may be multiple logging systems in place collecting audit events for archiving - one for existing platforms and one for new cloud native platforms. These will eventually be consolidated, along with the potential merging and archiving of duplicate data. It is at this point you may become familiar with the concept of “technical debt.” This is where short term actions are taken to get a new feature or service shipped, but that results in future rework. Time and labor will need to be expended whether a task is fully completed with a strategic solution, or a short term tactical solution needing rework, so do recognize that a short term fix now will need to have someone go back and tidy up later on.

Either way, don’t give up in the messy middle. While  you might have some applications that are running beautifully, not all may. The ones that are successful need to be used to demonstrate what can be achieved. Keep driving these forward to serve as ‘lighthouses’ for what is possible within your company. Small organizations might swim through level three, while large enterprise organizations with lots of heritage and legacy, might be here for years.

While there is a dedicated people section within scale, at level three the business needs to recognize how teams must evolve. As cloud native scales beyond a few projects, apps or services, more people will be onboarded to the new ways of working. The business should expect some resistance from users slow to accept cloud native. This is a journey that the business needs to expect, but also to bring users along the ride early so that when you get to level three, teams aren’t surprised. Training should be done as early as possible across the organization showing positive outcomes of the experimentation phase (level one) and migration phase (level two) for some applications. You don’t want cloud native to be viewed as an obstacle to work and you don’t want resistant users to become a hindrance to adoption.

The business needs to encourage ways to help people to learn the technology, process and policies so that you can achieve business goals. The organization needs to safeguard the leaders i.e. the people who have spearheaded the cloud native movement while encouraging others to onboard and become experts.

### Cost

As you scale your cloud native infrastructure, you’ll now start to scale down your legacy system. This is where your costs will start to even out and/or reduce. The chart below shows how you would expect to see your costs change over time.

![cloud native vs legacy cost](/images/cloud-native-vs-legacy-cost.svg)

At this level you’ll also, particularly in the case of a migration to public cloud from traditional on-premise or co-located systems, see a change in the types of costs faced by the organization.  OPEX expenses will have increased, but CAPEX such as fixed assets and associated depreciation, as well as long term data center contracts, may be reduced or come to an end.  The financial benefits of a reduced on-premise footprint should be becoming apparent.

When cost issues occur in the ‘messy middle’ which are particularly urgent, for example a proliferation of Kubernetes clusters rather than a consolidation onto a fewer number of clusters through more advanced resource usage patterns, maintain a strategy of working to resolve the issue and consider relevant options, rather than abandoning the transition to cloud native. Your technical team will likely have a solution but they may need to invest time to realize gains. They will also be addressing this as part of level four.


## <i class="fas fa-users"></i> People

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

## <i class="fas fa-cogs"></i> Process

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

## <i class="fas fa-edit"></i> Policy

### Policy Overview

You will implement policy-as-code and build this into your CI pipeline.

### Policy Creation

Create policies based on metrics refined around security, efficiency and reliability.

### Compliance

Policy compliance and auditing carried out through automated means on Kubernetes. This will likely include initial development of policy-as-code.

## <i class="fas fa-server"></i> Technology

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
