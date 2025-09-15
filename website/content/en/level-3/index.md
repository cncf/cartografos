---
title: Level 3 - Scale
description: Your competency is growing and you are defining processes for scale.
---

## <i class="fas fa-building"></i> Business Outcomes

Level three, scale, is the **“Messy Middle.”** Your organization \- both business and technology \- has bought into cloud native. You are seeing business goals achieved. You’ve resolved common challenges most organizations face, you understand how things are happening and are no longer spending time on what’s already been discovered/created/learnined. You’ve also made changes to people, process and technology. You’ll have repeatable patterns in place.

While this all sounds great, this is the messy middle because while people are comfortable with cloud native, things are happening much faster and there are new requirements emerging. Teams are adopting new technologies to support your business goals.

But with scale comes new requirements. You’ll have requests for new tooling to meet security, compliance, and availability requirements. You may have several teams working with different tools. There will be a proliferation of tooling \- some of it from existing or legacy infrastructure and systems, some of it dating from level one, and level two, and new tooling as new tools are introduced to add functionality or capabilities that the initial tool choices may not necessarily have had. This is the time where there will be the most sprawl. Furthermore, there may also be significant inefficiency where, for example, incorrectly sized platforms are being deployed, further driving up cost. All of this will need to be worked through and the business needs to understand that with scale can come complexity that the technology team needs to work through.

For example, at level three there may be multiple logging systems in place collecting audit events for archiving \- one for existing platforms and one for new cloud native platforms. These will eventually be consolidated, along with the potential merging and archiving of duplicate data. It is at this point you may become familiar with the concept of “technical debt.” This is where short term actions are taken to get a new feature or service shipped, but that results in future rework. Time and labor will need to be expended whether a task is fully completed with a strategic solution, or a short term tactical solution needing rework, so do recognize that a short term fix now will need to have someone go back and tidy up later on.

Either way, don’t give up in the messy middle. While you might have some applications that are running beautifully, not all may. The ones that are successful need to be used to demonstrate what can be achieved. Keep driving these forward to serve as ‘lighthouses’ for what is possible within your company. Small organizations might swim through level three, while large enterprise organizations with lots of heritage and legacy, might be here for years.

While there is a dedicated people section within scale, at level three the business needs to recognize how teams must evolve. As cloud native scales beyond a few projects, apps or services, more people will be onboarded to the new ways of working. The business should expect some resistance from users slow to accept cloud native. This is a journey that the business needs to expect, but also to bring users along the ride early so that when you get to level three, teams aren’t surprised. Training should be done as early as possible across the organization showing positive outcomes of the experimentation phase (level one) and migration phase (level two) for some applications. You don’t want cloud native to be viewed as an obstacle to work and you don’t want resistant users to become a hindrance to adoption.

The business needs to encourage ways to help people to learn the technology, process and policies so that you can achieve business goals. The organization needs to safeguard the leaders i.e. the people who have spearheaded the cloud native movement while encouraging others to onboard and become experts.

### **Cost**

As you scale your cloud native infrastructure, you’ll now start to scale down your legacy system. This is where your costs will start to even out and/or reduce. The chart below shows how you would expect to see your costs change over time.

![cloud native vs legacy cost](/images/cloud-native-vs-legacy-cost.svg)

At this level you’ll also, particularly in the case of a migration to public cloud from traditional on-premise or co-located systems, see a change in the types of costs faced by the organization. OPEX expenses will have increased, but CAPEX such as fixed assets and associated depreciation, as well as long term data center contracts, may be reduced or come to an end. The financial benefits of a reduced on-premise footprint should be becoming apparent.

When cost issues occur in the ‘messy middle’ which are particularly urgent, for example a proliferation of Kubernetes clusters rather than a consolidation onto a fewer number of clusters through more advanced resource usage patterns, maintain a strategy of working to resolve the issue and consider relevant options, rather than abandoning the transition to cloud native. Your technical team will likely have a solution but they may need to invest time to realize gains. They will also be addressing this as part of level four.

## <i class="fas fa-users"></i> People

