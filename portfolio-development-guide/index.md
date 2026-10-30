
---
layout: default
title: Portfolio Development Guide
---

# Building My GitHub Pages E-Portfolio

## 1. Introduction

The purpose of this guide is to document the steps I followed to create my personal e-portfolio using GitHub Pages.

For Milestone I, I developed a personal website to showcase my educational background, professional experience, skills, and certifications. I used GitHub Pages along with the Jekyll Minimal theme to create and customize my website.

This guide provides an overview of the development process, including creating a GitHub repository, selecting a website theme, customizing the website configuration, organizing content using Markdown, and publishing the completed e-portfolio.

The following sections explain the steps I completed and include screenshots to illustrate the development process.



## 2. Creating a GitHub Pages Repository

The first step in developing my e-portfolio was creating a GitHub repository to host my personal website.

I used GitHub Pages, which allows users to publish websites directly from a GitHub repository. I named my repository `farhaanpathan.github.io`, following the required naming convention for a personal GitHub Pages website.

After creating the repository, I set up the project files needed to build and customize the website. This repository served as the foundation for my e-portfolio.



## 3. Selecting and Configuring the Jekyll Minimal Theme

After creating my GitHub repository, I configured my website to use the Jekyll Minimal theme. This theme provided a basic website layout that I could customize to create my personal e-portfolio.

To configure the theme and personalize the website, I used the `_config.yml` file located in the root directory of my repository.

The following configuration settings were used:

```yaml
title: Farhaan Pathan
logo: /assets/img/logo.png
description: Business Analyst and M.S. Supply Chain Analytics student passionate about data, technology, and process improvement. Experienced in business analysis, systems implementation, and cross-functional collaboration at Amgen and Gilead Sciences.
show_downloads: true
google_analytics:
theme: jekyll-theme-minimal
```

### 3.1 Customizing the Website Configuration

I customized several settings within the `_config.yml` file to personalize the appearance and information displayed on my website.

- **Title:** I added my name, Farhaan Pathan, to identify my personal e-portfolio.
- **Logo:** I specified the location of my profile image using the assets folder.
- **Description:** I added a professional summary highlighting my background in business analysis, supply chain analytics, and process improvement.
- **Show Downloads:** I enabled this setting to display the download links provided by the Minimal theme.
- **Google Analytics:** I left this field blank because I did not configure Google Analytics tracking.
- **Theme:** I specified `jekyll-theme-minimal` to tell GitHub Pages which theme to use.

These changes allowed me to personalize the website while maintaining the basic structure and layout provided by the Jekyll Minimal theme.

![Jekyll Configuration](../assets/img/milestone2/jekyll-configuration.png)



## 4. Customizing the Portfolio Content

After configuring the Jekyll Minimal theme, I began customizing the main page of my e-portfolio. The main content of the website is stored in the `index.md` file located in the root directory of my GitHub repository.

I used Markdown to organize and present my personal and professional information. This allowed me to structure the website into different sections while keeping the content organized and easy to navigate.

### 4.1 Adding Personal and Professional Information

I added information about my educational background, professional experience, certifications, and technical skills. These sections were designed to provide visitors with an overview of my qualifications, career experience, and areas of expertise.

### 4.2 Organizing Content Using Markdown

I used Markdown headings, paragraphs, bullet points, and hyperlinks to organize the information throughout the website. These formatting options helped create a consistent structure and made the portfolio easier to read.

### 4.3 Adding a Profile Image

I added a personal profile image to customize the appearance of the website. The image was stored in the `assets/img/` directory and referenced through the `_config.yml` configuration file.

This customization helped make the e-portfolio more personal and recognizable while maintaining the original layout of the Minimal theme.

![Portfolio Markdown](../assets/img/milestone2/portfolio-markdown.png)



## 5. Publishing the Website Using GitHub Pages

After completing the customization of my e-portfolio, I used GitHub Pages to publish my website online.

GitHub Pages is a hosting service that allows users to publish static websites directly from a GitHub repository. Since my repository followed the naming convention `farhaanpathan.github.io`, I was able to publish my personal website using my GitHub account.

### 5.1 Committing Changes to GitHub

After making changes to my website files, I saved and committed the updates to my GitHub repository. These changes included updates to the Markdown content, website configuration, and profile image.

Committing and pushing the changes allowed GitHub Pages to process the updated files and publish the latest version of my website.

### 5.2 Verifying the Published Website

After publishing the changes, I visited my GitHub Pages website to verify that the updates appeared correctly.

I reviewed the website to make sure my personal information, professional experience, educational background, certifications, and profile image were displayed as expected.

This final verification helped ensure that the published website accurately reflected the changes made to my repository.

[Visit My E-Portfolio](https://farhaanpathan.github.io)

![Final E-Portfolio](../assets/img/milestone2/final-portfolio.png)



## 6. References and Resources

The following resources were used to develop, customize, and publish my e-portfolio. These references provided guidance on Markdown formatting, Jekyll configuration, GitHub repository management, and website publishing.

### 6.1 GitHub Pages

GitHub Pages documentation was used to understand how to host and publish a personal website directly from a GitHub repository.

[GitHub Pages Documentation](https://docs.github.com/en/pages)

### 6.2 Jekyll Documentation

Jekyll documentation was used as a reference for understanding website configuration, themes, and Markdown-based content organization.

[Jekyll Documentation](https://jekyllrb.com/docs/)

### 6.3 GitHub Markdown Guide

The GitHub Markdown guide provided information on formatting headings, paragraphs, lists, hyperlinks, and images throughout the portfolio.

[GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

### 6.4 GitHub Repository

My GitHub repository contains the source files, configuration settings, images, and Markdown content used to build my e-portfolio.

[Farhaan Pathan GitHub Repository](https://github.com/farhaanpathan/farhaanpathan.github.io)

### 6.5 Published E-Portfolio

The completed e-portfolio can be accessed through the following GitHub Pages website.

[Visit My E-Portfolio](https://farhaanpathan.github.io)


