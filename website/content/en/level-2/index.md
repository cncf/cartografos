---
title: Level 2 - Operate
description: The cloud native foundation is established and you are moving to production.
---

## <i class="fas fa-building"></i> Business Outcomes

At level two, you’ve experimented and made the decision to continue on the cloud native journey. Here you want to identify the projects that will uniquely benefit from cloud native. The business and technology needs to align on the project/service/application that makes the most sense to move. The decision could be focused on “where are we hurting the most” either internally or externally. While it may be easy to look at external “product or service” spend time considering internal requirements first.

Part of the decision making process should be based on seeing a return on investment (ROI). You should be moving an application that can serve as your speed boat.

*Speed boat: transform to the cloud steadily and incrementally using speed boats to accelerate adoption and achieve extreme agility.*

Moving business essential applications (i.e. production workloads) will come with trade offs so selection is key. If you choose application A for example, you may need to worry about cloud costs. If you choose application B, you’ll need to worry about compliance audits. Ensure that the decision of what applications to move first considers key non-functional requirements such as capacity, backup, DR, performance (availability) as well as any governance topics such as compliance (and audits, including relevant logging), and risks such as that to reputation through downtime or security compromise.

Whatever application is selected will force the technology team to set standards and innovate for new ways of working. The technology team will design and establish new patterns based on the business goals. The project(s) that are moved first will help establish new policy, technology, process and people changes. Be aware that the first application may require prerequisites to be implemented to fulfill specific obligations. For example, you may need to extend your current concept for identity and access management to cater for public cloud use cases. Be prepared for a cascade of activities to deliver the minimally acceptable prerequisites to get your first applications into production.

