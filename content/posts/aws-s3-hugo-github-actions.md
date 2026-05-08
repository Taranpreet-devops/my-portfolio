---
title: "Hosting a Static Website on AWS S3 Using Hugo and GitHub Actions"
date: 2026-05-08
draft: false
---

# Overview

In this project, I deployed a static website using Hugo, AWS S3, Route 53, and GitHub Actions.
The goal was to build a simple CI/CD workflow for static site hosting.

# Tech Stack

- Hugo
- AWS S3
- Route 53
- GitHub Actions
- Git
- Markdown

# Architecture

GitHub → GitHub Actions → S3 → Route 53

# What I Learned

- Configuring S3 static website hosting
- Managing DNS using Route 53
- Automating deployments with GitHub Actions
- Working with Git and GitHub repositories
- Writing infrastructure-oriented documentation

# Deployment Workflow

1. Write markdown content
2. Push changes to GitHub
3. GitHub Actions builds the Hugo site
4. Generated static files are uploaded to S3
5. Route 53 serves the site through the custom domain

# Future Improvements

- Add CloudFront CDN
- Enable HTTPS with ACM
- Add Terraform automation
- Configure cache invalidation
- Add monitoring and logging