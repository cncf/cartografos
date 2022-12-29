---
title: How to Contribute
linkTitle: "Contribute"
toc_hide: true
menu:
  main:
    weight: 30
description: Welcome! Are you interested in contributing to the Cloud Native Maturity Model?
---

## Content Guidelines

*more info on this*

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
