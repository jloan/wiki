---
layout: default
title: Wax
has_children: true
permalink: /wax/
nav_order: 4
---
# Minicomp/Wax

<img src="{{ '/assets/wax_screen.gif' | absolute_url }}"/>

## What is Wax?

**Wax is an extensible workflow for producing scholarly exhibitions with minimal computing principles.**  

It's comprised of: __a few Ruby gems__ for processing image data and associated metadata ([wax_tasks](https://github.com/minicomp/wax_tasks/), [wax_iiif](https://github.com/minicomp/wax_iiif/)), __a Jekyll theme__ ([wax_theme](https://github.com/minicomp/wax/)), and (hopefully soon!) a lot of __documentation and recipes__ for creating, deploying, and maintaining digital exhibitions.

**The exhibition sites created by Wax are static.**  

This means they consist of flat HTML, CSS, and JavaScript files that don't need to communicate in a complex way back to a server. This makes them cheaper, safer, and generally easier to maintain—as long as you're willing to learn some new skills.

**The skills needed to create Wax sites are fundamental.**  

This means they are largely transferable for use in other digital projects. 'Learning Wax' does not mean learning how to use a platform. It involves learning the basics of web development, data management, and [plain text editing](https://zapier.com/blog/beginner-ultimate-guide-markdown/) while leveraging a few great open source libraries and frameworks along the way.

**Wax keeps the collection presentation separate from the collection data.**  

The Wax workflow starts with making standardized image files and metadata records and builds around them, handling canonical information, scholarly content, and site styling differently and deliberately. This makes it easier for you or others to reuse and reimagine your collection data in other contexts, or to preserve the collection when it comes time to sunset the exhibition.

## Who is Wax for?

Wax was created for individuals and groups who either don't have or don't want to use a lot of resources to create their scholarly exhibitions. It's best suited for folks who are willing to take on some technical responsibility in exchange for a lot of flexibility.

This is to say that Wax has a relatively high but general-purpose learning curve. To get the most out of Wax, you should have some familiarity with:

- Using an interactive shell (e.g., Bash/Terminal) to install and interact with programs, files, and directories on your local computer.
- Using Git and GitHub to version control and collaborate on projects.
- Using Jekyll to generate static sites.
- Creating and normalizing data files (e.g., CSVs, JSON, YAML)
- Using file-naming conventions and best practices.
- Editing HTML, CSS, and some JavaScript.

**However, Wax is also great for teaching the skills above!** For examples of digital humanities pedagogy through the creation of Wax exhibitions, check out [this workshop](http://web.sas.upenn.edu/dream-lab/2018/09/14/minimal-computing/), [this GitHub repository](https://github.com/stylerevolution/stylerevolution.github.io), and [this custom Wax site](https://stylerevolution.github.io/).

## So what does Wax *look like?*

Below is a diagram to give you a zoomed-out view. In summary, you create a file of metadata records for your collection (in CSV, YAML, or JSON format), organize your collection image files, and put both in a Jekyll site folder. After updating your configuration, you run a few command line tasks to prepare the data and metadata for use by the Jekyll site. Then Jekyll uses special layouts and Wax components to build the exhibition and it spits them out as static pages.

From there, you can run tests on your site to catch errors and decide where and how to put it online with greater flexibility.

[![wax_screen]({{ '/assets/wax_workflow.jpeg' | absolute_url }} )]({{ '/assets/wax_workflow.jpeg' | absolute_url }})

## How can I get help?

You can submit questions, issues, and feature requests on [GitHub](https://github.com/minicomp/wax/issues/) or ask informally using your GitHub login on [Gitter chat](https://gitter.im/minicomp/wax/).
