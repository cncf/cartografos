# Cloud Native Maturity Model - Policy

## Navigation

The Cloud Native Maturity Model is composed of six separate documents - the [Prologue](./prologue.md) and the five key reference documents:

* [People](./people.md)
* [Process](./process.md)
* [Policy](./policy.md)
* [Technology](./technology.md)
* [Business Outcomes](./business_outcomes.md)

## Introduction

The Cloud Native Maturity Model spans five key dimensions: People, Process, Policy, Technology and Business Outcomes. This paper addresses policy, the critical implementation of internal requirements, and compliance to external regulations. 

The journey of adopting policy in cloud native environments parallels the learning curve of Kubernetes and cloud native technologies, transitioning from an imperative to a declarative approach. Rather than specifying the procedure, this dimension outlines outcomes and results you should anticipate. Understand that policy adoption is a gradient, every organization has a different risk appetite. 

Policy comes from both internal and external sources, forming a set of rules and requirements that the technical organization must interpret and comply with. In fast-changing environments, policy can be a contentious topic, often leading to disputes. Recognizing these challenges—and understanding how to mitigate them—is essential.

Policy input generally falls into three categories, each targeting different layers of the organization:

1. **Regulators (Business)** – Ensure the integrity of the industry, such as finance, healthcare, or utilities.  
2. **Legal (Compliance)** – Mandates like GDPR and EU DORA, enforced by regulators.  
3. **Technical (Standards & Guidelines)** – Frameworks from institutions like NIST and MITRE that provide technical guidance.

Not all policies carry the same weight, making it important to distinguish between regulatory, legal, and technical requirements.

## Policy Level Overview

* Level 1: You will have a limited set of documented policies in place to support services you're building in the cloud. You are working with compliance teams to evaluate policy obligations and how they may change with cloud native technology.  
    
* Level 2: As your services reach production, you have initial policies agreed upon and these are recorded.  
    
* Level 3: You will implement policy-as-code and build this into your processes.  
    
* Level 4: You now have defined SLAs around policies and remediation. Treating policy-as-code and enforcement as subject to a software development lifecycle.  
    
* Level 5: Based on your learnings, you will refine your policies as your organization achieves maturity, taking advantage of technologies such as machine learning in order to improve detection and enforcement. Your policy apparatus is constantly evolving with the changing cloud native threat landscape.

## Policy Creation

You will need to translate your organization’s policies and compliance requirements to your cloud native environment.

* Level 1: When adopting cloud native environments, start at Level 1 by understanding your application's functional and architectural requirements. Map these to both internal policies—such as infosec, physical security, and business policies—and external regulations from authorities and industry bodies.  
  You’ll need to reconcile existing policies with new cloud native guidelines and implications. Open communication between cloud native and policy teams is essential, ensuring stakeholders understand key policy requirements and can determine where traditional policies apply—or don’t. Intent matters as much as implementation.  
  To maintain velocity, identify policies that may create friction and discuss how traditional approaches, like universal backups or hot standbys, may not fit cloud native environments. Where necessary, engage policy stakeholders to refine or update policies, secure exemptions for early-stage or non-production use, and implement minimum production requirements (e.g., secrets management) at Level 1 to ease the transition to the next stage.  
* Level 2: Address the most critical issues first, such as audit requirements and major security threats. Treat this process as paying down policy exemption technical debt—whether by creating new policies, adhering to existing ones, or reassessing past decisions. At this stage, tactical measures like manual procedures may be necessary to meet policy requirements, but these should be recognized as temporary workarounds that contribute to technical debt.  
    
* Level 3: The cloud team should actively influence policy decisions by collaborating with business leaders and key stakeholders (rather than a one way dialogue with exception requests). The cloud team may also serve as subject matter experts within or alongside the compliance team. Given cloud native’s reliance on automation, identify manual processes from Level 2 that need to be addressed. Conduct thorough threat modeling and prioritize the highest-risk areas of the organization’s workflow. For example, if developers are introducing out-of-policy code—such as code without an SBOM—understand the reasoning and work to address the underlying issue.  
    
* Level 4: At this stage of maturity, you will customize policies to align with your organization's business needs while minimizing exceptions. This will integrate business functionality and logic into your technical policy infrastructure. Over time, your organization will gain a clearer understanding of its highest risks and greatest value areas, leading to a stronger emphasis on effective classification. Earlier levels may rely on external guidance without fully aligning with internal skill set requirements, but by Level 4, this matures. There will be a well-developed ability to classify risks and a more strategic engagement with technical, operational, and business risks. Policy decisions should be actively shaped by real-world learnings. Technical edge cases arising from enforcement should inform policy evolution. Additionally, at Level 4, organizations may begin leveraging LLMs to accelerate both technical and written policy creation—while ensuring accountability remains intact.  
    
* Level 5: At this stage, while still drawing from frameworks like CIS and NIST, your organization should also focus on giving back by actively contributing policies to the open source community. Regulators will likely seek input from Level 5 organizations to shape policy, making your expertise highly valuable in these discussions. Your deep understanding of what works—and what doesn’t—positions you as a key partner in policy formulation.    
    
  Leverage multiple data sources, including user activity, log data, internal datasets, and governmental guidelines, to drive informed policy decisions. With your advanced capabilities, you can share insights through case studies, thought leadership, and open source contributions, helping to shape the broader industry landscape.

