---
title: 如何做出贡献
linkTitle: "贡献"
toc_hide: true
menu:
  main:
    weight: 30
description: 欢迎！我们很高兴您想要为Cartografos工作组做出贡献。
---

## 简介

Cartografos工作组旨在提供工具，帮助采用者和终端用户在CNCF领域和更广泛的云原生生态系统中进行导航。

我们希望通过与CNCF内外的团体合作，为用户提供有效和实用的指导，帮助他们了解云原生生态系统。

我们与 CNCF 各个不同水平的项目互动- 沙盒、孵化和毕业，以确保有效和准确地表达相关的信息，并参考CNCF 所有技术咨询小组的反馈。我们还提供一个供验证、讨论和反馈的供应商中立论坛。

在您开始工作时，您是最有资格向我们提供有关工作组需要帮助的领域的反馈意见的人。这包括：

- 我们文档中的不足
- 工作以定义新的工件（artifact）
- 与CNCF及其项目内的TAG和SIG进行接触

## 贡献

我们鼓励每个人向工作组的工件提出变更、添加和改进的建议。我们采用由CNCF管理的社区驱动流程来开发和改进工件。欢迎所有符合工作组目的和章程的参与者做出贡献。任何想要做出贡献的人都可以提交GitHub issue 或创建拉取请求 (pull request)。

除了为工件和文档做出贡献外，我们非常欢迎您以以下方式提供帮助：

- 创建或为工作组贡献工件，帮助实现工作组帮助导航云原生生态系统的使命
- 为现有工件做出更新的贡献
- 您希望看到的新工件和改进的想法
- 文档
- 问题分类
- 通信/社交媒体/博客文章
- 发布管理

并不是所有事情都通过GitHub拉取请求完成。请参加我们的会议或联系我们，讨论如何合作。

## 参加会议

欢迎每个人参加我们的任何会议。我们每个月的第二个星期二在美国东部时间下午6点举行定期社区会议。

如想参加工作组，请在 CNCF 的社区平台 https://community.cncf.io/ 上注册并加入社区群组 https://community.cncf.io/cncf-cartografos-working-group/。
会议列表也在同一页上，您需要在您想参加的每次会议前确认您要出席：https://community.cncf.io/cncf-cartografos-working-group/。

The first time you come, introducing yourself is more than enough. Over time, we hope that you feel comfortable voicing your opinions, giving feedback on others’ ideas, and even sharing your own ideas, and experiences.
第一次参加时，自我介绍就足够了。随着时间的推移，我们希望您畅所欲言地表达您的意见，给予反馈，甚至分享您自己的想法和经验。

## Ask for Help

The best way to reach us with a question when contributing is:

- On the original GitHub issue
- In GitHub Discussions within the repository
- Our CNCF Slack channel - # cartografos-wg
- And of course, in person at a meeting

## Contribution Flow

Outline of what a contributor's workflow looks like:

- Fork it (<https://github.com/cncf/cartografos/fork>)
- Create a branch from where you want to base your work (usually main). Example git checkout -b my-new-feature)
- Make your changes and arrange them in readable commits.
- Commit your changes (Ex. `git commit -am 'Add some feature'``)
- Push to the branch (Ex. git push origin my-new-feature)
- Make sure branch is up to date with upstream base branch (eg. main)
- Create a new Pull Request (PR)

## Submitting a PR

Once you have updated your changes in your branch, you will open a PR to the upstream cartografos repo.
Before opening the PR ensure you have rebased on the latest upstream.
If other commits are pushed upstream before your PR is merged, you will also need to rebase again before it will be merged.
For general advice on how to submit a pull request, please see [Creating a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) on GitHub.

## Contributor Ladder

This contributor ladder outlines the different contributor roles within the working group, along with the responsibilities and privileges that come with them. Community members generally start at the first levels of the "ladder" and advance up it as their involvement in the working group grows. Our working group members are happy to help you advance along the contributor ladder.

### Participant

A Working Group Participant engages with the group and its community, contributing their time, thoughts, etc. Community participants are usually users who have stopped being anonymous and started being active in group discussions.

Responsibilities:

- Must follow the CNCF Code of Code of Conduct

How users can get involved with the community:

- Participating in community discussions
- Helping other users
- Submitting and commenting on issues
- Providing feedback on new artefact releases
- Attending community events

### Contributor

A Working Group Contributor contributes directly to the group and adds value to it. People at the Contributor level may be new contributors, or they may only contribute occasionally.

Responsibilities include:

- Follow the CNCF Code of Code of Conduct
- Follow the working group contributing guide
- Requirements (one or several of the below):
- Report and sometimes resolve issues
- Occasionally submit PRs
- Contributes to artifacts
- Show up at meetings
- Answer questions from other community members
- Submit feedback on issues and PRs
- Reviews artifact updates and provides feedback
- Runs or helps run events
- Promote the working group in public
- Helps run the working group infrastructure

### Reviewer

A Reviewer has responsibility for specific assets, documentation, or other working group areas. They are collectively responsible, with other Reviewers, for reviewing all changes to those areas and indicating whether those changes are ready to merge. They have a track record of contribution and review in the working group.

Reviewers are responsible for a "specific area." This can be a specific artifact, chapter of documentation, or other clearly-defined group artifact that is smaller than an entire repository. Most often it is one or a set of directories in one or more Git repositories. The "specific area" below refers to this area of responsibility.

Reviewers have all the rights and responsibilities of a Contributor, plus:

- Responsibilities include:
- Following the reviewing guide
- Reviewing most Pull Requests against their specific areas of responsibility
- Helping other contributors become reviewers

Requirements:

- Experience as a Contributor
- Is a working group member
- Has demonstrated in-depth knowledge of their specific area, ideally having authored or significantly contributed to the artifact in their specific area.
- Commits to being responsible for that specific area
- Is supportive of new and occasional contributors and helps get useful PRs in shape to commit

Additional privileges:

- Be an approver for pull requests in specific directories
- Can recommend and review other contributors to become Reviewers
The process of becoming a Reviewer is:

- The contributor is nominated by opening a PR against the appropriate repository, which adds their GitHub username to the OWNERS file for one or more directories.
- At least two members of the team that owns that repository or main directory, who are already Approvers, approve the PR.

### Maintainer

Maintainers are very established contributors who are responsible for the entire working group. As such, they have the ability to approve PRs against any area of the repository, and are expected to participate in making decisions about the strategy and priorities of the working group.

A Maintainer must meet the responsibilities and requirements of a Reviewer, plus:
Responsibilities include:

- Mentoring new Reviewers
- Writing refactoring PRs
- Participating in CNCF maintainer activities
- Determining strategy and policy for the working group
- Participating in, and leading, community meetings

Requirements

- Demonstrates a broad knowledge of the working group across multiple areas
- Is able to exercise judgement for the good of the working group, independent of their employer, friends, or team
- Mentors other contributors
- Can commit to spending time working on the working group

Additional privileges:

- Approve PRs to any area of the working group
- Represent the working group in public as a Maintainer
- Communicate with the CNCF on behalf of the working group
- Have a vote in Maintainer decision-making meetings

Process of becoming a maintainer:

- Any current Maintainer may nominate a current Reviewer to become a new Maintainer, by opening a PR against the root of the cncf/cartografos repository, adding the nominee as an Approver in the OWNERS file.
- The nominee will add a comment to the PR testifying that they agree to all requirements of becoming a Maintainer.
- A majority of the current Maintainers must then approve the PR.

## Contributing to the Website

We use [Hugo](https://gohugo.io/) to format and generate the Maturity Model website, the
[Docsy](https://github.com/google/docsy) theme for styling and site structure,
and [Netlify](https://www.netlify.com/) to manage the deployment of the site.
Hugo is an open-source static site generator that provides us with templates,
content organisation in a standard directory structure, and a website generation
engine. You write the pages in Markdown (or HTML if you want), and Hugo wraps
them up into a website.

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

### Setting up a local instance

Install a local copy of the Cloud Native Maturity Model site with these instructions. Note you must have [npm](https://www.npmjs.com/) and [Hugo](https://gohugo.io/) installed.

```
git clone https://github.com/cncf/cartografos.git
cd cartografos
git submodule update --init --recursive
cd website
npm install
```

You can then run the site using `hugo server`.
