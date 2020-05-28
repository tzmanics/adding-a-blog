---
title: jammin-on-the-jamstack
description: Have you heard about Scully?
published: true
date: "2020-81-22"
authors:
  - Tara Z. Manicisc
---

# Jammin' on the Jamstack

We want to make your development process as seamless and easy as possible. My goal is to hone in on working with Angular and Netlify. One way I realized we could do this was to take advantage of [Angular Schematics](https://angular.io/guide/schematics) and Angular's [ng add](https://angular.io/cli/add) functionality. Let me break down what these two sets of words mean.

- [**Schematics**](https://angular.io/guide/schematics): Schematics allow you to programmatically add to and edit a project to incorporate tooling and/or features. This can cut out a lot of steps in project setup and help customize projects to automate common practices. It does this by creating a virtual file system, or [tree](https://angular.io/guide/schematics-authoring#schematics-concepts), checking to make sure your changes don't break the project, then applying the changes.

- [**`ng add`**](https://angular.io/cli/add): This CLI command incorporates a library into your project by installing it, and running its schematics (if they exist).

In making this `v1` of the [Netlify schematics](https://github.com/tzmanics/netlify-schematics) I had to search for a lot of reference pieces and glue them together. I also had some great help from [Mike Brocchi](https://twitter.com/brocco) and [Justin Schwartzenberger](https://twitter.com/schwarty) on [ngBS](https://twitter.com/ngBS_show). Not everyone can be fortunate enough to have direct help from someone who helped write the CLI. So, I wanted to create a resource that went straight into the process, helped you create a quick schematics project, and give you my collected knowledge as succinctly as possible.

In this first post we'll look at the current [Netlify schematics](https://github.com/tzmanics/netlify-schematics/) and how to add them to your project. Then you can follow along in a couple other posts to learn the process and make your own schematics. Here's what is covered in the other posts in this series:
