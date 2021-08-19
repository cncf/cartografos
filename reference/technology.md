# Cloud Native Maturity Model - Technology

## Navigation

The Cloud Native Maturity Model is composed of five separate documents - the [Prologue](./prologue.md) and the four key reference documents:

* [People](./people.md)  
* [Process](./process.md)  
* [Policy](./policy.md)  
* [Technology](./technology.md)

## Introduction

The Cloud Native Maturity Model covers four major dimensions - People, Process, Policy and Technology. This paper addresses technology - the practical tooling that makes up cloud native applications, platforms, and infrastructure. As well as referring to specific technologies, this paper aims to show the stages you may go through as you move from starting out all the way through to cloud native excellence.

This paper illustrates just one path - but all journeys differ. This is absolutely as it should be, as organizations all start out at different points and have different destinations (business outcomes). Different locations, sizes, starting points (greenfield or long established), regulatory environments, and of course people, all influence the cloud native journey.  

The technology section of the Cloud Native Maturity Model is not exhaustive. We would love contributions to ensure the model is robust and useful for all users.

## The Technology Overview

We anticipate that you already have knowledge, experience and perhaps access to infrastructure such as virtual machines. You’ll likely have some baseline security components such as firewalls, SIEM for security events and logging; a security concept that likely lends itself to RBAC, and some identity and access management tooling such as LDAP or Active Directory directories.  

Most importantly, we anticipate you’ll have a reasonable understanding of why you want to adopt cloud native technology i.e. your expected business outcomes. Clarity on why you wish to undertake this journey to achieving full cloud native adoption is your largest asset.
At a high level, the key steps in your cloud native journey will look something like this:

* Level 1: You’ll have your initial experimentation and adoption of Kubernetes. You’ll start with relatively basic tools and technology. You’ll assess your existing toolset to see how they fit within the new landscape (what plays well with cloud native, and what doesn’t?). You’ll have limited automation, but don’t worry, it’s coming! Your focus is on getting the baseline technology implemented, and you won’t be in production yet.

* Level 2: This marks your first step into production. You’ve worked hard to build your foundation in Level 1, and now you are moving to production.  You might have started with something relatively small and simple, but this leap to production has certainly required you to address some significant steps.
You’ll probably have had to incorporate monitoring and observability into your workloads. You’ll have brought Prometheus in and started monitoring your clusters for standard metrics such as RAM, CPU etc.  
While you might be starting to evaluate application tracing, don’t worry about it too much if you have started to gather core metrics.
Your focus here is on getting an application running in production and having enough to support it.

* Level 3: Here you start to scale. Your suite of tools is more standardized. You're getting your release tooling, secrets management and policy tooling in place. You’re also starting to get a level of buy-in across your organization, which is helping to propel you forward. This is where you will be running the largest number of tools as you will be in the thick of evaluating, implementing, and running in production.

* Level 4: You’ve got full control over your environment, and you’ve built your confidence, with rapid adoption of cloud native patterns for new applications and platforms. You’ve also gained organizational commitment to cloud native and this is adding to your momenting. You’re starting to feel like you’ve “crossed the chasm.”

* Level 5: Your investment is now focused on automation in functional and non-functional areas such as scanning, policy, security and testing. You’ve got operators doing your operations for you and you’re fully automated.

## Infrastructure

* Level 1: You are building your cloud infrastructure either on-prem or off. It will pay dividends to consider early your supporting technology such as your network, firewalls and IAM, access controls and policies (and if you need to change them).  Many topics will come out of your initial experimentation with Kubernetes, so ensure you keep track of these - they are the ‘breadcrumbs’ you will follow as you move towards cloud native. This will include RBAC policies, load balancer and/or ingress configuration, cluster dashboards, privileged access (or lack thereof!) and container logging.

* Level 2: Because production is your goal, you’ve built Kubernetes clusters for production. Your aim is to move away from ‘pets’ to ‘livestock’ so you invest in declarative solutions for your Infrastructure as a Service with Infrastructure as Code (IaC) tooling such as Terraform, Pulumi etc.

* Level 3: As part of building confidence in your cloud infrastructure, you need to gain visibility into what your infrastructure is doing. Developing your monitoring, alerting and resource usage capabilities is going to be your focus. An important consideration here is that where previously you may have considered machine-specific properties such as cpu, ram etc, you’ll also want to factor in cluster metrics also. Additionally, you’ll replace components when they fail rather than spending time remediating issues in production. This builds on Level two.

* Level 4: Kubernetes and its API has become extremely familiar to you. With your infrastructure and IaC  tooling, you’ll likely find yourself investigating ClusterAPI and using that for deploying and managing the lifecycle of your clusters. You may also look at the CNCF project Crossplane.

* Level 5: Here you are managing your complete infrastructure lifecycle through software and tooling. Builds, upgrades, decommissioning is all taking place through code.

## Application Patterns and Refactoring

Start with a canonical microservice application if you can and confirm that it runs and that people are familiar with it. Attempt to start with a microservice application on your cloud native journey if you can. You can try an existing or monolithic application if this makes sense, as this will flush out tooling and dependencies you'll have for your journey to cloud native, such as kubectl, network connectivity and other topics.

Here is a working model for the microservices path. You may adapt this to your model.

