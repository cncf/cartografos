---
title: "Level 1 - Build"
description: >
   You have a baseline cloud native implementation in place and are in pre-production.
---

## <i class="fas fa-building"></i> Business Outcomes

### **Business Outcomes**

*“For many business leaders, the migration and continuing adoption of cloud native technology are not as clear-cut as migrating workloads as-is from on-premises to hybrid/public clouds. They are unlikely to sign off on major technological shifts, which inevitably create process and cultural change, without understanding the tangible benefits to them.”* [**CTO Summit**](https://www.cncf.io/reports/cto-summit-na-2022/)

Prior to arriving at level one of the model, your business should have agreed the goals for the move. These business goals need to inform adoption of cloud native technologies. Goals will center around managing risk, meeting compliance, customer satisfaction and trust and cost effectiveness. While the technologist might translate this into avoiding vendor lock-in, capacity and availability planning, disaster recovery, response times, etc, ensure that whenever discussing decisions to root the conversation in the business goal.

In level one, the organization must prioritize its top business goals/issues. This is an important step as prioritization/ranking of business goals will help technologies factor in tradeoffs. Compliance and disaster recovery will no doubt be important, but for some organizations, that might not be the main driver. Business scenario planning is essential. For example, in the case where a company has decided to use public cloud, if customer satisfaction is the priority goal and needs faster website response times, then the technology team will select cloud regions close to the customer. If cost reduction is a primary goal however, then a more cost-effective cloud region might be selected. Another example might be that it is cheaper to host data in the US, but due to EU data privacy laws, that isn’t an option. This is a very high level example, but should showcase how the prioritization of all business goals must inform decision making.

At this level, the organization is experimenting with cloud native. This should also translate into business expectations. Technologies should be given the freedom to try different experiments to achieve goals. Experiments should be documented, OKRs (Objectives and Key Results) or KPIs (Key Performance Indicators) created and provided to the business during this phase. The business should expect to see the outcomes of these experiments before continuing to embark on its cloud native journey. This helps to build confidence between the technology and business teams and is absolutely a vital step particularly as cloud native changes the way an organization operates.

### **Cloud Native Maturity Model Example KPIs**

The cloud native maturity model has four dimensions:

1. People  
2. Process  
3. Policy  
4. Technology

These all manifest within them a specific business goal. The following chart illustrates example overriding business and technology goals and how they translate across the dimensions. It includes some example business KPIs.

|  | Business to Business | Business to Business | Business to Consumer |
| ----- | ----- | ----- | ----- |
| **Business model** | ACME software sells to the enterprise market. | Anville Enterprise provides data to financial service organizations using ACME software. | ABC Company purchases data from Anville Enterprise. |
| **Business goal** | To sell to the enterprise, ACME must demonstrate security and compliance within the supply chain. *KPI: Zero policy violations* | To meet its customers’ demands, it must scale to deliver services to 20,000 locations. *KPI: Scalability* | To hit its revenue targets, it must improve customer retention through improved satisfaction rates. *KPI: eg. High Availability* |
| **Technology goal** | ACME software must ensure that all software is signed and has Software Bill of Materials (SBOM) as part of its deliverables, and meets all PCI, NIST and SOC2 standards for software delivery. | Anville must rely on a cloud native platform that is able to deliver capacity as required. It must be able to ensure compliance with policy at all times. | ABC must ensure that it has modern applications accessible from all platforms at all times, with frequent updates, and can be trusted by customers with their financial details. |
| **Process goals** | Implement a pipeline for delivering software with all relevant metadata attached and signed. | Anville must have a strong delivery process for its software and platforms. | ABC must understand the data it is purchasing with the assurance it meets all standards and can be audited i.e. how did we get the data and how did Anville process it. |
| **Policy goals** | ACME will understand what requirements it needs to meet to sell to customers, including customers’ own policy requirements | Business dictates what regulatory requirements it must meet. Outcome will be a documented completed checklist of achieved standards for the business to review. | ABC must meet (and all vendors meet) PCI compliance standards and pass PCI audits. |
| **People goals** | People will follow all security and policy requirements. People will adopt a security first approach to all activities. ACME will invest in a security center of excellence and train developers on secure software development processes. | Developers responsible for integration of ACME’s software, and DevOps teams responsible for operating platforms will be well skilled on cloud native and have adopted an agile approach with quick feedback/testing loops to meet scale. | Development teams are getting new features to market faster as they are enabled with guardrails. |
| **Example KPIs** | Count of software vulnerabilities Time to patch Code coverage testing SOC 2 Audit Report | Uptime measurement SLAs Response times Time to patch Release frequency | Baseline customer retention rate (CRR) Net Promoter Score (NPS) Customer effort score (CES) Customer satisfaction score (CSAT) Customer churn rate |

### **Cost**

In level one, the finance, technology and business teams need to be aligned. Technology needs to understand resourcing and the finance team needs to understand change fees. The organization must make allowances for running both the legacy systems and new cloud environments. In level one, costs will not go down, however as it is just the build/experimentation phase, the costs should not be exorbitant.


## <i class="fas fa-users"></i> People

### Organizational Change
With the adoption of cloud native technologies, your business will undertake organizational changes. You must be ready for this as teams, who you hire, and how you structure infrastructure and development will change.

In the early stages of cloud native transformation, organizational support is limited, with efforts centered on a proof of concept (POC) or a single application. Agile methodologies are being tested, but team structures remain largely unchanged. Cloud initiatives often start with informal, cross-functional groups, leveraging diverse skill sets for early experimentation and learning. At this stage, collaboration is intense as teams work together to build foundational knowledge. As maturity progresses, collaboration evolves, becoming more structured and role-driven from levels one to five.  

### Teams and Decentralization
Just like workloads in the cloud, your teams will become fit-to-purpose and highly scalable.

At level 1, teams are actively exploring cloud native tooling, primarily Kubernetes, with a clear goal of reaching production—not just experimentation. Work is typically conducted within an MVP program by a cross-functional team of developers, system engineers, and other experts with diverse technical experience. Success requires a strong commitment to developing skills across all layers of the stack, supported by frequent collaboration to maintain momentum. There’s easy access to different operations to ease difficult requests. For example, a network engineer can justify requests that are at first glance not appropriate. Leadership provides sponsorship and accountability to drive progress.

### Security
With all the many attack vectors that have to be mitigated remotely in a cloud native context, it is imperative to have a security-first posture for all aspects of the application lifecycle (including software delivery and ongoing operation/maintenance).

At level 1, security is heavily reliant on individuals manually configuring, learning, and adhering to best practices across development, source control, integration, testing, troubleshooting, and cloud resources. Clear guidelines define preferred, safe, and forbidden practices, along with documented workarounds that include measures to minimize or reverse their impact. Some security responsibilities are delegated within the cloud native team, requiring close coordination with core security teams. This may involve strict skill requirements or a dedicated security expert to ensure alignment and compliance.

### Upskilling
We know you already have great people, but they need to be equipped to take on the new challenges inherent to the cloud.

At this level, your team must grasp the challenges cloud native solves, the fundamentals of containers and how they differ from virtual machines, and why cloud native is ideal for microservice architectures. Leverage available resources—community forums, internal experts, and external specialists—to accelerate learning. A strong understanding of Kubernetes' declarative model and core resources will help newcomers navigate the ecosystem effectively.

### Culture
The adoption of cloud native technologies requires a significant cultural shift. A team’s willingness to embrace new ideas, experiment, and collaborate is a key indicator of its ability to progress through the maturity levels.

Initially, the cultural shift is limited to a small, dedicated team focused on a proof-of-concept (POC) or a minimum viable product (MVP). This team, often a combination of senior specialists and innovators, applies existing knowledge to new cloud native challenges. The broader organization’s culture remains largely unchanged at this stage, with cloud native efforts viewed as an isolated experiment.

### AI
As well as its profound effect on technology, AI brings in new roles and responsibilities, some of which are new to some organizations, and requires new skills and specialties not found in many companies.

At this first level, you’re not in production and individuals and teams primarily operate within their traditional disciplines, with limited understanding or direct integration with the complexities of cloud native AI systems. AI may first be used by many as a finished product or service, with little understanding of its underlying mechanisms, or how it is built or deployed.

Data scientists and ML engineers that are familiar with data and machine learning develop scripts locally and then may have them reengineered by Distributed Systems Engineers for distributed execution, at scale, perhaps on non-cloud native platforms, perpetuating a clear division of labour and expertise. At Level 1, as you take your first steps into cloud native AI, a need for close collaboration between AI and cloud native platform engineering teams emerges as the need becomes clear for specific engineering to cater for complex configurations and tasks like GPU virtualisation and dynamic allocation. AI practitioners find they need to engage in activities outside their core ML expertise such as becoming familiar with Kubernetes and containers, and, from their perspective, other platform or infrastructure concerns.  The first AI/ML pipelines in Kubernetes may include multiple technologies that are not tightly integrated.

## <i class="fas fa-cogs"></i> Process

### Audit and Logs
Your process will incorporate logging and auditing, whether to meet internal requirements or to support compliance mandates—both internal policies and external regulations.

At level 1, manual log scraping is likely ad hoc, with no centralized logging system or SIEM in place. Log aggregation and retention may be inconsistent or not exist across your cloud native stack, including infrastructure, platform, and application layers.

### Software Integration and Release
Central to your cloud native transformation is the adoption of a software integration and release process to help you build, test and deploy applications based on modern software development practices. 

At level 1, you may not have a formal change control process in place. Instead changes occur on an ad-hoc or informal basis. If you already use CI/CD, it’s essential to adapt and evolve it for your cloud-native environment. This means building on existing best practices while ensuring they align with cloud-native principles.

### Security
Integrating security tooling and best practices into your cloud native environment as early as possible is essential for maintaining a strong security posture. The concept of “shifting left” emphasizes embedding security—alongside testing and other critical practices—early in the development lifecycle. 

Security is woven throughout the Cloud Native Maturity Model, with each level playing a role in strengthening an organization's security posture. A comprehensive approach ensures security teams can drive maturity across the software supply chain, platforms, and beyond, recognizing security as a cross-cutting concern that impacts every aspect of cloud-native operations.

At level 1, make security a first-class citizen in every aspect of implementation. Understand the unique security challenges across your infrastructure, network, platform, applications, and code, and proactively address vulnerabilities and misconfigurations. Prioritize security from the start—building it in from the beginning is far easier than retrofitting security practices and tooling later.

## <i class="fas fa-edit"></i> Policy

### Policy Creation
When adopting cloud native environments, start at Level 1 by understanding your application's functional and architectural requirements. Map these to both internal policies—such as infosec, physical security, and business policies—and external regulations from authorities and industry bodies.  
  You’ll need to reconcile existing policies with new cloud native guidelines and implications. Open communication between cloud native and policy teams is essential, ensuring stakeholders understand key policy requirements and can determine where traditional policies apply—or don’t. Intent matters as much as implementation.  
  To maintain velocity, identify policies that may create friction and discuss how traditional approaches, like universal backups or hot standbys, may not fit cloud native environments. Where necessary, engage policy stakeholders to refine or update policies, secure exemptions for early-stage or non-production use, and implement minimum production requirements (e.g., secrets management) at Level 1 to ease the transition to the next stage.  

### Implementation and Compliance
You will need policies in place to implement compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve.

During level 1, take the time to understand your compliance requirements, such as CIS, NIST, and PCI. Define SLOs and set compliance priorities early on. While this may not be a strict pre-production requirement, its importance will grow as you move toward production. Recognize that existing policies may not seamlessly translate to a cloud native environment. Be prepared to address compliance concerns with different technical implementations—for example, using network policies to isolate cloud native platforms that might otherwise violate compliance or monitoring for anomalous behavior.

### AI
Policy is a vital topic within AI, both internally within the organization, and from outside the organization in terms of legislation and regulation.  As well as being technical, there are also ethical considerations with AI.

Level 1 is where there is foundational consideration given to AI.  Awareness of any data privacy regulations is critical, such as GDPR, as well as, for example, the European Union AI Act.  Internal model registries should be implemented where required.  Technical protections should be implemented, and data strategies for model training should also be developed.  Data classifications and existing data separation techniques may not necessarily fit as models in development may need access to production data for training purposes.  There also should be an acknowledgement of the need to address potential bias in data.

## <i class="fas fa-server"></i> Technology

### Architecture and Solution Design
This section outlines how architecture and solution design evolve from ad hoc development and basic planning to fully automated, policy-driven platforms with codified standards. As maturity increases, organizations align architecture with business goals, optimize for scale and efficiency, and empower developers through self-service and well-defined patterns.

At this level, the focus is on getting workloads into development, without paying much attention to the specific availability requirements of components. The goal is to prepare for production and begin building cloud native capabilities. Capacity planning, such as network address space, should be considered early to avoid significant rework later. It’s tempting to start small when prototyping, but small designs often make their way into production. Invest effort in upfront planning for areas that are difficult to adjust later.

In cloud native environments, traditionally distinct architecture domains are now tightly integrated. Architects must work more closely with core service teams such as networking, security, and storage. From a solution design perspective, begin evaluating how your application might need to change to better support cloud native architecture (e.g., a monolith may not be suitable). Authentication and authorization can be challenging for legacy applications—consider replacing LDAP with OAuth or OIDC 2.0.

Begin building up the supporting services for your cloud native workloads. Consider the logical and technical interfaces that make up your cloud perimeter, as these heavily influence how workloads are architected and how they integrate with upstream and downstream systems. Avoid boxing yourself into a corner early on to prevent common issues later. When planning your production architecture, consult reference architectures such as those provided by the [CNCF reference architectures](https://architecture.cncf.io/).

### Platforms and Infrastructure
For the sake of clarity, we regard a platform or infrastructure that is used by application developers as production. 

You’re beginning to build your cloud infrastructure, whether on-premises or in the cloud. It’s important to consider foundational technologies early—networking, firewalls, IAM, access controls, and policies—and whether any of these need to change. As you experiment with Kubernetes, keep track of emerging needs and decisions; these will serve as breadcrumbs guiding your journey toward cloud native.

Expect to address RBAC policies, load balancer or ingress configurations, cluster dashboards, privileged access (or the removal of it), and container logging. Your goal is to move from managing servers as ‘pets’ to treating them as ‘livestock’ by investing in declarative infrastructure with Infrastructure as Code (IaC) tools.

Platform teams need dedicated engineering clusters to validate and iterate on their infrastructure work. These clusters provide the flexibility to build, test, and tear down resources manually as needed. However, any cluster intended for application developers—including those labeled as "development" or "integration"—must be treated as production-grade. These environments should be provisioned using your strategic IaC tooling (e.g., OpenTofu), with versioned modules that ensure consistency across dev, test, and production. For example, if deploying GKE with specific NIC/subnet settings, the module should be versioned and reused across all application environments to ensure predictability and compliance.

If a consolidated DevOps practice isn’t yet in place, involve your future operations team now to build familiarity and alignment. For cloud service providers, you’ll also need to consider regions, encryption key management, and integration with your corporate network.

Regardless of environment, version-control everything and adopt IaC to manage configurations. You’ll be deploying frequently and must be able to tear down environments just as easily without leaving behind configuration drift or cruft (‘crumbs’ of left over technical detail, such as files or configuration).

You’re also beginning to shape your deployment and operating models. Key questions will emerge: Does the same team own both the app and the cluster? How are clusters provisioned? How are applications onboarded? Are you adopting models like namespace-as-a-service or cluster-as-a-service? Will there be a shared responsibility model for the clusters?

### Application Patterns and Refactoring
As you begin your cloud native journey, start with a small, manageable application—ideally a stateless, greenfield microservice. This will help you validate the fundamentals: Kubernetes access (kubectl), networking, platform capabilities, CI/CD processes, and initial security patterns. It also provides an opportunity to define application architecture standards, deployment templates, and policy guardrails that can scale across future projects.

While microservices are a common starting point, Kubernetes is increasingly used as a general-purpose runtime—meaning monoliths may still exist or even be newly developed, depending on business needs. It’s important to define the differences between microservices and monoliths early, and understand how microservices typically align better with Kubernetes’ strengths around scalability, independent deployment, and resilience. Regardless of architecture, focus on patterns that enable gradual modernization—such as the strangler pattern—which can guide future refactoring efforts.

Early cloud native adoption should focus on simple use cases that expose platform and process gaps quickly. Application and platform teams should work closely together at the start, ideally with cross-functional teams (e.g., developers paired with cloud specialists), to accelerate learning and reduce duplication of effort. Over time, these functions will split as platforms mature and can support broader reuse.

You’ll likely be dealing with technical debt, and some applications will depend on third-party services with their own roadmaps. These realities should inform your prioritization. Application teams must also become familiar with the cloud native services and capabilities offered by the platform team and may need to collaborate with platform product managers to shape future needs.

These early applications will serve as blueprints for broader adoption.

Here is a working model for the microservices path. You may adapt this to your model.

Level 1: Begin by reviewing microservice patterns and architecture in the context of your specific applications. Non-functional requirements—such as latency, resilience, scalability, and third-party integrations—must be carefully considered. For example, splitting logic across pods can introduce latency (particularly across datacenters or regions), so it’s critical to evaluate architectural patterns early.

If you're refactoring a monolith, expect significant redesign. Existing architectures may not have the technical scaffolding to support cloud native patterns. State management is a key concern—refactoring may require substantial changes here. This process should reinforce the understanding that moving to cloud native is a long-term commitment.

Cloud native platforms offer abstractions and capabilities that were previously hard to implement. With this flexibility comes the need to understand the quality and trade-offs of various infrastructure components—for example, object vs. block storage, or the selection of container network interfaces ([CNIs](https://kubernetes.io/docs/concepts/extend-kubernetes/compute-storage-net/network-plugins/)) or [networking](https://kubernetes.io/docs/concepts/services-networking/#the-kubernetes-network-model) resources within Kubernetes itself: ingress controllers, and service meshes like the Gateway API. Gaining a comprehensive view of available options is essential as you refactor for Kubernetes.

A shift to declarative models introduces new non-functional requirements for application teams. One fundamental change is the ephemeral nature of infrastructure—developers must now design applications assuming that no single instance will persist. Availability responsibilities move from infrastructure to application, requiring developers to build resilience into the code.

Instead of depending on individual pods, applications must be managed via higher-level Kubernetes resources like Deployments or StatefulSets. This lowers infrastructure costs but increases developer accountability for reliability and availability.

Pods, by nature, are ephemeral. This affects caching strategies—developers must either implement persistent caching or use persistent volumes where necessary. Because applications will sit behind ingress controllers or load balancers, readiness and liveness probes become critical. End-to-end readiness checks—such as backend transaction validation—ensure only functional services are exposed to users.

Developers must also understand pod-to-container relationships and models like sidecars, which help separate concerns. IP addresses are dynamic, so service discovery must rely on DNS, the Kubernetes API or other appropriate means.

### Container and Runtime Management
At this stage, the focus is on learning to build and run containers. Teams must upskill in writing container files, building images, running them in clusters, and understanding how containers differ from virtual machines. Developers also need to work comfortably with containers on their local machines.  
  A platform team is established to build and manage Kubernetes clusters. Developers begin using development and integration tooling (e.g., Tekton), while infrastructure teams introduce Infrastructure as Code (e.g., OpenTofu) to provision cloud environments, including projects, VPCs, IAM, and Kubernetes infrastructure.   
  To prepare for production, container image builds are integrated into CI pipelines, and a container registry is adopted with clear versioning and tagging practices. Kubernetes is now the application runtime platform, and you are gathering all necessary deployment artifacts such as YAML files for Deployments, StatefulSets, Services, Ingress, LoadBalancers, PersistentVolumes, and more.  
  You likely begin using Helm charts (e.g., for Ingress-NGINX) and deploy your first operators for core functionality such as secrets management. Understanding the Kubernetes operator model and custom resources (CRDs) becomes highly valuable.   

### Application Release and Operations
Managing a cluster with Infrastructure as Code (IaC) differs from managing application release and deployment, though many of the same techniques and tools apply to both.

When starting with Kubernetes, it is important to gain as much hands-on experience as possible. You will become familiar with the Kubernetes API, write YAML manifests, and begin exploring configuration management and templating tools. Early on, you’ll be supporting dev, test, and prod environments, so it’s critical to evaluate tooling that can help you manage your manifests effectively from the start.

Version control systems—traditionally used by developers—become essential for release and operations in the cloud native world. Since releases are defined in code, they must be tracked, forming the basis for GitOps. This requires careful evaluation of branching models that align with your organization’s release policies. Ensure you understand the capabilities of your GitOps tooling and your release process. Remember the developer principle of “Don’t Repeat Yourself.”

### Testing and Issue Detection
Testing and issue detection evolve significantly as organizations adopt cloud native practices. This section outlines how testing, observability, and operational readiness mature across each level, from manual validation to automated recovery and continuous validation.

At level 1, when just starting out, most testing is manual, focused on your initial production candidate application. With Kubernetes, your attention is on basic network connectivity and confirming that applications can be successfully deployed. You will perform smoke tests and user acceptance testing (UAT).

In Levels 1 and 2, the emphasis is on consistency in container image builds and the continuous delivery process. You’ll rely on existing tools for unit testing and static code analysis. Both functional requirements (e.g., application logic) and non-functional requirements (e.g., performance, capacity, and availability) must be considered.

You’ll begin implementing liveness and readiness probes and incorporating observability tools. It's important to define clear service level agreements (SLAs) based on business and customer expectations.

### Security and Policy
This section outlines how security and policy practices mature alongside cloud native adoption, starting with basic IAM and secret management and evolving toward automated, policy-driven platforms. As organizations progress, they implement defense-in-depth strategies, enforce compliance through policy as code, and continuously optimize security in response to changing threats.

Begin building your secured CI/CD pipeline if you haven’t already, and remember that your current practices with VMs will evolve significantly. You have developed an Identity Provider and Identity and Access Management (IAM) infrastructure, integrating it into your clusters using tools such as RBAC and service accounts.

Following the [12-Factor](https://12factor.net/) principles, configuration is stored in the environment—including secrets, which are base64-encoded (not encrypted)—to allow stage-specific configurations (e.g., dev, test, prod). Much more can be stored in the environment, enabling immutable images and a strong separation between application and configuration. Avoid embedding environment-specific information, such as credentials, directly in container images.

You are becoming familiar with the Kubernetes API and are aware of its users. You also understand Kubernetes’ flat networking model, where all pods can connect to each other by default, with no inherent workload isolation.

### Cost Efficiency, Resource Usage and Sustainability
This section outlines how efficiency and sustainability practices evolve from basic resource tuning and cost awareness to full optimization of workloads across architecture, geography, and carbon impact. As organizations mature, they incorporate FinOps, sustainability reporting, and developer accountability to achieve peak efficiency and minimize wasted resources.

At level 1, A common temptation at this level is to focus solely on containerizing and deploying workloads, without tuning resource requests and limits. Addressing these early yields long-term benefits. Developers will be involved, particularly in sizing memory allocations (e.g., Java heap sizes).

### AI
The [CNCF AI White Paper](https://www.cncf.io/reports/cloud-native-artificial-intelligence-whitepaper/) describes “Cloud Native Artificial Intelligence \[as] an evolving extension of Cloud Native” that “...refers to approaches and patterns for building and deploying AI applications and workloads using the principles of Cloud Native.  Enabling repeatable and scalable AI-focused workflows allows AI practitioners to focus on their domain”.  In this context, cloud native works to solve with its scalability, resilience, observability and manageability many of the challenges that AI suffers.

Level 1, start out with initial development and experimentation, organizations explore basic AI concepts and conduct small-scale experiments, typically where the outcome is known using discriminative AI such as the classification of email.  Developers working with AI will be working mostly on rapid prototyping and gaining access to resources such as storage, networking and processing for training (the process of building an AI model from data) and inference (computing results from AI models).  Kubernetes facilitates resource access and model dependencies can be effectively managed through containerization and as OCI artifacts, models can be stored in registries and caching can be enabled.