## Implementation and Compliance

You will need policies in place to implement compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve.

* Level 1: Take the time to understand your compliance requirements, such as CIS, NIST, and PCI. Define SLOs and set compliance priorities early on. While this may not be a strict pre-production requirement, its importance will grow as you move toward production. Recognize that existing policies may not seamlessly translate to a cloud native environment. Be prepared to address compliance concerns with different technical implementations—for example, using network policies to isolate cloud native platforms that might otherwise violate compliance or monitoring for anomalous behavior.  
    
* Level 2: Now that you're in production, ensure your primary compliance obligations are enforced. This may start with initial auditing, conducted manually or through simple scripts. Establish effective log collection across your infrastructure, platform, and application stack to enable meaningful analysis. Begin paying down the technical debt from Level 1 by implementing policies where exceptions or exemptions were previously granted.  
    
* Level 3: Policy compliance and auditing are increasingly automated within Kubernetes, often incorporating policy-as-code. Organizations may evaluate both generalized and specialized cloud native policy enforcement tools, leading to a proliferation of tooling. It's important to identify opportunities for consolidation.    
    
  Manual procedures from Level 2 should now be encoded as services, leveraging policy-as-code tools and CNCF ecosystem solutions to enforce policies effectively. It can be tempting to set a high bar of entry for tooling (e.g. to impose restrictions on tool adoption, or to enforce standards too early); however organizations should remain open to evaluating new projects as the cloud native landscape evolves.    
    
  This phase also presents an opportunity to strengthen the software supply chain by using emerging software patterns and tools to enhance policy enforcement. Just as a programming language becomes self-hosting when it can compile itself, organizations should aim for a policy framework that can enforce and refine itself through automation.  
    
* Level 4: Technical and business decision-making actively drives the consolidation and standardization of technologies, moving away from arbitrary or ad-hoc choices. Policy tooling expands beyond infrastructure to include applications such as traffic proxies, service meshes, message buses, and Linux, increasing the scope of managed policies while maintaining control through declarative configurations.  
    
* Key activities include applying policies to business applications or extending policy enforcement to middleware. Every enforcement gate should be backed by a business decision. Integrate policy into the software delivery lifecycle—unit test, smoke test, and integration test your policies. Treat policies as code and include them in your SDLC to ensure consistency, reliability, and compliance.  
    
* Level 5: Compliance never ends\! Strengthen your feedback loop with stakeholders and leverage advanced machine learning, ai and other tools to establish baselines, detect anomalies, and ensure visibility across large volumes of compliance data. At this stage, you may contribute to policy development by participating in organizations like NIST, the Linux Foundation, or industry-specific policy groups, providing valuable insights to the broader community.  
    
  Your technical implementations, security strategies, and defense posture can now be shared more openly than ever before. By contributing your expertise, you help the cloud native community navigate an increasingly complex and volatile landscape.

## AI

Policy is a vital topic within AI, both internally within the organization, and from outside the organization in terms of legislation and regulation.  As well as being technical, there are also ethical considerations with AI.

* Level 1: This is where there is foundational consideration given to AI.  Awareness of any data privacy regulations is critical, such as GDPR, as well as, for example, the European Union AI Act.  Internal model registries should be implemented where required.  Technical protections should be implemented, and data strategies for model training should also be developed.  Data classifications and existing data separation techniques may not necessarily fit as models in development may need access to production data for training purposes.  There also should be an acknowledgement of the need to address potential bias in data.

* Level 2: This level involves implementing policies and practices to address immediate production needs and standardising initial approaches to security and data handling.  General best practices for security should be followed, including penetration testing and compliance checks relevant to the workload industry, such as finance or healthcare.  Ensure that there is clearly defined data ownership data lineage throughout the AI lifecycle.  AI models are only as good as the data they are trained on, so it is important to actively monitor and address potential biases in the data and algorithms.

* Level 3: As you scale, it is important to bring in increasing supply chain best practices such as image validation, attestation, signing and data provenance.  Continuously validate models for potential biases and to ensure ethical outcomes.   This includes a  “safety by design” approach that embeds user safety and rights into the design and development of products.

* Level 4: In line with the AI discussion in the technology section, we see a convergence where AI itself is used to enhance governance, security and compliance within cloud native systems, growing a symbiotic relationship.  This means, for example, considering MLOps pipelines to capture and maintain data provenance.  AI may also be at the core of your tooling to Trust and Safety, managing content and conducting scans for risks, mitigate abuse, and protect brand safety.

* Level 5: This stage is characterized by the full automation and optimization of policy adherence and the integration of AI into all operational aspects of cloud native environments, leading to peak efficiency and sustainability.  Internally, within the cloud native environment, Kubernetes controllers integrate with a natural language interface using LLMs, understanding logs, managing resource usage and many other tasks.  Full data provenance and lineage is automatically captured and maintained, ensuring transparency and accountability.   In terms of sustainability, there is continuous optimization of resource scheduling \- not just for performance and cost, but also for power conservation, ensuring maximum energy efficiency and reduced carbon footprint.  Finally you see a future state where policies for responsible AI and ethical use are not merely applied but autonomously monitored, adapted and enforced by the AI systems themselves, in alignment with the “Safety by Design” philosophy at an architectural level.
