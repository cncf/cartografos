# Cloud Native Maturity Model - Policy

## Navigation

The Cloud Native Maturity Model is composed of five separate documents - the [Prologue](./prologue.md) and the four key reference documents:

* [People](./people.md)
* [Process](./process.md)
* [Policy](./policy.md)
* [Technology](./technology.md)

## Introduction

The Cloud Native Maturity Model covers four major dimensions - People, Process, Policy and Technology. This paper addresses policy, the critical implementation of internal requirements, and compliance to external regulations. Your goal as a cloud native practitioner should be to implement policies that enable and encourage shift left security. As your maturity grows, you will seek to automate policy enforcement in CI/CD and continuously monitor against policies in production.

We recognize policy adoption is a gradient. Every organization has a different risk appetite. Use this document as a guide to how you can define and enforce policy. By level 5, you will have achieved full policy maturity, however your mileage may vary.

* Level 1: You will have a limited set of documented policies in place to support services you're building in the cloud.

* Level 2: As your services approach production, you have initial policies agreed as standard and these are mostly documented.

* Level 3: You will implement policy-as-code and build this into your CI pipeline.

* Level 4: You now have defined SLAs around policies and remediation.

* Level 5: Based on your learnings, you will refine your policies as your organization achieves maturity, taking advantage of technologies such as machine learning in order to improve detection and enforcement.

## Policy Creation

You will need to translate your organization’s policies and compliance requirements to your cloud native environment.

* Level 1: Spend time understanding your application's functional and architectural requirements.

* Level 2: Define initial resource metrics and start collecting data.

* Level 3: Create policies based on metrics refined around security, efficiency and reliability.

* Level 4: Customize policies based on your business needs and minimize exceptions.

* Level 5: Contribute policies to the open source community and active engagement with regulators and other external stakeholders.

## Compliance

You will need policies in place to achieve compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve.

* Level 1: Spend time understanding your compliance requirements: CIS, NIST, PCI for example. Design SLOs and priorities for compliance. This will take time and may not be a pre-production requirement, but will increase as you move to production.

* Level 2: Initial auditing, carried out manually or through simple scripts.

* Level 3: Policy compliance and auditing carried out through automated means on Kubernetes. This will likely include initial development of policy-as-code.

* Level 4: Expansion of policy tooling to include applications such as traffic proxies, service mesh, message buses and Linux. This will broaden the scope of managed policies, but it will also help in having them under control by way of declarative configurations.

* Level 5: Compliance never ends! You will tighten the feedback loop with stakeholders and take advantage of advanced machine learning and other tooling to understand what is normal for your environment and ensure visibility of anomalous conditions in a large volume of compliance data.
