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

### Cost

In level 4, you’ll want to focus your team on cloud cost optimization. How can you improve your infrastructure to reduce cost and how can you demonstrate this to the business. The finance team will not want to understand per cluster costs, but instead how you’ve made changes to reduce costs or why you need more capacity. Use tools that help you demonstrate cloud and Kubernetes cost optimization.


## <i class="fas fa-users"></i> People

### People Overview

As you improve, you are shifting competency to the development team for them to self-service. Full commitment from leadership.

### Organizational Change

Cloud is now the default infrastructure for all services. The business is now requesting services from DevSecOps vs. requesting traditional servers.

### Teams and Decentralization

As the platform becomes more established, you can really start the process of decentralization. You can work on the development of a self-service portal incorporating the policies and processes of your organization to enable developer service ownership.

### Security

By this level, security is involved in design and deployment, you will enforce security in your cloud native environment. Your organization is committed to security with full understanding of policies and regulations both inside and outside of the organization.

### Developer Agility

Feedback is extended from application metrics through to platform and non-functional requirements with clear mapping of value streams to technological implementation. Developers are able to quickly test complex scenarios with many unknowns, cloud and application risks are easily and quickly identified and patched.

### Upskilling Developers

Developers are more sophisticated and Kubernetes is widely adopted by multiple groups in different business areas, with a body of knowledge developing and actively shared including integration and release processes. Developers and cluster owners are actively expanding Kubernetes in line with their specific business and technical needs.

### CNCF Certifications

Organizations may wish to consider the CKS around level 4.

#### Certified Kubernetes Security Specialist (CKS)
This program provides assurance that a CKS has the skills, knowledge, and competence on a broad range of best practices for securing container-based applications and Kubernetes platforms during build, deployment and runtime. CKA certification is required to sit for this exam.

## <i class="fas fa-cogs"></i> Process

### Process Overview

The governance model in place will support DevSecOps. You have guardrails in place to support agile software development. You will establish an application services library. You will also set policy around container usage for example auto-scaling policies or HPC.

### CI/CD

You will measure your release velocity and cadence to make improvements.

### Change Control

You have continuous delivery, but no continuous deployment to production - you still have a gate to production that requires operator approval.

### Security

Ensure security remediation is automated and/or identified automatically with remediation advice.

### Audit and Logs

Audit and alerts become mainstream and are made mandatory across applications.

## <i class="fas fa-edit"></i> Policy

### Policy Overview

You now have defined SLAs around policies and remediation.

### Policy Creation

Customize policies based on your business needs and minimize exceptions.

### Compliance

Expansion of policy tooling to include applications such as traffic proxies, service mesh, message buses and Linux. This will broaden the scope of managed policies, but it will also help in having them under control by way of declarative configurations.

## <i class="fas fa-server"></i> Technology

### Technology Overview

You’ve got full control over your environment, and you’ve built your confidence, with rapid adoption of cloud native patterns for new applications and platforms. You’ve also gained organizational commitment to cloud native and this is adding to your momentum. You’re starting to feel like you’ve “crossed the chasm.”

### Infrastructure

Kubernetes and its API has become extremely familiar to you. With your infrastructure and IaC tooling, you’ll likely find yourself investigating ClusterAPI and using that for deploying and managing the lifecycle of your clusters. As you also look to further refine control of your platforms, you’ll work to implement policy for your infrastructure control plane and other infrastructure controllers.

### Container and Runtime Management

With your sources of information you've gained from Level 3, your goal is to further integrate your data sources and gain visibility along with alerting. This closes the feedback loop on runtime and operations and allows you to respond quickly to unplanned events.

### Application Patterns and Refactoring

Microservices have become the preferred pattern for applications. The use of APIs is expanding within the organization, and other internal systems may be exposed and consumed, and they are available for general consumption, open across the organization via a service mesh. The organization becomes data-centric and API-centric, and data can be more easily consumed.

### Application Release and Operations

Not only are you using GitOps operators for rapid deployment, but you may also be using them for development and test purposes. You’ll be expecting most of your software to be packaged with Helm with the feedback loop being closed as quickly as possible to reduce configuration drift.

### Security and Policy

Apply your policy against production in case you haven’t already. You’ll continue to tune your policies in production.

### Testing and Issue Detection

As your environment becomes more complex in production, some issue remediation may require adjusting your policy-as-code or components of your Infrastructure as Code, as well as your application. Issues may relate to more than one application so you will aggregate across applications to determine trends. These may relate to bugs such as memory leaks, as well as security or policy issues. Your remediation may be to fix them at source, ideally as ‘far left’ as possible, or otherwise building automation capable of fixing them when they occur, and tuning it over time.
