---
title: jamstack-cong-rules
description: Angular didn't have a static site generator(SSG) yet? But, it does now!
published: true
date: "2020-05-27"
authors:
  - Tara Z. Manicisc
---

# Jamstack Conf Rules

## Netlify Build Plugins Are Here!

We are excited to announce the release of [Netlify Build Plugins](https://www.netlify.com/build/plugins/?utm_source=blog&utm_medium=bp-release-tzm&utm_campaign=devex) today! Build Plugins allow you to automate build tasks, customize your build process, and make your development process even easier. As a user of Build Plugins, you can take advantage of the one-click installs to [cache files](https://github.com/jlengstorf/netlify-plugin-gatsby-cache), [check for broken links](https://github.com/munter/netlify-plugin-checklinks), [trigger testing](https://github.com/tkadlec/netlify-build-plugin-speedcurve), and more. As a developer, creating Build Plugins keeps us in the realms of the familiar, relying on a plain 'ol JavaScript at its base.

Build Plugins are an additional piece of code that you can use by [adding them to your `manifest.yml` configuration file](https://docs.netlify.com/configure-builds/build-plugins/?utm_source=blog&utm_medium=bp-release-tzm&utm_campaign=devex#install-a-plugin) or clicking the 'Install' button on your [Build Plugins page](app.netlify.com/enable-beta). Then, when you deploy or build your Netlify site, the code will run in the background at a designated event of the [build process](https://docs.netlify.com/configure-builds/get-started/). Plugins we have now will [look for accessibility failures](https://github.com/sw-yx/netlify-plugin-a11y), [add instagram](https://github.com/philhawksworth/netlify-plugin-add-instagram), [check for misspelled brand words](https://github.com/tzmanics/netlify-plugin-brand-guardian), and even [check if you're deploying outside of your set deployment hours](https://github.com/neverendingqs/netlify-deployment-hours-plugin). That list is just skimming the surface of what you can do with Build Plugins.

Although I could talk about Build Plugins for days, I thought I'd share with you some great resources from the community and our team at Netlify instead. Here are some resources, a list of posts on creating and using plugins, followed by a list of Build Plugins available today!

## Build Plugins Resources

- [Netlify Build Plugins Documentation](https://docs.netlify.com/configure-builds/build-plugins/?utm_source=blog&utm_medium=bp-release-tzm&utm_campaign=devex)
- [Netlify Build repo](https://github.com/netlify/build)
- [Netlify Community on Build Plugins](https://community.netlify.com/c/Netlify-support/build-plugins)
- [Link to enable Build Plugins for your sites](app.netlify.com/enable-beta)

You can now find your Plugins page listed at the top of your Netlify dashboard.
