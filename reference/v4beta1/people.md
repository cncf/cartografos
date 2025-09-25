# Cloud Native Maturity Model \- People

## Navigation

The Cloud Native Maturity Model is composed of six separate documents \- the [Prologue](http://./prologue.md) and the five key reference documents:

* [People](http://./people.md)  
* [Process](http://./process.md)  
* [Policy](http://./policy.md)  
* [Technology](http://./technology.md)  
* [Business Outcomes](http://./business_outcomes.md)

## People Introduction

As you adopt cloud native technologies, your team's expertise will grow. The Cloud Native Maturity Model spans five key dimensions: People, Process, Policy, Technology and Business Outcomes. This paper focuses on People—the foundation of a successful deployment.  

Progressing from level one to five, your team starts with basic technical knowledge. Over time, they invest in training, build competency, and shift responsibilities to developers. Maturity is reached when DevOps and DevSecOps are fully integrated, and your team confidently explores new technologies. Leadership embraces cloud native as the future, recognizing its business value and driving agile transformation.

* Level 1: Your business aligns with cloud native goals, and leadership understands its benefits. The team is new to the technology but has basic technical knowledge and relevant qualifications.  
    
* Level 2: Individuals actively train and build skills, creating small groups of subject matter experts (SMEs). DevOps emerges as cloud engineers and developer groups contribute platform skills. Leadership begins taking ownership of cloud native initiatives.  
    
* Level 3: Competency expands across Dev, Ops, and Security, with formalized expertise, standardized practices, and accelerators. You may have a platform engineering team (see [platform engineering maturity model](https://tag-app-delivery.cncf.io/whitepapers/platform-eng-maturity-model/)) Cloud-native is integrated into business strategy as a core principle.  
    
* Level 4: Competency shifts to development teams, enabling self-service infrastructure. Leadership fully commits, driving cloud native transformation across the organization.  
    
* Level 5: Your organization operates with fully integrated DevOps and Platform Engineering. Teams confidently experiment with new technologies and sandbox trials, continuously innovating and adapting to change.

## Organizational Change

With the adoption of cloud native technologies, your business will undertake organizational changes. You must be ready for this as teams, who you hire, and how you structure infrastructure and development will change.

* Level 1: In the early stages of cloud native transformation, organizational support is limited, with efforts centered on a proof of concept (POC) or a single application. Agile methodologies are being tested, but team structures remain largely unchanged. Cloud initiatives often start with informal, cross-functional groups, leveraging diverse skill sets for early experimentation and learning. At this stage, collaboration is intense as teams work together to build foundational knowledge. As maturity progresses, collaboration evolves, becoming more structured and role-driven from levels one to five.  
    
* Level 2: Organizational change is underway. You’ll identify structural barriers, such as siloed teams that slow delivery. To improve agility, you’ll establish project teams, adopt agile methodologies, and explore frameworks like Team Topologies and value streams for faster feedback loops. Informal, cross-functional teams won’t scale effectively due to conflicting demands, requiring formal roles, responsibilities, and potential funding discussions. As you move to production, SLAs make this shift even more critical.  
    
* Level 3: As your team's competency grows, your organizational structure solidifies to support best practices, which are curated and encoded for reuse—often driven by facilitators like a Center of Excellence. Roles and workflows are formalized for consistency, exposing high-overhead services that rely on tickets, calls, and manual requests. This explicit coordination and collaboration between teams and individuals can highlight obvious services that would benefit from being “engineered as a service” and will evolve into platform engineering teams. The collaboration itself is valuable information that we can use in combination with the other data and metrics we are collecting.  
    
* Level 4: You're transitioning to platforms and value streams, with services efficiently delegated to product teams. Developers can focus on product code aligned with business goals, seamlessly consuming necessary services through efficient interfaces—eliminating time spent on platform and infrastructure tasks outside their core responsibilities.  
    
* Level 5: At full maturity, the organization is fully committed to cloud native, seamlessly integrating culture, technology, and processes for maximum efficiency. It rapidly adopts and discards elements based on their value, ensuring continuous optimization.

## Teams and Decentralization

Just like workloads in the cloud, your teams will become fit-to-purpose and highly scalable.

* Level 1: Teams are actively exploring cloud native tooling, primarily Kubernetes, with a clear goal of reaching production—not just experimentation. Work is typically conducted within an MVP program by a cross-functional team of developers, system engineers, and other experts with diverse technical experience. Success requires a strong commitment to developing skills across all layers of the stack, supported by frequent collaboration to maintain momentum. There’s easy access to different operations to ease difficult requests. For example, a network engineer can justify requests that are at first glance not appropriate. Leadership provides sponsorship and accountability to drive progress.  
    
* Level 2: Central services and responsibilities are being formalized, with a focus on consolidating tooling across technical domains like cloud engineering and middleware release. Developers are increasingly working directly with these service providers. Early scaling efforts emerge, often through informal methods like wiki documentation or repo cloning to replicate MVP success across other applications. Growth is happening, but without the necessary organizational reforms to support it. This drives the organization to reassess its structure, sparking active advocacy for change. As it gains momentum, and while new cloud-focused roles may be created, they often remain siloed, limiting their efficiency and understanding of dependencies.  
    
* Level 3: Service consolidation is accelerating, with development teams assuming clear responsibilities and consuming well-defined interfaces, ranging from email to fully developed APIs. However, the cognitive load of integrating various services is becoming a distraction, overwhelming teams that must independently manage consumption. To address this, organizations begin exploring a [**Platform Engineering**](https://tag-app-delivery.cncf.io/whitepapers/platforms/) strategy, treating the platform as a product with dedicated teams providing end-to-end support. Success requires the right skills, authority, and a team explicitly focused on platform enablement. Additionally, restructuring around technology value streams becomes essential, as siloed structures increasingly hinder efficiency. This shift requires a strong leadership mandate to drive change.  
    
* Level 4: At Level 4, the organization focuses on structuring its platform to centrally expose and integrate services for seamless developer consumption. The platform team consolidates previously fragmented capabilities into standardized, self-service interfaces accessible via portals, APIs, and CLIs. Developers move beyond email-based or Slack requests, instead consuming APIs and curated resources, shifting away from a consulting-based support model. This evolution embeds organizational policies and processes directly into the platform. Value Stream teams can now leverage platform capabilities with minimal handovers, enabling developers to request resources and services programmatically while staying focused on business logic.   
    
* Level 5: Teams have seamless access to the tools and capabilities they need to deliver business value without friction. Developers focus solely on business logic, free from platform and infrastructure concerns, while platform engineers ensure on-demand infrastructure availability. At this stage, the organization operates at peak efficiency—services are consumed without facilitation, teams remain lean, and both the technical ecosystem and organizational structure are right-sized. Tech debt is continuously managed within each domain, preventing accumulation. Efficiency drives every decision, ensuring the right resources are in place without compromising business needs (i.e. not downsizing to the detriment of the business). 

## Upskilling

We know you already have great people, but they need to be equipped to take on the new challenges inherent to the cloud.

* Level 1: Your team must grasp the challenges cloud native solves, the fundamentals of containers and how they differ from virtual machines, and why cloud native is ideal for microservice architectures. Leverage available resources—community forums, internal experts, and external specialists—to accelerate learning. A strong understanding of Kubernetes' declarative model and core resources will help newcomers navigate the ecosystem effectively.  
    
* Level 2: Your team has grown comfortable with YAML and core cloud native tools, developing the skills needed to run production applications. Through hands-on experience, they’ve learned workload management, secure containerization, and RBAC, successfully deploying Kubernetes on-premises or via a managed service. Developers and platform engineers are gaining deeper insight into cloud native challenges, not just through their own work but also by implementing third-party security tooling. The team is shifting its mindset focusing on non-functional requirements: prioritizing scalability, automation, and service interfaces over managing infrastructure. As they rethink traditional architectures, they are building a stronger foundation for long-term cloud native success.  
    
* Level 3: At this stage, teams are advancing beyond basic cloud native adoption, extending cloud platforms and leveraging the broader CNCF ecosystem. Senior and principal engineers play a crucial role in scaling these efforts, bringing deep expertise in Kubernetes, CI/CD, policy management, and public cloud operations. Cloud-native knowledge is widespread, with skills distributed in a bell curve—many at an intermediate level, while others push boundaries by experimenting, refining, and proving competency through CKA/CKAD certifications, bake-offs, and hands-on implementation. The organization confidently integrates new CNCF projects, such as extending Kubernetes with Crossplane or building developer portals with Backstage, solidifying its ability to navigate the messy middle of cloud native transformation.  
    
* Level 4: Cloud-native adoption is now deeply ingrained across teams, fostering a culture of shared knowledge and continuous learning. Developers, platform engineers, and architects are actively refining processes, selecting tools that align with organizational policies, and proactively delivering business value. Senior engineers and architects play a crucial role in guiding teams as they expand Kubernetes and integrate cloud native technologies to meet specific needs.  
    
  At this stage, developers evolve beyond writing code—they become problem-solvers, whether building applications, optimizing platforms, or extending infrastructure. A new generation of senior engineers emerges, comfortable with cloud native complexities and capable of developing operators, custom resource management, and automation frameworks. The shift from reactive problem-solving to strategic, proactive decision-making empowers teams to innovate with confidence.  
    
  As responsibilities grow, technical leadership is essential at every level. Managers and senior decision-makers must develop technical fluency to evaluate and approve solutions effectively. With layers of abstraction and self-service platforms, teams can work efficiently within well-defined guardrails, ensuring both autonomy and alignment with business goals.  This has the effect also of allowing junior staff to become much more productive, much more quickly as they are able to direct their attention to functional development and engineering without having to be caught up in environment setup and other concerns not directly concerned with their main responsibilities.

  A further mark of maturity at Level 4 is the quality of documentation.  At this level it covers all aspects of platforms as well as infrastructure, including design as well as operational documentation.  This is maintained alongside technical artefacts such as code and kept up today with appropriate archiving as features are removed and technical debt reduced.

* Level 5: Your organization is now composed of highly capable individuals and teams who fully leverage cloud native capabilities, engaging effectively across technical, architectural, and business domains. Teams can swiftly identify opportunities to drive business value and reduce technical debt, fostering a culture of continuous learning and innovation.  
    
  As a learning organization, you stay ahead of trends, integrating both mature CNCF projects and emerging sandbox technologies. Skilled engineers contribute to open-source projects, creating opportunities for outreach and deeper industry engagement.  
    
  Teams are small but diverse, equipped with broad expertise to mitigate key-person risk and ensure stability. Strong communication protocols and a robust professional development pipeline sustain long-term growth, enabling teams to adapt, collaborate, and innovate effectively.

## Security

With all the many attack vectors that have to be mitigated remotely in a cloud native context, it is imperative to have a security-first posture for all aspects of the application lifecycle (including software delivery and ongoing operation/maintenance).

* Level 1: Security is heavily reliant on individuals manually configuring, learning, and adhering to best practices across development, source control, integration, testing, troubleshooting, and cloud resources. Clear guidelines define preferred, safe, and forbidden practices, along with documented workarounds that include measures to minimize or reverse their impact. Some security responsibilities are delegated within the cloud native team, requiring close coordination with core security teams. This may involve strict skill requirements or a dedicated security expert to ensure alignment and compliance.  
    
* Level 2: With production workloads, your team must be fully equipped to uphold security best practices. Building on Level 1, team members now have clear, well-maintained guidelines, eliminating reliance on workarounds. Accountabilities are defined, ensuring security is a shared responsibility across product and security teams. Your organization invests in cloud native security training and certifications, empowering key team members to implement and enforce security policies effectively. Engineers and operators take ownership of mutual TLS, automated secret management, artifact provenance, and vulnerability scanning, integrating security seamlessly into daily workflows and strengthening the organization’s overall security posture.  
    
* Level 3: As teams mature, manual security practices are replaced with third-party tooling for tasks like secret management and mutual TLS. Supply chain security becomes a priority, with a focus on artifact provenance, bill of materials, and vulnerability scanning. Clear accountability and operational responsibilities are essential, as security remains a shared commitment in cloud native environments. Specialists in infrastructure, platform, and application security ensure depth in key technical domains. Identity and Access Management and physical access controls are established and rigorously maintained, reinforcing a culture of security at every level.  
    
* Level 4: Your team is embracing Zero Trust, shifting from default allow to default deny, ensuring access is granted case by case. This level of control is possible through integrated platform services authenticated by a single identity provider. Developers, engineers, and end users—from finance and HR to customers—experience seamless, secure access to approved capabilities, while the organization gains greater visibility and control over security and compliance.  
    
* Level 5: Your team operates at peak efficiency, with the right people, tools, and policies ensuring workloads and teams can handle requests safely and seamlessly. You rely on experts who can articulate what must be done, how to do it, and what’s possible. Clear, written guidelines support well-defined procedures, carried out by skilled engineers. Threat detection is embedded, whether preventative or retrospective, while security roles focus on policy development or technical execution. The organization actively contributes to public policy and open-source tooling, reinforcing its leadership in security and best practices.

## Culture

The adoption of cloud native technologies requires a significant cultural shift. A team’s willingness to embrace new ideas, experiment, and collaborate is a key indicator of its ability to progress through the maturity levels.

* Level 1: Initially, the cultural shift is limited to a small, dedicated team focused on a proof-of-concept (POC) or a minimum viable product (MVP). This team, often a combination of senior specialists and innovators, applies existing knowledge to new cloud native challenges. The broader organization’s culture remains largely unchanged at this stage, with cloud native efforts viewed as an isolated experiment.

* Level 2: As you move toward production, your team's interest may exceed its capabilities, requiring investment in training. The initial POC team may feel the burden of supporting new projects, highlighting a need to upskill operations staff to better support developers. The organization's overall culture still favors traditional applications and platforms, making cloud native development feel like an "island." A low level of trust may exist, with some viewing cloud native as a threat, creating competition and insecurity.

* Level 3: Cloud platforms are now widely accepted by product owners and business leaders. It's critical to demonstrate the benefits of cloud native to cultivate trust and overcome any lingering resistance. You know you're approaching maturity when technical teams, management, and leadership are all comfortable with cloud native. While competition may still exist (e.g., implementing competing tools like Argo vs. Flux), a high level of trust is a vital commodity for continued adoption.

* Level 4: Your organization has crossed the cultural chasm. Cloud native is the predominant mode of operation, with traditional application patterns becoming the exception, approved only under specific business requirements. Cost-consciousness is high, and the organization focuses on balancing innovation with efficiency, aiming to be "lean but not anemic." Trust becomes a major theme, and the cultural shift is fully embraced.

* Level 5: At this level, a culture of ease, trust, and respect prevails. Burnout is no longer a dominant topic. Conflicts and disagreements are addressed quickly and effectively, with a shared confidence that everyone is working toward the same goals. This culture is a key driver of efficiency, enabling continuous improvement and innovation without friction.

## AI

As well as its profound effect on technology, AI brings in new roles and responsibilities, some of which are new to some organizations, and requires new skills and specialties not typically found in many companies.

* Level 1: At this first level, you’re not in production and individuals and teams primarily operate within their traditional disciplines, with limited understanding or direct integration with the complexities of cloud native AI systems. AI may first be used by many as a finished product or service, with little understanding of its underlying mechanisms, or how it is built or deployed.  
    
  Data scientists and ML engineers that are familiar with data and machine learning develop scripts locally and then may have them reengineered by Distributed Systems Engineers for distributed execution, at scale, perhaps on non-cloud native platforms, perpetuating a clear division of labour and expertise. At Level 1, as you take your first steps into cloud native AI, a need for close collaboration between AI and cloud native platform engineering teams emerges as the need becomes clear for specific engineering to cater for complex configurations and tasks like GPU virtualisation and dynamic allocation. AI practitioners find they need to engage in activities outside their core ML expertise such as becoming familiar with Kubernetes and containers, and, from their perspective, other platform or infrastructure concerns.  The first AI/ML pipelines in Kubernetes may include multiple technologies that are not tightly integrated.

* Level 2: As we enter production efforts are made to simplify the interaction between AI practitioners and cloud native platforms through abstraction layers and improved tooling.  AI practitioners start to look towards user friendly and well known SDKs that abstract away Kubernetes details. Debugging may remain challenging, requiring involvement between both AI/MLOps teams and platform engineering.   
  New roles or responsibilities may need to be created to help with governance and compliance. These may include model validation as well as ensuring activities are compliant with rules such as the European Union’s Artificial Intelligence Act.  
    
* Level 3: As we scale out AI within the organization, we may start to see the emergence of the MLDevOps or AI Engineer as the glue between data science, platform engineering, infrastructure, and development. We may also see the emergence of trust and safety experts to manage content and conduct, mitigate abuse and protect user rights and brand safety. Operators will likely start to develop skills using AI-powered tooling for Kubernetes management such as  K8sGPT for the natural language processing of logs, or using machine learning to analyze massive datasets for security threat identification.

* Level 4: The “AI Engineer” role evolves to focus heavily on AI tooling, infrastructure and deploying AI chains and agents, indicating a deep specialization in AI-driven operations.  All personnel benefit from highly automated and intelligent systems. Administrators and site reliability engineers benefit from natural language interfaces for cluster control, which significantly lowers their learning curve for managing complex Kubernetes clusters. Skills in continuous optimization for multiple criteria (e.g., power conservation, latency) become crucial, often facilitated by AI-driven models

* Level 5: While we are attempting to be all encompassing in this model, the Cartografos Working Group would like to acknowledge that level 5 AI maturity is outside of our remit. AI is changing rapidly and what may be level 5 today might not be tomorrow. We are excited to see how AI will impact people’s skills. 

## CNCF Certifications

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