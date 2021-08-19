# Cloud Native Maturity Model - Process

## Navigation

The Cloud Native Maturity Model is composed of five separate documents - the [Prologue](./prologue.md) and the four key reference documents:

* [People](./people.md)  
* [Process](./process.md)  
* [Policy](./policy.md)  
* [Technology](./technology.md)

## Introduction

The Cloud Native Maturity Model covers four major dimensions - People, Process, Policy and Technology. This paper addresses process. Your process will affect your cloud native footprint, cluster topology and sizing. It will support your CI/CD maturity and help to improve your team's ability to ship applications faster.

As you start your transformation, you will lack process and consistency across implementations. However, that will change over time as you develop and document your processes and capability. Documentation should be close to code and potentially machine based. By the time you are achieving maturity, you will have a consistent and mature process with a template-based approach, and you will actively revisit your standards, identify configuration drift and adjust standards based on business requirements.

Process enables repeatability. In your ephemeral environment, you need to ensure that the processes implemented can be repeated across teams and clusters. This is core to your process implementation.

* Level 1: You will map application requirements, both functional (application features and code) and non-functional, such as performance, capacity, and availability, and define how your organization will scale. Feedback will be manual such as by Slack, email, and phone, and you’ll also remediate manually also.  You will start to implement repeatability by defining your Git workflow. Platform and technology lifecycle and updates, particularly security updates, need to be applied on a regular basis as vulnerable systems pose specific risks.  You will likely be applying these updates by hand on an adhoc basis, or using update systems included in distributions.

* Level 2: You’ll focus on production promotion of basic applications. This includes being well established with Git and CI. You are also instituting structured build and deployment processes that exhibit the qualities of a cloud and container native CI/CD system.

* Level 3: You will implement standardization across the organization with the benefit of improving onboarding and expanding your cloud native footprint and awareness. You will create a feedback loop. You will invest in repeatability. Do you have the tools in place that are accessible to everyone? Do you have Git services? Have you implemented workspace collaboration to save time, labor or avoid duplication? Finally, what is your process for measuring resource usage? In level three, you should be measuring your container usage, CPU and memory (runtime and uptime). Automation and processes associated with software release will also be extended to platforms. Lifecycle operations such as upgrades and patching, particularly CVEs and critical updates will benefit from further automation and the introduction of Infrastructure-as-code technologies.

* Level 4: The governance model in place will support DevSecOps. You have guardrails in place to support agile software development. You will establish an application services library. You will also set policy around container usage for example auto-scaling policies or HPC.

* Level 5: Achieving process maturity will see you build design capabilities for cloud native. You’ll also automate responses by using monitoring failures to restart or manage problematic and failing resources. Resource usage data will help you optimize spend and your process will include providing the business cost analysis.

## Audit and Logs

Your process will include logging and auditing. This can be based on internal requirements or support your compliance mandates.  

* Level 1: Manual log scraping is likely ad-hoc and you may not have a central logging point or SIEM.

* Level 2: Spend time defining log aggregation.

* Level 3: Start to audit and implement initial alerts. Filter noise.

* Level 4: Audit and alerts become mainstream and are made mandatory across applications.

* Level 5: You are enforcing audits.

## CI/CD

Central to your cloud native transformation is the adoption of CI/CD. CI/CD helps you build, test and deploy applications based on modern software development practices. Your CI/CD process will mature over time.

* Level 1: If you do CI/CD, you need to transform this into your cloud native environment. That includes taking existing best practices and building upon them.

* Level 2: For your application, you will institute structured build and deployment processes that exhibit the qualities of a cloud and container native CI/CD system.

* Level 3: You are implementing a center of excellence around your CI/CD process.

* Level 4: You will measure your release velocity and cadence to make improvements.

* Level 5: Achieving maturity ensures you can demonstrate the benefit of your CI/CD process to the organization. You’ll be able to clearly see an increase in velocity, continuous deployment speed and see the effect on your business. For example, you will ship new features faster.

## Change Control

Change control will need to be implemented to control your deployments.

* Level 1: You have no change control process in place. Instead changes are performed based on ad-hoc requests.

* Level 2: Here you develop a fundamental understanding of the workflow from source control management (scm) to deployment and have access to merge/tag commits in scm to trigger deployments.

* Level 3: Your code quality is improving as measured with automated tooling and you are seeing CI and test success frequently.

* Level 4: You have continuous delivery, but no continuous deployment to production - you still have a gate to production that requires operator approval.  

* Level 5: You now have quality engineering (QE) capability. That means you have quality guardrails in place, continuous deployment to production with only a failed automated test preventing an update being automatically released to production.  You are seeing fewer defects, hotfixes and bug fixes being released. You now have best practices in place and have removed human access from production in favor of service accounts. You are also using monitoring failures to restart or manage problematic and failing resources.

## Security

Incorporating security tooling and practices into your cloud native environment, whether through a practice or a process, as early as possible is crucial to keeping your cloud native environment secure. We often use the term ‘shift left’ to refer to bringing a practice, whether relating to testing or security, into a process as early as possible. Security is covered in all sections of the Cloud Native Maturity Model and each section with People, Process, Policy and Technology can be combined to support the security team as they seek to mature the organization’s cloud native security.

* Level 1: Take action: your security journey starts here. Consider security in all aspects of implementation and make it a first class citizen.

* Level 2: Build security into your CI process including container scanning and configuration scanning.

* Level 3: Implement automatic continuous scanning to flag misconfigurations or security issues.

* Level 4: Ensure security remediation is automated and/or identified automatically with remediation advice.

* Level 5: The software supply chain is secured, with reproducible builds and software bills of materials providing insight into code and dependencies, with clear code provenance and secured release pipelines.You've shifted security left. You are preserving security by continuously monitoring Kubernetes for security and vulnerabilities.
