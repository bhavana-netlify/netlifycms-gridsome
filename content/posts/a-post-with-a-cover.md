---
title: "Gatsby 101: Features, Benefits, and Trade-Offs from the Netlify Blog By
  Jason Lengstrof"
date: 2019-01-07T00:00:00.000Z
published: true
tags:
  - Markdown
  - Cover Image
cover_image: /images/uploads/gatsby-blog.png
description: >-
  Whether you’re looking to build a website or a full-blown web app,
  [Gatsby](https://github.com/gatsbyjs/gatsby#readme) has been rising steadily
  in popularity as a meta-framework for building with React on the web. Many
  developers love it because it lets them work with modern tools with fast
  startup times, and users love it because the websites are extremely fast to
  load and navigate.


  In this article, we’ll take a look at **what Gatsby is, why it’s popular, and how it’s different from other tools in the web development space.**
---
## What is Gatsby?

**Gatsby is a meta-framework built on top of React that specializes in producing fast-loading, fully interactive Jamstack sites.** It’s popular for its extensive plugin ecosystem, powerful integrations with virtually any API and data source, excellent documentation, and pleasant developer experience.

> If you’re new to the Jamstack, I wrote an overview to get you up to speed: **[WTF is the Jamstack?](https://www.learnwithjason.dev/blog/wtf-is-jamstack/)**

## What features should I know about?

Because Gatsby is a meta-framework on top of React, there are very few limitations to what you can build with it — if you can build it with React, you can most likely build it with Gatsby. However, **Gatsby adds powerful features on top of React that improve developer experience, site performance, and overall shipping velocity.**

### Gatsby allows you to bring your data from anywhere.

Probably the largest draw for Gatsby is its ability to load data from virtually any data source into a uniform data layer. A thriving ecosystem of [source plugins](https://www.gatsbyjs.org/plugins/?=gatsby-source) give you the power to integrate with SaaS solutions and third-party tools with minimal configuration and [API support for adding any custom data](https://www.gatsbyjs.org/docs/node-apis/#sourceNodes) to Gatsby’s data layer mean you’re able to build websites with a uniform developer experience no matter where the data comes from.

This means **your team doesn’t have to choose between a pleasant content management system for content managers *or* a pleasant workflow for developers** — you can use whatever tools you like best for managing content and developers are able to build sites with it using a modern React and GraphQL workflow.

### Gatsby gives you fantastic performance out of the box.

Gatsby is designed with performance as a first-class focus. The build process is optimized to maximize site performance through multiple strategies, including:

* Effective code splitting to serve only the necessary code for each page
* Inlining of critical assets
* Heavy image optimization to reduce asset sizes and lazy load images
* Smart preloading of assets to reduce load times during navigation

**Gatsby starts out by creating a very fast site — developers start at 💯 and have all the tools to *keep* it fast.** This is a decent amount of work that comes built into Gatsby, which helps save time and [makes the right thing the easy thing](https://lengstorf.com/right-thing-easy-thing/) when it comes to performance.

### Gatsby has an extensive open source ecosystem.

Gatsby’s greatest strength is the open source community. A solid collection of [API hooks](https://www.gatsbyjs.org/docs/node-apis/) enable developers to customize Gatsby at every step of the build process, such as loading data into Gatsby, transforming data from one format to another, or adding third-party tools.

**The Gatsby community has [created over 2,000 plugins](https://www.gatsbyjs.org/plugins/), which means you’re usually able to find a ready-made tool to accomplish your tasks.**

### Gatsby’s documentation is world-class.

**The [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/) is the gold standard for open source documentation.** It’s clear, comprehensive, and provides context not just on what Gatsby is doing, but on everything from setting up your development environment to quickstarts for the underlying tools.

This has been one of Gatsby‘s biggest successes, because it makes Gatsby accessible to beginners and seasoned devs alike.

## What are the downsides of Gatsby?

Every decision has trade-offs, and web development frameworks are no exception. Gatsby is extremely powerful, but it does come with a set of opinions and limitations that it’s good to be aware of.

### Gatsby has a steep learning curve.

If you’re new to development, **Gatsby can introduce a pretty steep learning curve.** The starter project introduces not just React, but GraphQL, Gatsby-specific APIs, Markdown, and both client-side JavaScript and Node.

For developers who are familiar with some or all of these technologies, Gatsby’s setup is intuitive and convenient, but for new developers it can feel extremely overwhelming.

### Gatsby has a lot of magic.

Gatsby packs a huge amount of value into its default configuration by effectively creating a killer preset for the underlying tools that Gatsby uses. In most cases, this is incredibly convenient and a massive boost to developer productivity. However, in cases where something goes wrong or you find yourself needing to change underlying defaults, **it can be tricky to figure out where Gatsby ends and the underlying tools begin.**

To insert a little bit of personal opinion here, though, if you find yourself frequently fighting against Gatsby’s defaults, it may be worth examining *why* that’s happening. Many people I’ve seen frustrated by changing Gatsby internals were struggling to make changes to suit their preferences rather than hitting real problems with Gatsby.

### Plugins are spread out and not always high quality.

The ecosystem is one of the best things about Gatsby, but it also means that **building Gatsby sites often involves bouncing between different GitHub repos for documentation** because each thing you need is built and maintained by someone else. This also means that it’s hard to know if the plugin you’re using actually works. (You can check npm usage stats and GitHub issues to see when a plugin is not used or has problems, but this can feel cumbersome.)

To be fair, this is more of a generic open source trade-off than a Gatsby-specific one.

(It’s also worth pointing out that the flipside of this coin is waiting helplessly for a company to get around to building that thing you really need that’s been on their product roadmap for three years with “coming soon!” in bold. Everything has trade-offs.)



## How do I get started with Gatsby?

**If you’re ready to get started with Gatsby, here are some helpful resources:**

* Learn more about Gatsby in the [official Gatsby tutorial](https://www.gatsbyjs.org/tutorial/).
* Use the [Gatsby optimization checklist to make your builds fast](https://www.netlify.com/blog/2020/06/11/5-optimizations-for-faster-gatsby-builds/?utm_source=blog&utm_medium=gatsby-101-jl&utm_campaign=devex).
* Learn how to [migrate a WordPress site to the Jamstack with Gatsby](https://www.netlify.com/blog/2020/03/23/migrate-your-wordpress-site-to-the-jamstack/?utm_source=blog&utm_medium=gatsby-101-jl&utm_campaign=devex).
* Create a copy of Gatsby’s default starter on your own GitHub, GitLab, or Bitbucket account and deploy it in a couple clicks using our Deploy To Netlify button:[](http://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-default&utm_source=blog&utm_medium=gatsby-101-jl&utm_campaign=devex)