*“Organizations must develop meaningful processes for sharing information and results between technology and business units, which might mean seeking out new talent with technical expertise and passion for sharing information.”* [**CTO Summit**](https://www.cncf.io/reports/cto-summit-na-2022/)

Measurement is key as we move through business outcomes. Each KPI and OKR must map to the overall business goal. It must be documented in a language that the business can understand.

Before moving to level three \- scale \- you must demonstrate business value. Lots of organizations get stuck at level two because they cannot demonstrate how the technology has helped achieve the goal. Going through this goal mapping exercise as early as possible is vital to your cloud native journey.

### Cost

When selecting what you are moving first, you must consider how you will deal with changes in cost. You will no longer be buying server and network hardware and software directly, but instead effectively leasing or paying as you go for capacity. While this brings with it flexibility, it will also require some work with cloud providers to get discounts. Ensure your technology team is in lock-step with finance to plan accordingly. The business should continuously ask for ways of optimizing infrastructure to save money and/or for evidence as to why more or less capacity is needed. Cost control really does become everyone’s responsibility as real money exits the organization on a regular basis.

## <i class="fas fa-users"></i> People

### Organizational Change
At level two, organizational change is underway. You’ll identify structural barriers, such as siloed teams that slow delivery. To improve agility, you’ll establish project teams, adopt agile methodologies, and explore frameworks like Team Topologies and value streams for faster feedback loops. Informal, cross-functional teams won’t scale effectively due to conflicting demands, requiring formal roles, responsibilities, and potential funding discussions. As you move to production, SLAs make this shift even more critical.

### Teams and Decentralization
Central services and responsibilities are being formalized, with a focus on consolidating tooling across technical domains like cloud engineering and middleware release. Developers are increasingly working directly with these service providers. Early scaling efforts emerge, often through informal methods like wiki documentation or repo cloning to replicate MVP success across other applications. Growth is happening, but without the necessary organizational reforms to support it. This drives the organization to reassess its structure, sparking active advocacy for change. As it gains momentum, and while new cloud-focused roles may be created, they often remain siloed, limiting their efficiency and understanding of dependencies.  

### Upskilling

At level 2, your team has grown comfortable with YAML and core cloud native tools, developing the skills needed to run production applications. Through hands-on experience, they’ve learned workload management, secure containerization, and RBAC, successfully deploying Kubernetes on-premises or via a managed service. Developers and platform engineers are gaining deeper insight into cloud native challenges, not just through their own work but also by implementing third-party security tooling. The team is shifting its mindset focusing on non-functional requirements: prioritizing scalability, automation, and service interfaces over managing infrastructure. As they rethink traditional architectures, they are building a stronger foundation for long-term cloud native success.

### Security
At level 2, you have production workloads and with production workloads, your team must be fully equipped to uphold security best practices. Building on Level 1, team members now have clear, well-maintained guidelines, eliminating reliance on workarounds. Accountabilities are defined, ensuring security is a shared responsibility across product and security teams. Your organization invests in cloud native security training and certifications, empowering key team members to implement and enforce security policies effectively. Engineers and operators take ownership of mutual TLS, automated secret management, artifact provenance, and vulnerability scanning, integrating security seamlessly into daily workflows and strengthening the organization’s overall security posture.

### Culture
As you move toward production at level 2, your team's interest may exceed its capabilities, requiring investment in training. The initial POC team may feel the burden of supporting new projects, highlighting a need to upskill operations staff to better support developers. The organization's overall culture still favors traditional applications and platforms, making cloud native development feel like an "island." A low level of trust may exist, with some viewing cloud native as a threat, creating competition and insecurity.

### AI
As we enter production efforts are made to simplify the interaction between AI practitioners and cloud native platforms through abstraction layers and improved tooling.  AI practitioners start to look towards user friendly and well known SDKs that abstract away Kubernetes details. Debugging may remain challenging, requiring involvement between both AI/MLOps teams and platform engineering.   

New roles or responsibilities may need to be created to help with governance and compliance. These may include model validation as well as ensuring activities are compliant with rules such as the European Union’s Artificial Intelligence Act.  

### CNCF Certifications

The Cloud Native Computing Foundation (CNCF) provides a vendor-neutral home for leading open-source projects like Kubernetes, Prometheus, and Envoy.

To build a sustainable cloud native ecosystem, investing in CNCF certifications is essential. Organizations should consider CKA and CKAD at Levels 2 and 3, with CKS becoming relevant at Level 4 to deepen security expertise.

[**Certified Kubernetes Administrator (CKA)**](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/)

* This program provides assurance that CKAs have the skills, knowledge, and competency to perform the responsibilities of Kubernetes administrators.

[**Certified Kubernetes Application Developer (CKAD)**](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/)

* This exam certifies that users can design, build, configure, and expose cloud native applications for Kubernetes.

[**Certified Kubernetes Security Specialist (CKS)**](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)

* This program provides assurance that a CKS has the skills, knowledge, and competence on a broad range of best practices for securing container-based applications and Kubernetes platforms during build, deployment and runtime. CKA certification is required to sit for this exam.

[Kubernetes and Cloud Native Associate (KCNA)](https://www.cncf.io/training/certification/kcna/)

* KCNA is a pre-professional certification designed for candidates interested in advancing to the professional level through a demonstrated understanding of Kubernetes foundational knowledge and skills.


[Kubernetes and Cloud Security Associate (KCSA)](https://www.cncf.io/training/certification/kcsa/) 

* This certification is ideal for individuals interested in learning about or working with cloud native security technologies.

[Kubestronaut Program](https://www.cncf.io/training/kubestronaut/)

* Individuals who have successfully passed every CNCF’s Kubernetes certifications – CKA, CKAD, CKS, KCNA, KCSA.

## <i class="fas fa-cogs"></i> Process

### Audit and Logs

Define a clear log aggregation strategy to ensure comprehensive logging for your production workloads at level 2\. As you're now in production, capturing and managing logs is critical. Consider implementing long-term archiving to support compliance, troubleshooting, and historical analysis.

### Software Integration and Release

For your application, implement structured build and deployment processes that align with cloud-native and container-native integration and release practices. Code quality is improving, as measured by automated tooling, and you are consistently achieving successful CI runs and test validations.  

### Security

At level 2, build security into your software integration process and runtime environment including container scanning and configuration scanning. You are extending your existing policies into your cloud native ecosystem.

## <i class="fas fa-edit"></i> Policy

### Policy Creation

At level 2, address the most critical issues first, such as audit requirements and major security threats. Treat this process as paying down policy exemption technical debt—whether by creating new policies, adhering to existing ones, or reassessing past decisions. At this stage, tactical measures like manual procedures may be necessary to meet policy requirements, but these should be recognized as temporary workarounds that contribute to technical debt.

### Implementation and Compliance

At level 2 you're now in production, ensure your primary compliance obligations are enforced. This may start with initial auditing, conducted manually or through simple scripts. Establish effective log collection across your infrastructure, platform, and application stack to enable meaningful analysis. Begin paying down the technical debt from Level 1 by implementing policies where exceptions or exemptions were previously granted.

### AI

This level involves implementing policies and practices to address immediate production needs and standardising initial approaches to security and data handling.  General best practices for security should be followed, including penetration testing and compliance checks relevant to the workload industry, such as finance or healthcare.  Ensure that there is clearly defined data ownership data lineage throughout the AI lifecycle.  AI models are only as good as the data they are trained on, so it is important to actively monitor and address potential biases in the data and algorithms.

## <i class="fas fa-server"></i> Technology

### Architecture and Solution Design
At level 2, you’re now in production. As an architect, you're thinking about the non-functional business requirements of applications, including performance, capacity, availability, disaster recovery, and security. As you implement platforms, consider how they can meet these needs and how they might fail—not only through infrastructure failure but also through logical corruption or misconfiguration. You may conduct exercises to identify failure scenarios and the risks they pose, which will guide engineering decisions.

It’s easier to meet requirements at higher levels of abstraction (e.g., instead of replicating a stateful VM, run multiple pods and load balance across them; use tools like [Rook](https://rook.io/) or [Longhorn](https://longhorn.io/) instead of replicating a [SAN](https://en.wikipedia.org/wiki/Storage_area_network)). Levels 1 and 2 are valuable stages for exploring and learning about the applications transitioning to cloud native and their service requirements, helping reduce operational risk later.

You are starting to establish production patterns that will be reused going forward. Common Terraform modules may be approved for specific workload types, and patterns for tools like secret management are being established. You are standardizing how platforms, services, and applications are built and maintained—using tools like Kustomize at scale, mandating Helm charts, or taking an operator-first approach. You may set standards for container integration (e.g., buildpacks or Containerfiles for everything).

A catalog of basic patterns is beginning to emerge. The focus is on raising the standard across applications, platforms, and infrastructure to ensure high-quality production services. This sets the foundation for scaling in Level 3\. Security classification becomes a key non-functional requirement, alongside availability and recovery. For each classification, you should know which applications fall under it and have defined patterns for supporting security components—e.g., encryption policies, artifact placement, Kubernetes secret handling, and key rotation.

You are also starting to develop placement patterns (on-prem, cloud, edge) for infrastructure and platform services such as Kubernetes clusters, and to select right-fit solutions based on these. Even if the goal is full cloud rehosting, technical or policy constraints may require keeping some workloads or services on-prem.

### Platforms and Infrastructure
At Level 2, given the production status of the workload, it is worth considering your overall platform strategy.  There are architecture aspects to this, as well as engineering.  Review the [Platforms White Paper](https://tag-app-delivery.cncf.io/whitepapers/platforms/) from the CNCF as well as the [Platform Maturity Model](https://tag-app-delivery.cncf.io/whitepapers/platform-eng-maturity-model/).  As the white paper explains, “a platform is an integrated collection of capabilities defined and presented according to the needs of the platform’s users.”  The paper also explains that there are consistent user experiences for managing the platform’s capabilities such as web portals, project templates and self-service APIs.  As such, consider that your organization does already have a set of capabilities that together provide developers the ability to get business functionality into production; however given the likely unintegrated nature of them, with potentially different user experiences with different tooling, you’ll want to consider creating an internal developer platform (IDP).  At level 2, the key aim will be the [thinnest viable platform](https://tag-app-delivery.cncf.io/wgs/platforms/glossary/#thinnest-viable-platform-tvp).

### Container and Runtime Management
At level 2, you are now running in production, you begin augmenting the basics with tools for security, policy enforcement, and workload configuration. You establish practices around container hygiene and begin defining policies for base images and dependency management. This may include:

- Using standardized base images (e.g., UBI or internal Ubuntu mirrors)  
- Allowing upstream images from sources like Docker Hub or [Quay.io](http://Quay.io) with SBOM validation  
- Maintaining a catalog of hardened, source-built images


Security practices include automated scanning, runtime observability, and policy controls. CNCF projects become strong candidates to support observability and governance requirements.

### Application Patterns and Refactoring
You’re in production now, and the focus shifts to scale, availability, observability, and alignment between your platform and applications. You may be introducing service meshes and more advanced monitoring.  
  If you’re adopting GitOps, developers need a clear understanding of its key principles and how to get started. Irrespective of this decision, they should begin using Kubernetes-native configuration management tools. This includes externalizing configuration using ConfigMaps, Secrets, or other runtime mechanisms—rather than embedding configuration in the image at build time. This approach improves validation and reduces drift, making practices like `git diff` effective for tracking changes.  
  Because the platform is software, it requires regular maintenance. Kubernetes releases approximately three times per year, so establishing a proactive cluster lifecycle and maintenance process is critical. Regular updates should be scheduled as part of ongoing operations—not treated as exceptional events.  
  From the start, developers must understand that pods are ephemeral. They should account for this by implementing node and pod affinities, PodDisruptionBudgets, and TopologySpreadConstraints to ensure service continuity during cluster upgrades and disruptions.

### Application Release and Operations
At level 2, you are now using GitOps operators for rapid, consistent deployment across all environments. Controlling access to configuration repositories and ensuring they reflect what is deployed is critical. You are consuming Helm charts and upstream package artifacts to configure third-party tools.

Supply chain security techniques are being incorporated into your releases (see the Security and Policy section). Observability is now vital to operating cloud native applications. With increased flexibility in environment creation, new release paradigms—such as maintaining two production environments to allow upgrades at any time—can offer significant benefits.

You are adopting a “roll forward” approach to issue remediation, applying the last known good configuration to the cluster. Using resources as feature flags (e.g., with Kustomize) is an effective strategy for testing upgrades. Application teams are expected to maintain all components and third-party dependencies in their solutions.

If development and operations remain separate, there must be an approval process for promoting changes to production, with operations reviewing each release. SBOMs are required for any third-party applications, possibly as a contractual or licensing requirement. It is essential to follow strong security practices for both container images and Kubernetes deployments, and to document and share these practices. Robust configuration management accelerates testing and security patching.

### Security and Policy
At level 2, ensure that development and operations teams follow best practices for container, secrets, and security management. In production, you must address encryption, authentication, and authorization. This includes certificate management and a functioning CA infrastructure that can issue certificates to running pods.

You are implementing secret management tools and automation. TLS or mutual TLS is being deployed at the cluster level and between pods—especially for sensitive workloads. A service mesh may be considered to enhance traffic visibility and manage network security features.

Your systems are auditable, with logs and events captured and retained. Generic accounts that are not traceable to individuals (e.g., “administrator” or “kubeadmin”) are not used, in contrast to service accounts used by software to access resources.

You may limit service exposure to load balancers and restrict network access to the production cluster to prevent unnecessary or unexpected exposure. These measures are especially important in multi-tenant clusters (e.g., Namespace as a Service).

Access policies are expanding to include source control, automation components, and dependencies used for managing clusters. You are extending GitOps to the platform layer, ensuring consistency and convergence to a known state, and reverting any drift—whether malicious or accidental.

You are beginning to restrict API access, and validating incoming requests using admission controllers, possibly including mutating admission controllers.

### Testing and Issue Detection
At level 2, you are now in production, you’ll begin experimenting with tools that support security, policy enforcement, misconfiguration detection, resource management, and observability—starting in staging or development environments.

Development teams are supported by platform and infrastructure teams for environment management. Tooling decisions should prioritize customer-impacting functionality. For example, don’t focus on low-priority policy controls if customers are experiencing latency issues that could be addressed by monitoring through a service mesh.

You’re actively prioritizing based on business needs and customer satisfaction. Production feedback becomes a valuable source of insight. Metrics should be tracked and visualized from both platform and application sources. While logging may be challenging at this stage, it is essential for effective troubleshooting. You may also start evaluating tracing tools.

This phase can be both exciting and challenging, as team members gain production experience at different speeds. Consistent deployments make testing easier, and a strong release pipeline improves issue remediation.

### Cost Efficiency, Resource Usage and Sustainability
At level 2, the primary focus is reaching production. This often results in cluster sprawl across environments, leading to increased costs and operational complexity. You begin limiting resource consumption and may explore multi-tenancy (e.g., Namespace as a Service) or consolidating environments (e.g., dev and test in a single cluster with separate namespaces).

You might evaluate CNCF projects like Capsule to reduce the overhead of running multi-tenant clusters. Chargeback and FinOps capabilities are introduced in a basic form, such as tracking CPU and pod requests or applying quotas at the namespace level. These practices will become more granular as you mature. You also begin experimenting with vertical and horizontal pod autoscaling—initially based on platform metrics, with early exploration into application-level metrics to inform scaling decisions using KEDA.

### AI
With the first production deployment of AI models, the emphasis shifts to ensuring the AI workload’s stability, basic scalability and service resiliency.  Initial observability is important, and model drift needs to be tracked.  Tools such as OpenTelemetry and Prometheus can also assist with monitoring load, number of accesses and response latency.  Security is also a concern in production, with model serving instances requiring firewall production, access control, penetration testing, and compliance checks.  Reaching production is a major step, but it’s not the last in increasing maturity.
