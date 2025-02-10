---
title: "Creating Your First Hugo Page"
date: 2025-02-10
author: "Maria Hryntus"
tags: ["Hugo", "Static Sites", "Getting Started"]
---

## Introduction  

Hugo is a fast and flexible static site generator that makes it easy to create and manage content. In this guide, you'll learn how to create your first page in a Hugo project.  

## Prerequisites  

Before you start, make sure you have created a new Hugo site (`hugo new site my-site`).   

## Step 1: Create a New Page  

To create a new page, use the following command inside your Hugo site directory:  

```sh
hugo new content index.md
```

## Step 2: Edit the Page

Open the content/index.md and update it with your text. Use the formating of this page as an example or copy the sample later. 

```sh
---
title: "My First Hugo Page"
date: 2025-02-10
draft: true
---

Welcome to my first Hugo page! Hugo makes it easy to create and publish content quickly.
``` 

## Step 3: Start the Hugo Server

To preview your site, run:

```sh
hugo server
``` 

This will start a local development server at [http://localhost:1313/](http://localhost:1313/), where you can see your new page in action.

## Step 4: Publish Your Page

To publish the page, commit your changes to GitHub and merge them as required. After the merge is completed, your changes will be available on your deployed website. 