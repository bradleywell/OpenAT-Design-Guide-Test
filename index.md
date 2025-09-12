---
title: Home
layout: home
---

Many of the devices in the MMC library use the same components, but all use slightly different dimensions when adding the parts into the design. The designers frequently reference other, older designs that use the part for the correct dimensions to use, but there are so many different dimensions used that this leads to several different ‘standards’ being used across devices for the same part. This guide is an attempt to standardize the dimensions for parts across designs, and to serve as a central reference point for use designing devices. 

In the first section, the guide covers the commonly used commercial parts in MMC designs, and how to integrate them into 3D printed components. This includes the right size holes to use for screws, the best ways to secure a switch to a component, and what size openings to use for various USB connectors. 

The second section covers common design elements used in MMC devices, such as 3D printed threads, cotter pins, and shadow lines. This section focuses less on exact measurements and dimensions than the previous section, as the designer has control over the dimensions of all the components involved. Instead this section focuses more on the necessary design considerations and minimum/maximum sizes of the features.

The third section of the guide is primarily a link to the Hydra Research Design Rules for basic 3D printing tips, such as wall thicknesses, overhangs, and filet sizes. It also breaks out the section on printing overhanging holes for easy reference, and gives a brief overview of the printers used in the design of the devices mentioned in the guide, and how that affected the tolerances used in the guide. It also covers how these tolerances can be changed for other 3D printers to make them fit better.  


This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
