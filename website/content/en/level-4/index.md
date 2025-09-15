---
title: Level 4 - Improve
description: You are improving security, policy and governance across your environment.
---

## <i class="fas fa-building"></i> Business Outcomes

At level four, the business should have complete alignment with technology on how cloud native has achieved goals. Here you’ll be moving remaining applications, only holding onto legacy applications if this is a strong compliance requirement. You also might let legacy applications age out as you build its replacement.

The business should see that the investment in cloud native has helped reduce traditional support outages. There has been a change in the profile of how teams are staffed based on new skill sets.

Overall, at level four, the technology team will spend more time on forward looking innovation vs. support. Because of the software development processes put in place for cloud native, the business can expect fewer disruptive (side) projects for upgrades, professional services or additional staff requirements. The teams have more time to focus on strategic initiatives and adding customer services/features, than having to spend cycles on maintenance.

At level four, the business should expect to clean up the messy middle. There should be a consolidation of vendors and tooling to streamline the efficiency of the team and also of money spent externally. This consolidation will help to reduce risk as the business benefits from less management of patching/fixing and maintenance.

The technology team will have a much clearer understanding of their requirements from third parties vs. in earlier levels where they might have procured more than needed. The team will be able to assess what software and tools they have and select the best tool that the team can maintain, scale and ensure proper implementation. While there may be a cost reduction via procurement of software, there may also be a give and take of spend in one area over another.

The business will have a clearer understanding of risk at this stage. Policy enforcement from business goals down will be turned into automated scanning and remediation. The technology team will be able to demonstrate compliance.

At level four, the technology is not as important as the business output. The improvements made should be focused on getting to business value faster by reducing repeatable processes.

### **Cost**

In level 4, you’ll want to focus your team on cloud cost optimization. How can you improve your infrastructure to reduce cost and how can you demonstrate this to the business. The finance team will not want to understand per cluster costs, but instead how you’ve made changes to reduce costs or why you need more capacity. Use tools that help you demonstrate cloud and Kubernetes cost optimization.

## <i class="fas fa-users"></i> People

### Organizational Change
You're now transitioning to platforms and value streams at level 4, with services efficiently delegated to product teams. Developers can focus on product code aligned with business goals, seamlessly consuming necessary services through efficient interfaces—eliminating time spent on platform and infrastructure tasks outside their core responsibilities.

### Teams and Decentralization
At Level 4, the organization focuses on structuring its platform to centrally expose and integrate services for seamless developer consumption. The platform team consolidates previously fragmented capabilities into standardized, self-service interfaces accessible via portals, APIs, and CLIs. Developers move beyond email-based or Slack requests, instead consuming APIs and curated resources, shifting away from a consulting-based support model. This evolution embeds organizational policies and processes directly into the platform. Value Stream teams can now leverage platform capabilities with minimal handovers, enabling developers to request resources and services programmatically while staying focused on business logic. 

### Upskilling

At level 4, cloud-native adoption is now deeply ingrained across teams, fostering a culture of shared knowledge and continuous learning. Developers, platform engineers, and architects are actively refining processes, selecting tools that align with organizational policies, and proactively delivering business value. Senior engineers and architects play a crucial role in guiding teams as they expand Kubernetes and integrate cloud native technologies to meet specific needs.

At this stage, developers evolve beyond writing code—they become problem-solvers, whether building applications, optimizing platforms, or extending infrastructure. A new generation of senior engineers emerges, comfortable with cloud native complexities and capable of developing operators, custom resource management, and automation frameworks. The shift from reactive problem-solving to strategic, proactive decision-making empowers teams to innovate with confidence.

As responsibilities grow, technical leadership is essential at every level. Managers and senior decision-makers must develop technical fluency to evaluate and approve solutions effectively. With layers of abstraction and self-service platforms, teams can work efficiently within well-defined guardrails, ensuring both autonomy and alignment with business goals.  This has the effect also of allowing junior staff to become much more productive, much more quickly as they are able to direct their attention to functional development and engineering without having to be caught up in environment setup and other concerns not directly concerned with their main responsibilities.

A further mark of maturity at Level 4 is the quality of documentation.  At this level it covers all aspects of platforms as well as infrastructure, including design as well as operational documentation.  This is maintained alongside technical artefacts such as code and kept up today with appropriate archiving as features are removed and technical debt reduced.

