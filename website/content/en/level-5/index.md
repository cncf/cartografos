---
title: Level 5 - Adapt
weight: 5
description: You are revisiting decisions made earlier and monitoring applications and infrastructure for optimization.
---

## <i class="fas fa-building"></i> Business Outcomes

When reaching level five of the Cloud Native Maturity Model, the business has trust and confidence in the technology team i.e. they can sleep at night. There are no nasty surprises from auditors, no outages in the same way legacy systems faced. Your team no longer faces jarring and stressful pivots. You can look to the future without feeling anxiety about the current state.

Essentially level five is utopia. You’ve met your business goals. You’ve invested the time in a platform that allows your teams to be flexible and adapt to businesses ever-evolving needs.

### **Cost**

IT spend has become more predictable as FinOps and policies have helped to avoid unforeseen circumstances and events. Both the business and technology teams can plot highs and lows throughout the year to make budget predictions and forecasts.

## <i class="fas fa-users"></i> People

### Organizational Change
At full maturity, the organization is fully committed to cloud native, seamlessly integrating culture, technology, and processes for maximum efficiency. It rapidly adopts and discards elements based on their value, ensuring continuous optimization.

### Teams and Decentralization
At level 5, teams have seamless access to the tools and capabilities they need to deliver business value without friction. Developers focus solely on business logic, free from platform and infrastructure concerns, while platform engineers ensure on-demand infrastructure availability. At this stage, the organization operates at peak efficiency—services are consumed without facilitation, teams remain lean, and both the technical ecosystem and organizational structure are right-sized. Tech debt is continuously managed within each domain, preventing accumulation. Efficiency drives every decision, ensuring the right resources are in place without compromising business needs (i.e. not downsizing to the detriment of the business). 

### Upskilling

At level 5, your organization is now composed of highly capable individuals and teams who fully leverage cloud native capabilities, engaging effectively across technical, architectural, and business domains. Teams can swiftly identify opportunities to drive business value and reduce technical debt, fostering a culture of continuous learning and innovation.

As a learning organization, you stay ahead of trends, integrating both mature CNCF projects and emerging sandbox technologies. Skilled engineers contribute to open-source projects, creating opportunities for outreach and deeper industry engagement.

Teams are small but diverse, equipped with broad expertise to mitigate key-person risk and ensure stability. Strong communication protocols and a robust professional development pipeline sustain long-term growth, enabling teams to adapt, collaborate, and innovate effectively.

### Security
Your team operates at peak efficiency, with the right people, tools, and policies ensuring workloads and teams can handle requests safely and seamlessly. You rely on experts who can articulate what must be done, how to do it, and what’s possible. Clear, written guidelines support well-defined procedures, carried out by skilled engineers. Threat detection is embedded, whether preventative or retrospective, while security roles focus on policy development or technical execution. The organization actively contributes to public policy and open-source tooling, reinforcing its leadership in security and best practices.

### Culture
At this level, a culture of ease, trust, and respect prevails. Burnout is no longer a dominant topic. Conflicts and disagreements are addressed quickly and effectively, with a shared confidence that everyone is working toward the same goals. This culture is a key driver of efficiency, enabling continuous improvement and innovation without friction.

### AI
While we are attempting to be all encompassing in this model, the Cartografos Working Group would like to acknowledge that level 5 AI maturity is outside of our remit. AI is changing rapidly and what may be level 5 today might not be tomorrow. We are excited to see how AI will impact people’s skills. We welcome any advice on this topic. 

### CNCF Certifications

For those who reach level 5 maturity, people may want to look into the Kubestronaut program. 

