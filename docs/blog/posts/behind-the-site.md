---
authors: 
    - snake
categories:
  - Automation
  - Web Development
date: 2024-12-20
comments: true
---

# Behind the Tech Miami Site 

TechMiami.com is a static website generated via the MkDocs framework and specifically the Material theme. It combines the use of Markdown for content generation with a customizable and easy-to-configure website template that brings to life even basic ideas down on text. We chose this framework for the Tech Miami platform to demonstrate the use and viability of open-source Markdown-to-site frameworks like MkDocs and anothers in leveling the bar of entry to allow you to share your content on the web in a user-friendly and also comprehensive manner.

In this post, we will walk you through the basics of how TechMiami.com is set up, to be used as a learning resource for those who are also looking for a quick start to getting their own web resources created and deployed online. 

<!-- more -->

___

Framework 

- TechMiami.com domain purchased from GoDaddy.com (with domain protection) 
- Material MkDocs framework created for site generation and contained within project Github Repository 
- Github Pages enabled for repository 
- DNS Settings enabled for Github Pages connection to owned custom domain
- Github Actions workflow created to enable seamless CI/CD (Continuous Integration/Continuous Deployment)

At first glance, it may seem like a lot to understand how to go from aquiring a domain name to generating a website like this one, but we will make it easy to understand at least the process we followed in creating the web framework for this project


1. Purchase a GoDaddy domain name (consider domain protection)

2. Decide on the web framework you would like to build (must be static)

3. Create a Github repository to contain the website contents for your project 

4. In your Github repository, enable a Github Page to be created for the static website delivery content 

5. Link your Github Pages to your custom domain name by declaring it in Github Actions settings and adding the appropriate DNS settings in your DNS provider (GoDaddy)

6. Confirm that your DNS settings have been verified by Github

7. Create a Github Actions workflow that builds your MkDocs project programatically and pushes (need to enable Write Permissions) a deployable branch in the repository framework 

8. On commit, see your Markdown creations come to life and be deployed on your very own custom URL

9. Enable HTTPS  for your Github Pages-powered custom domain website


Check out our Github Repository for the full workflow details.
___
