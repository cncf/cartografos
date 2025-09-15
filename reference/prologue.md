
# Cloud Native Maturity Model \- Prologue

## Navigation

The Cloud Native Maturity Model is composed of six separate documents - this document, the [Prologue](./prologue.md), and the five key reference documents:

* [People](./people.md)  
* [Process](./process.md)  
* [Policy](./policy.md)  
* [Technology](./technology.md)
* [Business Outcomes](./business_outcomes.md)

# The Cloud Native Maturity Model: A Framework for Your Success

The Cloud Native Maturity Model is designed to support *you*—whether you're just beginning your cloud native journey, leading a team of practitioners, or are already an experienced expert. This model helps identify where you may need to invest in tools, processes, people, or policies. Most importantly, it bridges the gap between technical goals and business outcomes, enabling you to effectively communicate the value of your cloud native strategy to organizational leadership.

Developed by practitioners who have guided numerous organizations through cloud native transformations, the model addresses a common challenge: starting without a clear roadmap. Its purpose is to provide a structured, practical framework to guide your journey—from initial adoption to full maturity.

By aligning with the CNCF landscape, the model helps you unlock the full potential of cloud native technologies to build and operate scalable, resilient applications across public and hybrid cloud environments.

# **Cloud Native Maturity Model 4.0 (Beta) Now Available**

The beta release of Cloud Native Maturity Model (CNMM) 4.0 is here. The Cartografos Working Group has updated the model to reflect the rapid evolution of the cloud native ecosystem since its initial launch in 2021 and subsequent updates in 2022 and 2023\.

Version 4.0 introduces expanded coverage of AI, emerging technologies, and the organizational and cultural shifts required to succeed in today’s complex IT landscape. Critically, it continues to emphasize alignment between cloud native practices and business outcomes, ensuring organizations don’t just adopt technology—but do so with purpose and impact.

Cloud Native Must Serve the Business At its core, cloud native maturity must be driven by business requirements. No organization should adopt cloud native technologies without a clear connection to business goals. That’s why version 4.0 puts greater emphasis on what the business must consider to fully realize the benefits of cloud native.

Too often, technical conversations dominate cloud native initiatives—causing a disconnect between engineering and “the business.” But the business doesn’t care about Kubernetes for Kubernetes’ sake. It cares about managing risk, meeting compliance obligations, ensuring customer satisfaction and trust, and achieving cost efficiency.

While the CNMM still covers the full range of technology topics, it now begins each maturity level by framing the business and technology focus areas first. Then, it explores how these focus areas affect the four pillars: People, Process, Policy, and Technology. For the purposes of this model, “the business” includes anyone outside infrastructure, platform engineering, operations or development teams.

If you’re on the technology side, this model will help you translate cloud native concepts into business-relevant language—bridging the communication gap and building stronger alignment.

Shifting Left the Business Strategy It’s worth noting: in the early stages of maturity, technology naturally dominates. However, introducing policy, process, and enforcement earlier accelerates progress. This shift-left approach allows organizations to align technical decisions with business goals from the outset.

Importantly, cloud native isn’t always a guaranteed cost reduction—especially in the early stages. There’s a financial maturity journey involved. Organizations moving from CAPEX-heavy infrastructure to cloud-based OPEX models must rethink how they view cost. Early on, expenses may rise due to the need to maintain legacy systems while launching cloud native platforms.

That’s why FinOps practices are essential—particularly for enterprise-scale organizations. FinOps can serve as a strategic ally, helping finance and engineering collaborate to manage and optimize cloud spend as maturity grows.

The CNMM is designed to work alongside the Platform Maturity Model, offering both a top-down and bottom-up perspective. Together, they provide a layered view that supports strategic planning and tactical execution. This release also includes links to architectural references and resources from CNCF Technical Advisory Groups (TAGs) and other working groups.

We hope this beta release serves as a cornerstone reference for end users navigating cloud native adoption. As always, we welcome feedback and contributions to continuously evolve the model.

# **Where Are You in Your Cloud Native Maturity?**

We surveyed the CNCF community to understand where organizations see themselves on the cloud native maturity journey:

* 39% say they are in the middle of their journey  
* 19% are just getting started  
* 15% believe they’ve reached maturity  
* Another 15% fall within Level 2 and 12% within Level 4

These responses highlight that organizations are at all stages of adoption, reinforcing the need for continued education, resources, and frameworks to guide progress through the many phases of cloud native maturity.

When asked if they have the resources to make cloud native adoption successful, 54% said they need more support—a clear signal that many teams are still under-resourced.

Only 15% of respondents say their cloud native efforts are completely aligned with overall IT strategy, while 39% see some alignment, and 8% report almost none. Bridging this gap is critical for success.

When it comes to business drivers for cloud native initiatives, here’s what respondents identified:

* Agility – 85%  
* Scalability – 77%  
* Cost savings – 65%  
* Innovation – 46%  
* Customer experience – 27%

It’s important to note that cost savings—though commonly cited—may not be fully realized until later stages (Level 3 or 4\) of the maturity model. Early investments can temporarily increase spend before long-term efficiencies are achieved.

## **Target audience**

The main target for this model is broad and encompasses the following groups:

* Businesses that are embarking or starting down the path of digital transformation  
* Those who want to navigate the massive CNCF landscape to hone in on a framework model you can implement and trust  
* Open source and CNCF projects and practitioners wishing to use or contribute to the model  
* Leadership teams looking to understand the benefits of cloud native, scope of effort, and level of investment  
* Technologists wishing to get started with moving towards cloud native technologies who are keen to understand in more detail the journey ahead of them, as well as have further areas for investigation highlighted

## **How the model is divided up**

