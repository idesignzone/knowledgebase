---
title: Gridsome Setup
date: 2020-01-01
slug: gridsome-setup

---
## Local Installation

To install Gridbox locally in your computer, Open env.development file in root of the project and change the URLS to your WordPress installation then open a terminal and navigate to project folder. now run the following commands:

    yarn install

wait until all the dependency packages are installed and then run:

    gridsome develop

this will run Gridsome in development mode.

## Deploy to Netlify

Netlify is an excellent solution for deploying and hosting Gridsome sites. Netlify is a unified platform that automates your code to create high-performant, easily maintainable sites and web apps. They provide continuous deployment (Git-triggered builds), an intelligent, global CDN, full DNS (including custom domains), automated HTTPS, asset acceleration, and more.

Their free tier includes unlimited personal and commercial projects, HTTPS, continuous deployment from public or private repos and more. Here are a few ways to deploy your Gridsome applications to Netlify:

**From your Git repository**

To deploy your Gridsome site to Netlify, go to your [Netlify app](https://app.netlify.com/) and click `New site from Git`. Select your project repo from either GitHub, GitLab, or Bitbucket.

Add these build settings:

* **Build Command:**`gridsome build`
* **Publish directory:**`dist`

And click `Deploy Site` to deploy your application.

## Deploy to Vercel

[Vercel](https://vercel.com/) is a cloud platform that enables developers to host Jamstack websites and web services that deploy instantly, scale automatically, and require no supervision, all with zero configuration. They provide a global edge network, SSL encryption, asset compression, cache invalidation, and more.

To deploy your Gridsome app with a [Vercel for Git Integration](https://vercel.com/docs/git-integrations), push your code to a repository on GitHub, GitLab, or Bitbucket.

Import the project into Vercel using the [Import Flow](https://vercel.com/import/git). During the import, you will find all relevant [options](https://vercel.com/docs/build-step#build-&-development-settings) preconfigured for you.

After your project has been imported, all subsequent user pushes to branches will generate [Preview Deployments](https://vercel.com/docs/platform/deployments#preview), and all users changes made to the [Production Branch](https://vercel.com/docs/git-integrations#production-branch) (commonly "main") will result in a [Production Deployment](https://vercel.com/docs/platform/deployments#production).

Once deployed, you will get a URL to see your app live, such as the following: [https://gridsome.now-examples.now.sh](https://gridsome.now-examples.now.sh "https://gridsome.now-examples.now.sh").