### Organizational Change
As your team's competency grows, your organizational structure solidifies to support best practices, which are curated and encoded for reuse—often driven by facilitators like a Center of Excellence. Roles and workflows are formalized for consistency, exposing high-overhead services that rely on tickets, calls, and manual requests. This explicit coordination and collaboration between teams and individuals can highlight obvious services that would benefit from being “engineered as a service” and will evolve into platform engineering teams. The collaboration itself is valuable information that we can use in combination with the other data and metrics we are collecting.

### Teams and Decentralization
During level 3 service consolidation is accelerating, with development teams assuming clear responsibilities and consuming well-defined interfaces, ranging from email to fully developed APIs. However, the cognitive load of integrating various services is becoming a distraction, overwhelming teams that must independently manage consumption. To address this, organizations begin exploring a [**Platform Engineering**](https://tag-app-delivery.cncf.io/whitepapers/platforms/) strategy, treating the platform as a product with dedicated teams providing end-to-end support. Success requires the right skills, authority, and a team explicitly focused on platform enablement. Additionally, restructuring around technology value streams becomes essential, as siloed structures increasingly hinder efficiency. This shift requires a strong leadership mandate to drive change.

### Upskilling

At this stage, teams are advancing beyond basic cloud native adoption, extending cloud platforms and leveraging the broader CNCF ecosystem. Senior and principal engineers play a crucial role in scaling these efforts, bringing deep expertise in Kubernetes, CI/CD, policy management, and public cloud operations. Cloud-native knowledge is widespread, with skills distributed in a bell curve—many at an intermediate level, while others push boundaries by experimenting, refining, and proving competency through CKA/CKAD certifications, bake-offs, and hands-on implementation. The organization confidently integrates new CNCF projects, such as extending Kubernetes with Crossplane or building developer portals with Backstage, solidifying its ability to navigate the messy middle of cloud native transformation.

### Security
As teams mature at level 3, manual security practices are replaced with third-party tooling for tasks like secret management and mutual TLS. Supply chain security becomes a priority, with a focus on artifact provenance, bill of materials, and vulnerability scanning. Clear accountability and operational responsibilities are essential, as security remains a shared commitment in cloud native environments. Specialists in infrastructure, platform, and application security ensure depth in key technical domains. Identity and Access Management and physical access controls are established and rigorously maintained, reinforcing a culture of security at every level.

### Culture
Cloud platforms are now widely accepted by product owners and business leaders at level 3\. It's critical to demonstrate the benefits of cloud native to cultivate trust and overcome any lingering resistance. You know you're approaching maturity when technical teams, management, and leadership are all comfortable with cloud native. While competition may still exist (e.g., implementing competing tools like Argo vs. Flux), a high level of trust is a vital commodity for continued adoption.

### AI
As we scale out AI within the organization at level 3, we may start to see the emergence of the MLDevOps or AI Engineer as the glue between data science, platform engineering, infrastructure, and development. We may also see the emergence of trust and safety experts to manage content and conduct, mitigate abuse and protect user rights and brand safety. Operators will likely start to develop skills using AI-powered tooling for Kubernetes management such as  K8sGPT for the natural language processing of logs, or using machine learning to analyze massive datasets for security threat identification.

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

During level 3, you should begin enabling audit capabilities and configuring the most critical alerts if you haven’t already. Reduce noise by filtering irrelevant data and ensuring logs are structured for easy retrieval and analysis. Focus on capturing and presenting the most business-critical insights to support informed decision-making.

### Software Integration and Release

At level 3, you are establishing a center of excellence around your software integration and release process, focusing on measuring and improving release velocity, defect rates, and deployment cadence. While you have implemented continuous delivery, production deployments still require an approval gate.

At this stage, you are experimenting with advanced deployment strategies such as blue-green and canary releases to optimize reliability. Defects, hotfixes, and bug fixes are trending downward, reflecting improved stability. Best practices are now firmly in place, and human access to production has been eliminated in favor of GitOps operators, ensuring a more secure and automated deployment process.

### Security

At level 3, your security process should including implementing automatic continuous scanning to flag misconfigurations or security issues.

## <i class="fas fa-edit"></i> Policy

### Policy Creation

At level 3, the cloud team should actively influence policy decisions by collaborating with business leaders and key stakeholders (rather than a one way dialogue with exception requests). The cloud team may also serve as subject matter experts within or alongside the compliance team. Given cloud native’s reliance on automation, identify manual processes from Level 2 that need to be addressed. Conduct thorough threat modeling and prioritize the highest-risk areas of the organization’s workflow. For example, if developers are introducing out-of-policy code—such as code without an SBOM—understand the reasoning and work to address the underlying issue.

### Implementation and Compliance

At level 3, policy compliance and auditing are increasingly automated within Kubernetes, often incorporating policy-as-code. Organizations may evaluate both generalized and specialized cloud native policy enforcement tools, leading to a proliferation of tooling. It's important to identify opportunities for consolidation.  

Manual procedures from Level 2 should now be encoded as services, leveraging policy-as-code tools and CNCF ecosystem solutions to enforce policies effectively. It can be tempting to set a high bar of entry for tooling (e.g. to impose restrictions on tool adoption, or to enforce standards too early); however organizations should remain open to evaluating new projects as the cloud native landscape evolves.  

This phase also presents an opportunity to strengthen the software supply chain by using emerging software patterns and tools to enhance policy enforcement. Just as a programming language becomes self-hosting when it can compile itself, organizations should aim for a policy framework that can enforce and refine itself through automation.

### AI

As you scale at level 3, it is important to bring in increasing supply chain best practices such as image validation, attestation, signing and data provenance.  Continuously validate models for potential biases and to ensure ethical outcomes.   This includes a  “safety by design” approach that embeds user safety and rights into the design and development of products.

## <i class="fas fa-server"></i> Technology

### Architecture and Solution Design
t this level, architectural planning becomes more intentional. You are operating in production and discovering new ways cloud native can deliver business value—such as supporting multiple standards (e.g., object storage), increasing platform agility, and improving cost and availability. Costs may initially rise before falling. New capabilities emerge—for example, handling bursty workloads by using spot nodes, which in turn improves availability.

A subtle shift occurs: tools previously outside the runtime platform are now integrated (e.g., GitOps and its dependency on source control repositories), which raises availability requirements for those tools. It’s essential to understand your dependencies within the cloud native ecosystem.

You may find preferred tools or standards don’t work for all use cases (e.g., the 80/20 rule), especially with specialized workloads that scale horizontally or vertically. These edge cases need their own standards. Rather than letting those teams create them in isolation, extend your portfolio of services and standards to include them. Having multiple teams consume a pattern will help with driving up quality over time as feedback is incorporated about what works and what doesn’t.

The growing cloud native ecosystem offers many new capabilities. Emphasis now falls on defining what is acceptable for use and under what conditions—based on non-functional requirements. For example, you might offer multiple placement region options, with tiered requirements for regional versus zonal clusters, depending on application criticality. Creating a capability catalog helps prevent overprovisioning and reduce costs.

Security rules and standards are codified as policies and checked regularly—including within the software supply chain. You have patterns in place for data sovereignty, data residency, and complying with regulations across jurisdictions (e.g., some countries require financial or medical data to stay within their borders). You must understand your provider’s residency guarantees.

At this stage, you're expected to trial new technologies, vendors, and tools. Learn and decide quickly, and clearly document what is and isn’t supported. Think in terms of full technology lifecycles and retire tools to pay down technical debt as soon as possible.

You also begin standardizing workload migration processes and architectural requirements. A triage process may be needed per application to handle networking, IAM, and analysis components. Define a clear policy set for all application workloads during migration. Migrating workloads requires time and architecture guidance. For example: do we refactor? How do we replace authentication solutions previously available on-prem? Reference architectures and implementations help development teams accelerate migration and refactoring.

### Platforms and Infrastructure
At this stage, you're building confidence in your infrastructure by gaining deep visibility into how it's operating. Monitoring, alerting, and resource usage tracking become top priorities—not just at the node level (CPU, memory, etc.) but also across the entire cluster. You're evolving from simply running infrastructure to managing it proactively.

Whereas in earlier stages you may have remediated failing components manually, now you're replacing and redeploying them automatically. You're beginning to manage infrastructure like software, leveraging Kubernetes as the control plane for elasticity and self-healing behavior. This means offloading more responsibility to the cluster itself through mechanisms like horizontal and vertical pod autoscalers, as well as application-focused autoscalers such as KEDA.

Advanced Kubernetes scheduling practices come into play, including the use of priority classes, quality of service tiers, affinity rules, and TopologySpreadConstraints. These capabilities help manage resource allocation and eviction behavior, which are critical in elastic, multi-tenant environments where infrastructure directly impacts user experience.

Your infrastructure must now support a more sophisticated software delivery lifecycle. This includes provisioning sandbox environments for application developers, platform engineers, and infrastructure teams to experiment and validate changes safely. Your deployment and operating models become more flexible to support a wider range of workload types and team needs.

You’re beginning to collect and act on platform usage data to inform architectural decisions. For example, if 95% of teams operate effectively within a namespace-as-a-service model, you may double down on optimizing that offering. If others require dedicated clusters, you’ll need to decide whether to offer cluster-as-a-service or guide them toward scalable alternatives. These decisions are costly to reverse, so it's essential to balance strategic vision with measured data from real usage.

Infrastructure becomes harder to change as it scales—so flexibility must increasingly come from the platform and application layers rather than the infrastructure itself. To support this, you'll need to clearly communicate platform capabilities, limitations, and upcoming evolutions. You’ll also begin to prioritize investments based on both customer needs and cost-awareness, recognizing that in a cloud environment, every resource consumed has a price.

### Application Patterns and Refactoring

At Level 2, application patterns are well defined and there's a strong push for consistency in foundational practices. Now at level 3, you begin expanding beyond the basics and may encounter the limitations of your existing tooling.

Applications are refactored to better align with platform-native resource types—such as using object storage instead of persistent volumes—and to adopt operator-first patterns for lifecycle management. Where developers previously worked within a namespace-as-a-service model, they may now explore cluster-as-a-service options to gain greater isolation or flexibility.

You may introduce abstraction layers like [Dapr](https://dapr.io/) to decouple infrastructure services (e.g., messaging, storage) from application code, simplifying development and improving portability. Kubernetes is no longer just an infrastructure platform—it’s evolving into a true application hosting platform, a foundation for your internal PaaS.

New application patterns are emerging, while older, less scalable ones are phased out. These shifts are guided by your evolving [non-functional requirements](https://en.wikipedia.org/wiki/Non-functional_requirement) and the capabilities of the underlying platform. 

### Container and Runtime Management
As your workloads grow and you scale operations at level 3, consistent tooling across clusters becomes essential for maintaining visibility into your Kubernetes environments. Tools like KArmada enable multi-cluster configuration management, helping ensure consistency and reducing configuration drift—even across regions or continents.

Namespace as a Service models are common, but maintaining efficiency becomes more challenging. Cost management becomes critical—when infrastructure scales by a factor of 10, even small inefficiencies (e.g., 80% vs. 90% utilization) have a large impact.

Release management complexity increases. You need to answer questions like: How do we support multiple clusters with a tool like Argo CD? Network planning becomes more important, particularly around IP address management and API server quotas. Even small clusters can place heavy load on Kubernetes API servers, so it's vital to monitor quota limits with your cloud provider should you not be hosting on premise clusters.

Managing custom resources and operators also becomes a significant operational concern. You must define and document shared responsibilities across infrastructure, platform, and application teams. Operational processes such as cluster upgrades must be well-thought-out and follow best practices—like managing all configuration in source control.

Observability expands dramatically. The volume of metrics, logs, and traces increases with scale. You need to archive logs effectively and ask whether you should audit system calls if you are doing so. Certificate management and encryption (including key rotation) become critical, often necessitating service meshes for automatic certificate issuance and mTLS. Manual processes won’t scale—automation becomes mandatory.

You will likely be exploring different techniques and operators and discovering their limitations depending on your deployment model. Centralized tooling can become a bottleneck—for example, pulling artifacts from a single repository or funneling logs to a single destination. Distributed control may be necessary to avoid these constraints, such as using multiple Fluent Bit instances to aggregate logs instead of overwhelming a central log ingestion endpoint.

You begin to weigh tradeoffs between centralized and distributed models, each offering different benefits and challenges. Questions around maintaining application artifacts and dependencies at scale also emerge—you may be managing tens or hundreds of thousands of containers that require updates and patching.

Readiness and liveness probes take on new importance at scale. Readiness probes should validate end-to-end functionality, including downstream dependencies, to ensure the pod is truly ready for traffic. Liveness probes help maintain workload availability. As always, workloads must be treated as cattle, not pets.

### Application Release and Operations
Level 3 means developers are now responsible for their own releases, including developing their own continuous deployment pipelines. They use the same deployment process for dev, test, and production environments. You are placing greater emphasis on provenance and controlling what enters your clusters (see Security and Policy section).

Instrumentation is robust and includes tracing, observability, service meshes, and mutual TLS. Awareness of cloud provider offerings increases, and performance becomes a key concern. You must now balance performance and cost.

Sharing learning across the organization is essential to avoid perpetuating inefficient practices and technical debt. Upstream third-party tools often release updates as quickly as your internal platform, making it important to stay current with new versions, features, and best practices. As you scale, capacity limits in your initial tooling may surface, making capacity planning and deeper tooling utilization critical.

### Security and Policy
Now at level 3 is the time to automate deployment guardrails and platform components like certificate management while implementing security best practices through policy as code. Define your enforcement strategy and begin adopting relevant third-party benchmarks and standards. Consider incorporating anomaly and threat detection technologies.

As production environments grow more complex, some issue remediation may require changes to your policy-as-code, Infrastructure as Code, or application code.

You are evaluating [SPIFFE/SPIRE](https://spiffe.io/docs/latest/spire-about/spire-concepts/) as you move towards a zero trust model for security, and are well underway with certificate and trust store automation, and service mesh integration. Admission controllers now read from your policy platform, enforcing organization-wide or application-specific rules.

You are scanning container images, identifying and addressing [CVE](https://www.cve.org/)s, and maintaining SBOMs to provide provenance. You aim to meet [SLSA Build Level 1](https://slsa.dev/spec/v1.1/levels) requirements. Machine learning may also be introduced to enhance threat detection practices.

### Testing and Issue Detection
Building on your tool and process experimentation at level 3, you now implement these practices in production. You establish robust alerting and dashboards, expanding your observability capabilities. Consistency in builds and deployments supports reproducible testing.

Development and test environments become shorter-lived and are spun up or torn down based on business requirements, following consistent specifications. These environments may be entire clusters or, for cost efficiency, isolated namespaces within a single cluster. You'll begin investing in user interfaces that allow developers to create and destroy environments easily.

To manage the overhead of dynamic environments, automation is key. You are scaling your build pipelines, leveraging platform capabilities such as cost-efficient regional placement, resource management, and parallelization to increase build concurrency and support more comprehensive testing.

Vulnerability scanning at the container and cluster level, along with SBOMs, enables effective identification of dependency-related security issues. You’re also becoming more aware of the tradeoff between developer velocity and test coverage, including how frequently and which types of tests are run.

### Cost Efficiency, Resource Usage and Sustainability
At level 3, sticker shock may occur here (or even earlier). You begin consolidating workloads and resources more aggressively, potentially using spot VMs and deploying in lower-cost regions, while balancing availability and performance. Idle development and test workloads are scaled down outside business hours where possible.

You become more aware of underlying infrastructure—such as machine types, chipsets like ARM or RISC-V, and specialized hardware like GPUs. FinOps becomes essential as multiple teams run production workloads. Cluster efficiency improves through approaches like Namespace as a Service, and you adopt tools to report and manage resource requests effectively.

### AI
At level 3, as the organization begins to scale, more complex AI applications like Generative AI and Large Language Models (LLMs) are introduced, and the focus shifts to standardizing MLOps processes and addressing inconsistencies between development and production environments.  As such, if not already employed, then you may find yourself investigating solutions like Python SDKs for KubeFlow or general-purpose distributed computing engines like Ray (and KubeRay in Kubernetes).  For more advanced Kubernetes scheduling needs, Kueue, Volcano and other non-CNCF tools may help.  Data volumes and locality will also drive technical solution architecture.  Rising processing demands from LLMs will lead to increased demand for accelerators such as GPUs, TPUs and other technologies.  Given the cost implications, technologies such as that allow for sharing of resources such as vGPU and multi instance GPU may be investigated.  Kubernetes development around Dynamic Resource Allocation may also help.  In order to promote sustainability as well as reduce costs, models may be autoscaled for serving and placed into geographical regionals that are powered by cleaner energy.  
