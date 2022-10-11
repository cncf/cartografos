# Cloud Native Maturity Model - People

## Navigation

The Cloud Native Maturity Model is composed of five separate documents - the [Prologue](./prologue.md) and the four key reference documents:

* [People](./people.md)  
* [Process](./process.md)  
* [Policy](./policy.md)  
* [Technology](./technology.md)

## Introduction

As you adopt cloud native technologies, you and your team will become increasingly knowledgeable. The Cloud Native Maturity Model covers four major dimensions - People, Process, Policy and Technology.  This paper addresses people - the key to success of your deployment.

Working from level one to five, your team will be new to the technology with some basic technical understanding. Over time, your team will be actively invested in training and skill development, grow competency and shift it to the development team. You’ve reached maturity when you have DevOps and DevSecOps working and your team is comfortable with experimenting with new technologies and sandbox trials. Your leadership team has accepted cloud native as the future and understands the value it brings to the business. Your leadership team actively drives agile transformation.

* Level 1: Cloud native framework is driving your business and technical goals. You and your team are new to the technology, however do have some basic technical understanding and some pre-existing qualifications. Your business leaders understand the benefits of cloud native.

* Level 2: Individuals are actively invested in training and skills. The outcome is that small pockets of SMEs and expertise are appearing. DevOps has started to appear with inclusion of cloud skill engineers and developer groups offering platform skills. Cloud Native efforts are also owned by members of leadership.

* Level 3: The team’s competency is growing and there is commitment from Dev, Ops and security. You are formalizing expertise and curating standards and accelerators. Cloud Native becomes a first-class citizen for strategy.

* Level 4: As you improve, you are shifting competency to the development team for them to self-service. Full commitment from leadership.

* Level 5: You've reached maturity, the organization is skilled and you have DevOps and DevSecOps working. Teams are comfortable experimenting with new technologies and sandbox trials.

## Organizational Change

With the adoption of cloud native technologies, your business will undertake organizational changes. You must be ready for this as teams, who you hire, and how you structure infrastructure and development will change.

* Level 1: As you transform, you will have limited organizational support and will be in a proof of concept (POC) phase or be focused on only one application.

* Level 2: Organizational change is happening. You will define project teams, create agile project groups and have quick feedback/testing loops.

* Level 3: As your people’s competency grows, the organization structure is now in place to support best practices and these are curated and encoded for reuse. You will have formalized responsibilities and embrace an agile methodology.

* Level 4: Cloud is now the default infrastructure for all services. The business is now requesting services from DevSecOps vs. requesting traditional servers.  

* Level 5: At maturity, the entire organization is committed and onboarded to the cloud native environment.

## Teams and Decentralization

Just like workloads in the cloud, your teams will become fit-to-purpose and highly scalable.

* Level 1: Teams are exploring cloud native tooling, primarily Kubernetes.  However, this is not just for the sake of exploring, but rather it is with the goal of reaching production.  All work is generally taking place within a formal MVP program.

* Level 2: We are starting to formalize central services and responsibilities, including the consolidation of tooling, as well as the deprecation of non-cloud native tooling.

* Level 3: You’re really starting to see a high degree of centralisation, with clear and understood responsibilities. A balance must be struck, however, between flexibility and velocity: exceptions or customizations to standardized support may introduce validation and approval bottlenecks.

* Level 4: As the platform becomes more established, you can really start the process of decentralization. You can work on the development of a self-service portal incorporating the policies and processes of your organization to enable developer service ownership.

* Level 5: You now have self-provisioning amongst different groups, along with organizational acceptance of the self-service portal. The business benefits from service ownership.

## Developer Agility

Your organization is committed to decentralization and will employ “teams of teams”. This is an essential requirement of your people. Across the different levels of maturity, people will be implementing tools for automated testing, metrics and feedback. DevOps SMEs will appear around level 4 and you will have group cohesion. By level 5 maturity, agile is well incorporated into the organization.