### Security
Your team is embracing Zero Trust, shifting from default allow to default deny, ensuring access is granted case by case. This level of control is possible through integrated platform services authenticated by a single identity provider. Developers, engineers, and end users—from finance and HR to customers—experience seamless, secure access to approved capabilities, while the organization gains greater visibility and control over security and compliance.

### Culture
At level 4, your organization has crossed the cultural chasm. Cloud native is the predominant mode of operation, with traditional application patterns becoming the exception, approved only under specific business requirements. Cost-consciousness is high, and the organization focuses on balancing innovation with efficiency, aiming to be "lean but not anemic." Trust becomes a major theme, and the cultural shift is fully embraced.

### AI
During level 4, the “AI Engineer” role evolves to focus heavily on AI tooling, infrastructure and deploying AI chains and agents, indicating a deep specialization in AI-driven operations.  All personnel benefit from highly automated and intelligent systems. Administrators and site reliability engineers benefit from natural language interfaces for cluster control, which significantly lowers their learning curve for managing complex Kubernetes clusters. Skills in continuous optimization for multiple criteria (e.g., power conservation, latency) become crucial, often facilitated by AI-driven models.

### CNCF Certifications

To build a sustainable cloud native ecosystem, investing in CNCF certifications is essential. CKS becomes relevant at Level 4 to deepen security expertise.

[**Certified Kubernetes Security Specialist (CKS)**](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)

* This program provides assurance that a CKS has the skills, knowledge, and competence on a broad range of best practices for securing container-based applications and Kubernetes platforms during build, deployment and runtime. CKA certification is required to sit for this exam.

