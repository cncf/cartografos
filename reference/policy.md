# Cloud Native Maturity Model - Policy

## Navigation

The Cloud Native Maturity Model is composed of five separate documents - the [Prologue](./prologue.md) and the four key reference documents:

* [People](./people.md)  
* [Process](./process.md)  
* [Policy](./policy.md)  
* [Technology](./technology.md)

## Introduction

The Cloud Native Maturity Model covers four major dimensions - People, Process, Policy and Technology. This paper addresses policy. Your goal of cloud native should be to implement policy to embrace shift left security. Across all levels, you will seek to implement policies and automate enforcement in CI/CD and continuously monitor against policies in production.

We recognize policy is a gradient. Every organization has a different risk appetite. Use this as a guide to how you can enforce policy. By level 5, you will have achieved full policy maturity, however your mileage may vary.

* Level 1: You will have a limited set of documented policies in place to support services.

* Level 2: You now have initial policies agreed as standard and these are mostly documented.

* Level 3: You will implement policy-as-code and build this into your CI pipeline.

* Level 4: You now have defined SLAs around policies and remediation.

* Level 5: Based on your learnings, you will refine your policies as your organization achieves maturity, taking advantage of machine learning.

## Policy Creation

You will need to translate your organization’s policies and compliance requirements to your cloud native environment.

* Level 1: Spend time understanding your application requirements.

* Level 2: Gather resource metrics.

* Level 3: Create policies based on metrics around security, efficiency and reliability.

* Level 4: Customize policies based on your business needs and minimize exceptions.

* Level 5: Contribute policies to the open source community and active engagement with regulators and other external stakeholders.

## Compliance

You will need policies in place to achieve compliance especially in highly regulated industries. For compliance, there is a gradient of what you will achieve:

* Level 1: Spend time understanding your compliance requirements: CIS, NIST, PCI for example. Design SLOs and priorities for compliance. This will take time and may not be a pre-production requirement, but will increase as you move to production.

* Level 2: Initial auditing, carried out manually or through simple scripts

* Level 3: Policy compliance and auditing carried out through automated means on Kubernetes.  This will likely include initial development of policy as code with projects such as Open Policy Agent and Kyverno.

* Level 4: Expansion of policy tooling to include applications such as traffic proxies, service mesh, message buses and Linux.

* Level 5: Compliance never ends! You will tighten the feedback loop with stakeholders and take advantage of advanced machine learning and other tooling to understand what is normal for your environment and ensure visibility of anomalous conditions in a large volume of compliance data.
