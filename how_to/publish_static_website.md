---
menuTitle: Publish Static Website
weight: 1.1
---

# Publish Static Website

It is possible to publish a regular static HTML-based website without a single [Markdown](https://en.wikipedia.org/wiki/Markdown) file at all. Just place your static website files into a GitHub repository and publish it using **mddocs**. 

It is similar to [GitHub Pages](https://pages.github.com/), but allows you to publish a website from an arbitrary repository and repository branch. GitHub Pages demands the repository to be named `<account>.github.io` and publishes only the main branch of the repository.

Let's publish a static website repository using the website example:

### 1. Fork example repository

[Cloud Academy](https://cloudacademy.com/) has published a good static website example that can be found in the [static-website-example](https://github.com/cloudacademy/static-website-example) repository. Let's fork it into our own repository: 

![set up a plan](./../images/how-to/publish-static-website/mddocs-1-fork-repo.png)

### 2. Grant an access to the repository

```md
Note: If the Mddocs GitHub Application has an access to `All repositories` there is no need to grant an access explicitly.
```

Goto to the [Installed GitHub Apps](https://github.com/settings/installations), find `Mddocs` installation and grant an access to the forked repository:

![set up a plan](./../images/how-to/publish-static-website/mddocs-2-provide-access.png)


### 3. Goto mddocs.io, locate the repository card

