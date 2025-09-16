# Cloud Native Maturity Model \- Process

## Navigation

The Cloud Native Maturity Model is composed of six separate documents \- the [Prologue](http://./prologue.md) and the five key reference documents:

* [People](http://./people.md)  
* [Process](http://./process.md)  
* [Policy](http://./policy.md)  
* [Technology](http://./technology.md)  
* [Business Outcomes](http://./business_outcomes.md)

## Introduction

The Cloud Native Maturity Model spans five key dimensions: People, Process, Policy, Technology and Business Outcomes. This paper addresses the process. Your process will affect your cloud native footprint, cluster topology and sizing. It will support your CI/CD maturity and help to improve your team's ability to ship applications faster.

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

## Audit and Logs

Your process will incorporate logging and auditing, whether to meet internal requirements or to support compliance mandates—both internal policies and external regulations.

* Level 1: Manual log scraping is likely ad hoc, with no centralized logging system or SIEM in place. Log aggregation and retention may be inconsistent or not exist across your cloud native stack, including infrastructure, platform, and application layers.  
    
* Level 2: Define a clear log aggregation strategy to ensure comprehensive logging for your production workloads. As you're now in production, capturing and managing logs is critical. Consider implementing long-term archiving to support compliance, troubleshooting, and historical analysis.  
    
* Level 3: Begin enabling audit capabilities and configuring the most critical alerts if you haven’t already. Reduce noise by filtering irrelevant data and ensuring logs are structured for easy retrieval and analysis. Focus on capturing and presenting the most business-critical insights to support informed decision-making.  
    
* Level 4: Audit and alert systems are treated as essential production components and enforced across all applications. You have a defined strategy for indexing, partitioning, and managing large volumes of data, ensuring it is handled with the same level of importance as business-critical information. Regularly test your ability to respond to audit requests on short notice to maintain readiness and compliance.  
    
* Level 5: At maturity, you have a clear understanding of the value of the data you retain. You can now determine what should be summarized for long-term retention and what can be safely deleted. Compliance obligations may also require the disposal of certain data after a set period. Consider leveraging logging data as a source for machine learning and AI to uncover new insights and improve decision-making.

## Software Integration and Release

Central to your cloud native transformation is the adoption of a software integration and release process to help you build, test and deploy applications based on modern software development practices. 

* Level 1: You may not have a formal change control process in place. Instead changes occur on an ad-hoc or informal basis. If you already use CI/CD, it’s essential to adapt and evolve it for your cloud-native environment. This means building on existing best practices while ensuring they align with cloud-native principles.  
    
* Level 2: For your application, implement structured build and deployment processes that align with cloud-native and container-native integration and release practices. Code quality is improving, as measured by automated tooling, and you are consistently achieving successful CI runs and test validations.  
    
* Level 3: You are establishing a center of excellence around your software integration and release process, focusing on measuring and improving release velocity, defect rates, and deployment cadence. While you have implemented continuous delivery, production deployments still require an approval gate.  
    
  At this stage, you are experimenting with advanced deployment strategies such as blue-green and canary releases to optimize reliability. Defects, hotfixes, and bug fixes are trending downward, reflecting improved stability. Best practices are now firmly in place, and human access to production has been eliminated in favor of GitOps operators, ensuring a more secure and automated deployment process.  
    
* Level 4: You can now demonstrate the value of your software integration and release process to the organization, showcasing tangible improvements in velocity, deployment speed, and business impact. You may have implemented DORA metrics and will want to map those to business outcomes.  
    
  With optimized delivery methods, new features ship faster, accelerating innovation. Your quality engineering (QE) capability is well-established, ensuring automated deployments to production, where only failed tests can block a release. Additionally, monitoring failures trigger automated responses, such as restarting or managing failing resources, enhancing system resilience and reliability.  
    
* Level 5: You are actively exploring and investing in innovative strategies—including potential system refactoring, infrastructure optimizations, and runtime or programming language improvements—to enhance both the safety and speed of software integration, testing, and deployment. With a streamlined release process, successful deployments happen efficiently, enabling the business to adapt quickly to evolving market conditions and stay ahead of the competition.

## Security

Integrating security tooling and best practices into your cloud native environment as early as possible is essential for maintaining a strong security posture. The concept of “shifting left” emphasizes embedding security—alongside testing and other critical practices—early in the development lifecycle. 

Security is woven throughout the Cloud Native Maturity Model, with each level playing a role in strengthening an organization's security posture. A comprehensive approach ensures security teams can drive maturity across the software supply chain, platforms, and beyond, recognizing security as a cross-cutting concern that impacts every aspect of cloud-native operations.

* Level 1: Make security a first-class citizen in every aspect of implementation. Understand the unique security challenges across your infrastructure, network, platform, applications, and code, and proactively address vulnerabilities and misconfigurations. Prioritize security from the start—building it in from the beginning is far easier than retrofitting security practices and tooling later.  
    
* Level 2: Build security into your software integration process and runtime environment including container scanning and configuration scanning. You are extending your existing policies into your cloud native ecosystem.  
    
* Level 3: Implement automatic continuous scanning to flag misconfigurations or security issues.  
    
* Level 4: Ensure security remediation is automated and/or identified automatically with remediation advice.  
    
* Level 5: The software supply chain is secured, with reproducible builds and software bills of materials providing insight into code and dependencies, with clear code provenance and secured release pipelines.You've shifted security left. You are preserving security by continuously monitoring Kubernetes for security and vulnerabilities.