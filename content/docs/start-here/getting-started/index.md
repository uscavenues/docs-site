---
title: "Getting Started"
description: ""
summary: ""
date: 2024-01-10T11:02:06-08:00
lastmod: 2024-01-10T11:02:06-08:00
draft: false
menu:
  docs:
    parent: "start-here"
    identifier: "start-here-3756649371abe48b98bd98ebc4b734fd"
weight: 100
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

The Avenues website is built using <a href="https://nextjs.org/">Next.js</a>, which is subsequently built on top of <a href="https://react.dev/">React</a>, and is hosted on our <a href="https://github.com/uscavenues">GitHub</a>, using <a href="https://git-scm.com/">Git</a> as our version control system. Naturally, we use <a href="https://vercel.com/">Vercel</a>, also by the same company that develops Next.js, to deploy the website. If you are unfamiliar with any of these tools, feel free to browse the aforementioned websites to get a feel for our stack.

## Toolchain Installation

You will require the following tools to be able to work on the website:

 - A suitable terminal environment (<a href="https://iterm2.com/">iTerm2</a> on Mac or <a href="https://termius.com/">Terminus</a> on Windows)
 - A modern JavaScript version
 - <a href="https://nodejs.org/">Node.js</a> and <a href="https://www.npmjs.com/">NPM</a>
 - <a href="https://pnpm.io/">PNPM</a>
 - <a href="https://nextjs.org/">Next.js</a>

Also make sure Git and GitHub are working properly on your local machine as it will be the primary way of contributing to the website repository.

## Building Locally

To get up and running locally, first clone the respository:

```console
git clone https://github.com/uscavenues/site.git
```

Then `cd` into the repository, and run:

```console
pnpm install
```

This should install all the dependencies for building the website. Then run:

```console
pnpm run dev
```

This will create a **localhost** server that is directly accessible on your and only your local machine, meant for development. You can now navigate to `localhost:3000` (or whatever port it says) and you should have a fully-functioning development website for use during implementation.