Developing a cloud native maturity model is not just a technology journey, but one which is influenced by five major areas:

1. Business outcomes \- What can the business expect to achieve from cloud native? How are you going to communicate the benefits to the CXO and/or business leadership?  
2. People \- How do we work, what skills do we require, what does our organization look like as we move through this process, and how do we weave security into how people work?  
3. Process \- What processes do we need, what technology is required and how do we map workflows and CI/CD using infrastructure as code (IaC) and how do we shift security as “far left” as possible?.  
4. Policy \- What internal and external policies are required to achieve security and compliance mandates? Do these policies reflect your business’s operating environment?  
5. Technology \- What technology is required for you to deliver on the benefits of cloud native and support people, processes and policy as well as the technology for CI/CD, adoption of GitOps, observability, security, storage, networking, etc.

## **But what if we don’t fit this model…**

Relax\! No project, organization or person is expected to match all of the details contained within the model, perfectly. It’s deliberately designed to cover many different scenarios; everything from startups to Fortune 100 companies. Take what is most relevant to you and your situation, and if this helps inspire you in (or indeed account for, but then rule out) any items or areas, then we consider this to be a success for you\!

*The aim of this model is not to be overly prescriptive, but rather to be a tool to help guide you on your journey. Cloud native transformation is not an exact science, but rather lives within your project, your organization, and of course takes place in a specific time and place.*

## **Prerequisites for the Cloud Native Maturity Model**

The first, and arguably most important, thing to do when adopting cloud native is to outline your business and technology goals, particularly what your business expects to gain from the exercise.

Few organizations start out with an entirely blank slate (often known as a greenfield). You may have something like the following:

* Your organization may range in age from a few months, years, decades or even longer. And may have a collection of technical debt.  
* You may have a considerable application, platform and infrastructure estate.  
* You may even have started a migration to cloud service providers, perhaps adopting a ‘lift and shift’ approach with your existing estate.

The most important thing you should have is a clear idea of the business outcomes you expect to achieve. These will be your ‘north star’, helping guide your decision making process.

## **When is the right time**

You may be ready to start your cloud native journey if you meet the following criteria:

### **Business Outcomes**

* Whether you are a startup choosing to build on the cloud or an enterprise organization adopting cloud native, there must be long term business goals that require the investment in cloud native. These goals may be derived internally from corporate strategy, or from outside from industry trends, or competitive market pressures.  
* Prioritized business goals must drive the decision making with all stakeholders aligned.  
* Organizations should have established meaningful processes for sharing information and results between business units.

### **People**

* You have significant separation between development and operations, with a clear staff delineation between infrastructure, cloud, application operations and development.  
* You have traditionally split your operations and infrastructure divisions and your application development departments. This may have been enforced by regulatory requirements.  
* This split may have worked well for you, and indeed may be mandated. But you may be finding additional challenges as much of your platforms become code and application oriented. You may find you require skills in your platform area that have traditionally belonged within your application area.

### **Process**

* Your application deployments may be done manually in many cases, or your release processes may take a very long time to complete, often with multiple attempts.  
* You may support multiple distributions of the same software and have trouble upgrading or evaluating without significant down-time.

### **Policy**

* Policy may be in the form of conventions and rules that are located external to the application and its platform, and are not enforced natively within your applications and runtime environment.  
* Policies might be disparate and built in silos; defense in depth parity might be more of an accident than deliberate.

### **Technology**

* You’ll likely have VM’s on demand.  
* Some automation scattered around.  
* You will have baseline security components such as SIEM, RBAC concepts, and a directory of some type.  
* You have some software packaging, but this could be inconsistent.  
* You’ll have perimeter security and perhaps some coarse network zoning at layers 1-4, but you may feel some anxiety and security practices.  
* Your experience with encryption may vary \- you might have some certificate authorities for example, but they may not be used extensively, with a high barrier to entry for many.  
* Your applications may rely on infrastructure solutions for high availability, which in turn may be more costly than you’d like  
* Your server estate could range from single physical or virtual servers with low levels of availability, through to highly available clusters. Scaling could be a real challenge and may require considerable investment in money, time and planning.  
* You may have started to dip your toe into a ‘Everything as Code’ model. i.e. started to script your infrastructure with Terraform.

## **The Cloud Native Maturity Model Journey**

There are five stages within the cloud native maturity model. While you may be in stage five for one application, at the same time, you may be at stage 2 for another. Keep that in mind as you identify your stage of maturity.

Through level 4, you've likely stood on the shoulders of giants. At level 5, you become the giant—there's no one left to stand on but you.

* [**Level 1 \- Build**](https://maturitymodel.cncf.io/level-1/) You have a baseline cloud native implementation in place and are in pre-production. Of importance, level one isn’t a lab or POC, you do have an implementation in place. It can be really hard to move from a build to operate stage.   
* [**Level 2 \- Operate**](https://maturitymodel.cncf.io/level-2/) The cloud native foundation is established and you are moving to production.  
* [**Level 3 \- Scale**](https://maturitymodel.cncf.io/level-3/) Your competency is growing and you are defining processes for scale.  
* [**Level 4 \- Improve**](https://maturitymodel.cncf.io/level-4/) You are improving security, policy and governance across your environment.  
* [**Level 5 \- Adapt**](https://maturitymodel.cncf.io/level-5/) You are revisiting decisions made earlier and monitoring applications and infrastructure for optimization.

In each of the following sections, we will highlight core concepts and discuss what this means in each stage of your maturity across people, process, policy and technology.

We welcome feedback from the community on the Cloud Native Maturity Model\!

## **Position on Included Technologies**

The Cloud Native Maturity Model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software.