* Level 1: Developers may have learned about Agile Manifesto and adopted Scrum Framework without necessarily including Operations. Developers may attempt to resolve external dependencies themselves, slowing down feedback, with incomplete features per sprint.

* Level 2: The team is comfortable with technically challenging problems and how cloud native can help. There is an organizational commitment to decentralisation and automated testing of builds, with automated deployments to some environments.

* Level 3: Your people have implemented continuous delivery for all environments, including for complex releases and with built-in compliance testing. The ops team is now integrated into cross-functional teams, though individuals may not necessarily be able to do all functions.

* Level 4: Feedback is extended from application metrics through to platform and non-functional requirements with clear mapping of value streams to technological implementation. Developers are able to quickly test complex scenarios with many unknowns, cloud and application risks are easily and quickly identified and patched.

* Level 5: The group has strong ability to recover and maintain throughput, tolerating individuals joining and leaving. Business decisions are well informed by rich and accurate data across all teams in the organization allowing adoption of FinOps.

## Upskilling Developers

We know you already have great people, but they need to be equipped to take on the new challenges inherent to the cloud.

* Level 1: Your application team will be trained in 12 factor applications, microservice and cloud native patterns. You will also require developers who are quite comfortable with cloud native concepts and tooling such as kubectl in order to bootstrap your development team.

* Level 2: Your wider development team is able to operate the fundamentals of Kubernetes including:  
  * Connecting an operator to the Kubernetes API
  * Become comfortable with Kubectl commands
  * Understanding how to list and view resources
  * Performing basic actions (mechanical actions with limited understanding of how it works)

* Level 3: Implement a repeatable cycle of troubleshooting so changes and iterations are done quickly.

* Level 4: Developers are more sophisticated and Kubernetes is widely adopted by multiple groups in different business areas, with a body of knowledge developing and actively shared including integration and release processes. Developers and cluster owners are actively expanding Kubernetes in line with their specific business and technical needs.

* Level 5: Advanced testing and release patterns developed and in use, such as blue/green or canary

## Security

With all the many attack vectors that have to be mitigated remotely in a cloud-native context, it is imparative to have a security-first posture for all aspects of the application lifecycle (including software delivery and ongoing operation/maintenance).

* Level 1: Default security settings will be used and will work in pre-production. You’ll spend time identifying your open source security posture and conduct a security POC of the pre-production environment so that both Dev, Ops and security understands what is required in cloud native workloads.

* Level 2: Your team needs to focus on who is responsible for Kubernetes cluster security and how it will be managed. That will require the inclusion of the security team.

* Level 3: Your risk tolerance will impact at what level you are focused on cloud native security training so you are actively skilling people.

* Level 4: By this level, security is involved in design and deployment, you will enforce security in your cloud native environment. Your organization is committed to security with full understanding of policies and regulations both inside and outside of the organization.

* Level 5: You will be actively developing security internally, with the community and regulators.

## CNCF Certifications

Cloud Native Computing Foundation (CNCF) serves as the vendor-neutral home for many of the fastest-growing open source projects, including Kubernetes, Prometheus, and Envoy.

In order for you to build a sustainable ecosystems for cloud native infrastructure is it important to have your team invest in the CNCF Certifications.

Organizations may wish to consider the CKA and CKAD exams around level 2 and 3; and the CKS around level 4.

[**Certified Kubernetes Administrator (CKA)**](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/)

* This program provides assurance that CKAs have the skills, knowledge, and competency to perform the responsibilities of Kubernetes administrators.

[**Certified Kubernetes Application Developer (CKAD)**](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/)

* This exam certifies that users can design, build, configure, and expose cloud native applications for Kubernetes.

[**Certified Kubernetes Security Specialist (CKS)**](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)

* This program provides assurance that a CKS has the skills, knowledge, and competence on a broad range of best practices for securing container-based applications and Kubernetes platforms during build, deployment and runtime. CKA certification is required to sit for this exam.