[Kubestronaut Program](https://www.cncf.io/training/kubestronaut/)

* Individuals who have successfully passed every CNCF’s Kubernetes certifications – CKA, CKAD, CKS, KCNA, KCSA.

## <i class="fas fa-cogs"></i> Process

### Audit and Logs
At maturity, you have a clear understanding of the value of the data you retain. You can now determine what should be summarized for long-term retention and what can be safely deleted. Compliance obligations may also require the disposal of certain data after a set period. Consider leveraging logging data as a source for machine learning and AI to uncover new insights and improve decision-making.

### Software Integration and Release
Level 5: You are actively exploring and investing in innovative strategies—including potential system refactoring, infrastructure optimizations, and runtime or programming language improvements—to enhance both the safety and speed of software integration, testing, and deployment. With a streamlined release process, successful deployments happen efficiently, enabling the business to adapt quickly to evolving market conditions and stay ahead of the competition.

### Security
Reaching level 5 maturity means the software supply chain is secured, with reproducible builds and software bills of materials providing insight into code and dependencies, with clear code provenance and secured release pipelines.You've shifted security left. You are preserving security by continuously monitoring Kubernetes for security and vulnerabilities.

## <i class="fas fa-edit"></i> Policy

### Policy Creation

At stage 5, while still drawing from frameworks like CIS and NIST, your organization should also focus on giving back by actively contributing policies to the open source community. Regulators will likely seek input from Level 5 organizations to shape policy, making your expertise highly valuable in these discussions. Your deep understanding of what works—and what doesn’t—positions you as a key partner in policy formulation.  

Leverage multiple data sources, including user activity, log data, internal datasets, and governmental guidelines, to drive informed policy decisions. With your advanced capabilities, you can share insights through case studies, thought leadership, and open source contributions, helping to shape the broader industry landscape.

### Implementation and Compliance

Compliance never ends\! Strengthen your feedback loop with stakeholders and leverage advanced machine learning, ai and other tools to establish baselines, detect anomalies, and ensure visibility across large volumes of compliance data. At this stage, you may contribute to policy development by participating in organizations like NIST, the Linux Foundation, or industry-specific policy groups, providing valuable insights to the broader community.  
  Your technical implementations, security strategies, and defense posture can now be shared more openly than ever before. By contributing your expertise, you help the cloud native community navigate an increasingly complex and volatile landscape.

### AI

At the maturity stage is characterized by the full automation and optimization of policy adherence and the integration of AI into all operational aspects of cloud native environments, leading to peak efficiency and sustainability.  Internally, within the cloud native environment, Kubernetes controllers integrate with a natural language interface using LLMs, understanding logs, managing resource usage and many other tasks.  Full data provenance and lineage is automatically captured and maintained, ensuring transparency and accountability.   In terms of sustainability, there is continuous optimization of resource scheduling \- not just for performance and cost, but also for power conservation, ensuring maximum energy efficiency and reduced carbon footprint.  Finally you see a future state where policies for responsible AI and ethical use are not merely applied but autonomously monitored, adapted and enforced by the AI systems themselves, in alignment with the “Safety by Design” philosophy at an architectural level.

## <i class="fas fa-server"></i> Technology

### Architecture and Solution Design
Everything is self-service and fully automated. Environments are right-sized, secured, cost-effective, and provisioned or decommissioned on demand.  
  Developers have access to a mature portfolio of capabilities and services that meet all functional and non-functional requirements. Automation includes AI/ML for detecting issues, suggesting optimizations, and generating pull requests for rapid review. It is easy and safe for developers to get the capabilities they need while being guided toward the right solutions.  
  Architectural decisions are made with full awareness of their implications and impacts. Design reviews take the form of pull requests, with the entire application stack—including IaC and Kubernetes manifests—rendered in code, accelerating delivery.

### Platforms and Infrastructure
At this stage, your entire infrastructure lifecycle—provisioning, upgrades, and decommissioning—is fully managed through software and codified processes. Every infrastructure change is made via code, enabling repeatability, auditability, and rapid iteration.  
  You are maximizing efficiency and minimizing technical debt. Infrastructure is highly flexible, cost-optimized, and aligned with business needs, supported by robust self-service interfaces that empower teams without compromising control. FinOps practices are well-integrated, ensuring that both resource utilization and cost are continuously optimized.  
  Tight GitOps-based control loops are in place across the entire infrastructure, eliminating configuration drift and enforcing consistency. Everything is version-controlled, declaratively defined, and managed as part of a cohesive system.  
  Shared or pooled costs are minimized or fully allocated. You have clear, effective mechanisms for cost management and chargeback, ensuring that infrastructure expenses are transparent and aligned with team or business unit usage.

### Application Patterns and Refactoring
At this level, all new greenfield applications are developed with a cloud native-first approach—unless specific requirements (such as ultra-low latency) dictate otherwise. You’re actively onboarding your existing application portfolio to the platform using proven, repeatable processes.  
  Applications are now fully aligned with platform strengths and capabilities. You’ve arrived at the “right tool for the job” through an organic, Darwinian evolution—where scalable, resilient services have emerged as the standard. Infrastructure providers no longer constrain your design decisions.  
  Mature, well-matched application patterns are in place, supported by robust self-service APIs across both the platform and cloud native tooling. These APIs offer a wide range of capabilities that enable teams to operate efficiently at scale.  
  At this level, you're harnessing the full power of cloud native and the elasticity of cloud infrastructure. For many organizations, this ability to scale seamlessly can have a direct and significant impact on cash flow, operational efficiency, and long-term viability.

### Container and Runtime Management

At the highest level of maturity, your platform responds to events automatically. All security and operational data is centralized, allowing for coordinated and efficient action. The system is no longer reactive but proactive. Automated event responses, centralized observability, and full lifecycle automation make the container runtime environment robust, scalable, and secure.

### Application Release and Operations
Code is released at the highest level of abstraction and with [idempotence](https://en.wikipedia.org/wiki/Idempotence) from the underlying infrastructure, enabling maximum velocity and minimal vendor lock-in. You are effectively managing controlling artifacts and addressing technical debt.  
    
  Continuous deployment to production is now in place, supported by a fast, controlled, and automated release pipeline.

### Testing and Issue Detection

At this level, both platforms and applications recover automatically and immediately. Restoration to a known good state is always possible and predictable. You have strong test coverage for both functionality and quality of service, and testing occurs as early in the development lifecycle as possible. Immutability and idempotency principles ensure systems can consistently return to a reliable state.

### Security and Policy
Security policies are continuously optimized in response to evolving threats and business requirements. Exceptions are minimized and formally controlled. You are working toward compliance with [SLSA Build Level 3](https://slsa.dev/spec/v1.1/levels#build-l3-hardened-builds).

### Cost Efficiency, Resource Usage and Sustainability
You’ve reached peak efficiency. Resource usage is optimized, FinOps reporting is mature, and your systems are highly sustainable—leveraging efficient chip architectures, immediate responsiveness, and minimal overhead. Wasted resources are minimized, and workloads are right-sized and deployed on the most appropriate platforms in the most efficient regions.

### AI
 In line with the overall drive towards efficiency, the AI lifecycle is fully automated and highly optimized through cloud native technologies, and is also deeply integrated into the operational fabric of the cloud native environment, with the organization achieving peak efficiency and sustainability for its AI workloads.  Cloud native supports this through full infrastructure automation and continuous deployment for AI.  AI itself is used for operational tasks, and there is optimised resource usage with full FinOps capabilities.  Promoting environmental sustainability and developing energy-efficient AI models is crucial at this level.