* Level 1: Your business needs to review microservice patterns and architecture and look to understand the specifics for your applications. Non-functional requirements such as latency, resilience, scaling and third party tooling should definitely be considered. If you're transforming a monolith, this may impose significant redesign on the application as existing needs may not have the technical resources available.  Try to ensure that the knowledge stays with the code, so make sure an existing developer familiar with the code participates in its migration to the cloud.  Minimize divergence between cloud and your existing estate. This exercise will ensure all understand that it's a commitment to move to cloud native.

* Level 2: You're in production, with your first APIs exposed. Consider developing a “microservices first” framework particularly if your first choice is always a microservices approach. If not, consider moving applications suitable for lift and shift or don't migrate the app until later.

* Level 3: Culturally, your organization has started to think about services rather than “servers”.  Microservices are embraced within the organization and are now used by default where appropriate.

* Level 4: Microservices have become the preferred pattern for applications. The use of APIs is expanding within the organization, and other internal systems may be exposed and consumed, and they are available for general consumption, open across the organization via a service mesh. The organization becomes data-centric and API-centric, and data can be more easily consumed.

* Level 5: Unless applications have specific requirements, such as extremely low latency, new greenfield applications are cloud native. You’ll look to onboard your existing portfolio of applications to your cloud native platform using your proven process. You’ll see now that your application matches your platform strengths and capabilities.

## Container and Runtime Management

* Level 1: Initially you’ll want to focus on just building containers. One of your first steps will be to add container builds to your CI for your application. You’ll also want to adopt a container registry such as Harbor for your images and you’ll need to consider versioning and tagging so that you can ensure you know exactly what code is in use.

* Level 2: You’re working in production now. You will experiment with tooling to augment the basics in production to help with security, policy management, workload misconfigurations, resource requests and limits.

* Level 3: Whereas in level 2 you’ve been experimenting, in level 3, as you increase your workload, and as you scale, you need consistent tooling across clusters to gain continuous visibility into your Kubernetes clusters. This should include automatic scanning and having runtime observability of what is occurring within your containers and your cluster. CNCF projects such as Falco, Kyverno, and OPA are good options here. You will have alerting and dashboards in place.

* Level 4: With your sources of information you've gained from level three, your goal is to further integrate your data sources and gain visibility along with alerting. This closes the feedback loop on runtime and operations and allows you to respond quickly to abnormal events.

* Level 5: You’re now automating the response to events, and you have all your security data in one central repository. The platform is able to respond to events

## Application Release and Operations

* Level 1: When starting with Kubernetes, it is important that you start out with as much hands-on experience as possible. Initially you’ll be doing ad-hoc deployments with kubectl and kustomize.

* Level 2: For your initial steps into production, you’ll be using Jenkins, kubectl and kustomize to potentially deploy your first smaller applications. It’s really important by now that you are writing YAML and developing your key skills with it. Developers and operations engineers will be using it as part of their daily business.

* Level 3: Because consistency is important, you may be starting to write Helm Charts for your application releases. You may also be starting to take your first steps into GitOps with Flux and Argo, introducing controllers to manage your release and operations.

* Level 4: Not only are you using GitOps operators for production, but you may also be using them for development and test purposes. You’ll be expecting most of your software to be packaged correctly with Helm with the feedback loop being closed as quickly as possible.

* Level 5: You’re now in full production with GitOps operators and controls, and your release and operations workflows reside within Git.

## Testing and Issue Detection

* Level 1: When just starting out, much of your testing will be conducted manually on your business application that you’ve identified as your initial production candidate.  With Kubernetes you’ll be focussing on your network connectivity and your ingress, and load balancer configuration, and ensuring you’re able to deploy your applications.  You will have smoke tests, and UAT testing.

* Level 2: Now that you are into production, you’ll be experimenting with tooling to help with security, policy management, workload misconfigurations, resource requests and limits.

* Level 3: On the basis of your experiments in the previous level, you’ll be implementing this in production, and including good alerting and good dashboards.  

* Level 4: Having built up a corpus of issues, you’ll want to work your way through them, ideally fixing or tuning. Some issue remediation may require adjusting your policy-as-code or components of your infrastructure-as-code, as well as your application. Issues may relate to more than one application so you will aggregate across applications to determine trends. These may relate to bugs such as memory leaks, as well as security or policy issues. Your remediation may be to fix them at source, ideally as ‘far left’ as possible, or otherwise building automation capable of fixing them when they occur, and tuning it over time.

* Level 5: Here we further optimize the automation used in responses to issues by working to prevent mistakes from entering production in the first place.

## Security and Policy

* Level 1: Start building your secured CI-CD pipeline if you don’t have one already and don’t forget that what you are doing today with VMs will end up quite different in the future.

* Level 2: Ensure that your development and operations groups are following good practice with secrets.  Because you are in production, you will want to ensure that you have encryption (TLS) as well and authentication and authorization addressed.

* Level 3: It’s now time to step up and automate your deployment guardrails and security best practices with policy as code Kyverno and Open Policy Agent are good options here.

* Level 4: Here you can attempt  dry-runs of your policy against production in case you haven’t don’t this already. You’ll continue to tune your policies in production.

* Level 5: Here you will have ongoing optimization and adjustment in line with new requirements, aligning with the ongoing threat environment. Exceptions to policy are both minimized, and are formally controlled.