[Kubestronaut Program](https://www.cncf.io/training/kubestronaut/)

* Individuals who have successfully passed every CNCF’s Kubernetes certifications – CKA, CKAD, CKS, KCNA, KCSA.

## <i class="fas fa-cogs"></i> Process

### Audit and Logs

At level 4, your audit and alert systems are treated as essential production components and enforced across all applications. You have a defined strategy for indexing, partitioning, and managing large volumes of data, ensuring it is handled with the same level of importance as business-critical information. Regularly test your ability to respond to audit requests on short notice to maintain readiness and compliance.

### Software Integration and Release

You can now demonstrate the value of your software integration and release process to the organization, showcasing tangible improvements in velocity, deployment speed, and business impact. You may have implemented DORA metrics and will want to map those to business outcomes.  
    
With optimized delivery methods, new features ship faster, accelerating innovation. Your quality engineering (QE) capability is well-established, ensuring automated deployments to production, where only failed tests can block a release. Additionally, monitoring failures trigger automated responses, such as restarting or managing failing resources, enhancing system resilience and reliability.

### Security

Ensure security remediation is automated and/or identified automatically with remediation advice.  

## <i class="fas fa-edit"></i> Policy

### Policy Creation

At this stage of maturity, you will customize policies to align with your organization's business needs while minimizing exceptions. This will integrate business functionality and logic into your technical policy infrastructure. Over time, your organization will gain a clearer understanding of its highest risks and greatest value areas, leading to a stronger emphasis on effective classification. Earlier levels may rely on external guidance without fully aligning with internal skill set requirements, but by Level 4, this matures. There will be a well-developed ability to classify risks and a more strategic engagement with technical, operational, and business risks. Policy decisions should be actively shaped by real-world learnings. Technical edge cases arising from enforcement should inform policy evolution. Additionally, at Level 4, organizations may begin leveraging LLMs to accelerate both technical and written policy creation—while ensuring accountability remains intact.

### Implementation and Compliance

Technical and business decision-making actively drives the consolidation and standardization of technologies, moving away from arbitrary or ad-hoc choices. Policy tooling expands beyond infrastructure to include applications such as traffic proxies, service meshes, message buses, and Linux, increasing the scope of managed policies while maintaining control through declarative configurations.  
    
Key activities include applying policies to business applications or extending policy enforcement to middleware. Every enforcement gate should be backed by a business decision. Integrate policy into the software delivery lifecycle—unit test, smoke test, and integration test your policies. Treat policies as code and include them in your SDLC to ensure consistency, reliability, and compliance.

### AI

In line with the AI discussion in the technology section, we see a convergence where AI itself is used to enhance governance, security and compliance within cloud native systems, growing a symbiotic relationship.  This means, for example, considering MLOps pipelines to capture and maintain data provenance.  AI may also be at the core of your tooling to Trust and Safety, managing content and conducting scans for risks, mitigate abuse, and protect brand safety.

## <i class="fas fa-server"></i> Technology

### Architecture and Solution Design
The capability catalog becomes more refined, narrowing down to a short list of highly expressive options. You can deploy infrastructure, platforms, and applications rapidly—and decommission just as easily. Lifecycle management across infrastructure, platform, and application is in place, with a strong emphasis on automation.  

You are far more efficient in resource allocation and take advantage of placement options (e.g., deploying in Iowa instead of the West Coast to save on cost). Interfaces are clean and consistent, and applications scale effectively within your platform. Interfaces are well-defined and come in multiple forms to suit different needs, all with strong observability.  

Developer experience is excellent, with clearly defined stages, easy-to-use interfaces, and built-in guidance. The platform leads developers toward secure, compliant, and efficient designs. Policy requirements are encoded into the platform and surfaced through portals, helping developers build according to organizational standards.  

Solutions design becomes less manual. Policy is baked into the platform, and architectural consulting focuses more on refining and reviewing designs for alignment with business goals. You can spin up entire environments to test new capabilities without impacting production.  

As tribal knowledge becomes codified in the platform, it must meet the same security classification standards as the workloads it supports (e.g., usingapplying [HSM](https://en.wikipedia.org/wiki/Hardware_security_module)s with [OpenBao](https://openbao.org/) when supporting medical applications with patient data).  

### Platforms and Infrastructure
By this stage, Kubernetes and its API are second nature. You’ve matured your infrastructure practices and Infrastructure as Code (IaC) tooling, and you're likely exploring ClusterAPI to automate the deployment and full lifecycle management of your clusters.

As platform maturity increases, so does the need for refined control and governance. You’re now implementing policies across the infrastructure control plane and related controllers to ensure consistent behavior, security, and compliance at scale. 

Your deployment and operating models have been further refined, recognizing that no single approach fits every team. Earlier solutions—like namespace-as-a-service—were effective for rapid onboarding in lower-risk environments. Now, with more sophisticated needs across development and product teams, you're supporting a broader range of workloads and operator-based services such as storage, databases, messaging, and logging.

This introduces more complexity and risk with each change to your operating model. Development teams are making more demands, and your platform must be flexible without sacrificing stability. To meet this need, you’re investing in centrally maintained Infrastructure as Code templates (e.g., using [OpenTofu](https://opentofu.org/)), while still allowing for team-specific customization such as networking or other infrastructure components.

The challenge at this level is to plan and support a diverse set of workloads across the enterprise—from lightweight APIs to complex, large-scale systems with demanding functional and non-functional requirements. Flexibility, consistency, and strong governance become the pillars of your infrastructure strategy as you scale to meet the needs of a growing and diverse engineering organization.

As platform maturity increases, so does the need for refined control and governance. You’re now implementing policies across the infrastructure control plane and related controllers to ensure consistent behavior, security, and compliance at scale.

Your deployment and operating models have been further refined, recognizing that no single approach fits every team. Earlier solutions—like namespace-as-a-service—were effective for rapid onboarding in lower-risk environments. Now, with more sophisticated needs across development and product teams, you're supporting a broader range of workloads and operator-based services such as storage, databases, messaging, and logging.

This introduces more complexity and risk with each change to your operating model. Development teams are making more demands, and your platform must be flexible without sacrificing stability. To meet this need, you’re investing in centrally maintained Infrastructure as Code templates (e.g., using [OpenTofu](https://opentofu.org/)), while still allowing for team-specific customization such as networking or other infrastructure components.

The challenge at this level is to plan and support a diverse set of workloads across the enterprise—from lightweight APIs to complex, large-scale systems with demanding functional and non-functional requirements. Flexibility, consistency, and strong governance become the pillars of your infrastructure strategy as you scale to meet the needs of a growing and diverse engineering organization.

### Application Patterns and Refactoring

At this stage, cloud native [design patterns](https://en.wikipedia.org/wiki/Software_design_pattern) are formalized and shared across the organization—often documented in Git repositories or collaboration tools like Confluence. Consistency in implementation is not only visible but may now be actively enforced.

The organization strikes a balance between standardization and flexibility. While standardization is ideal for scale and maintainability, some variation remains to support the “right tool for the job” approach. This balance directly influences application architecture and development patterns.

By this point, the organization is converging on a well-defined set of tools and practices that align with both platform capabilities and business needs.

### Container and Runtime Management
By Level 4, the platform vision and architecture are clearly defined. Experiments and ad hoc tooling from Level 3 are rationalized and replaced with strategic, standardized solutions. You may still have overlapping tools in use, but now you have a better understanding of their tradeoffs and suitability. Some of this clarity results from hard lessons and suboptimal solutions adopted under pressure at earlier levels.  
    
  Technical debt from Level 3 is acknowledged, and although paying it down is difficult, it now becomes a focused effort.  

### Application Release and Operations
You are actively securing the supply chain, and policies now govern both the release pipeline and runtime state. The Kubernetes API is used not only for container orchestration but also to manage other data center components having likely been extended with [Crossplane](https://www.crossplane.io/) and other technologies.  

Organizations at this level can create and destroy production-ready clusters on demand and take advantage of beta and alpha APIs. Releases are automated, reliable, consistent, measurable, auditable, revertable, and quick. Artifacts are standardized and predictable.  

Automation—including [admission controllers](https://kubernetes.io/docs/reference/access-authn-authz/admission-controllers/)—is used to validate workloads before production release. Security and policy controllers enforce defense-in-depth strategies. Kubernetes becomes a foundational platform component, and developers begin coding against infrastructure capabilities. Tools like [Crossplane](https://www.crossplane.io/) illustrate this evolution by integrating cloud and infrastructure lifecycles directly into applications.  

### Testing and Issue Detection

At level 4, issues may now span multiple applications, requiring you to aggregate data across systems to identify trends. You’ve established consistent patterns for validating all environments—including production—and can create and destroy them with ease.

This includes platform considerations like load balancing and secret management to ensure environments feel seamless and plug-and-play. Data consistency across environment instances becomes increasingly important.

Recovery processes are now integrated into standard operations, including chaos engineering to simulate failures and validate system resilience. This helps ensure non-functional requirements like availability and fault tolerance are continuously met in practice.

### Security and Policy
At level 4, apply your security policies to production, if you haven’t already, and continue tuning them. You have implemented measures to reduce attack surfaces, such as preventing manual pod access (e.g., no shell inside pods), while providing safer alternatives with full audit trails (e.g., Falco).

You’re improving security posture by removing the need for insecure workarounds or legacy practices. At this stage, you are working toward [SLSA Build Level 2](https://slsa.dev/spec/v1.1/levels#build-l2-hosted-build-platform) compliance.

### Cost Efficiency, Resource Usage and Sustainability
You begin reporting on carbon emissions and shift focus from pure cost efficiency to include sustainability goals. This includes carbon reporting and machine right-sizing, considering both size and architecture. Cost-benefit analysis becomes more rigorous—for example, evaluating whether a workload justifies GPU usage.  
    
Developers now share responsibility for efficiency and are expected to optimize code based on the capabilities of the underlying platform and infrastructure.  

### AI
At this stage the organisation has achieved significant control over its AI operations, with mature MLOps practices and has formalized its cloud native design patterns for AI workloads.  There’s a clear understanding of the AI supply chain, and policies are actively governing its security and runtime state.  We see at this level the beginning of a symbiotic relationship where AI is used to improve cloud native systems themselves.  Projects like K8sGPT can enter the hands of operators to enhance their productivity using LLMs for processing logs.  This allows less technical users to operate complex systems.  AI can also be used to identify workload patterns and anticipate load, and optimize resource scheduling for things like power conservation, resource utilization, latency and priorities.  Best practices for the software supply chain should also be followed here.  This will also include taking advantage of capabilities such as hardware-supported Trusted Execution Environments to protect sensitive data and valuable ML models.  Security may also be enhanced by using AI itself as a ‘red team’ member for the identification of security gaps.
