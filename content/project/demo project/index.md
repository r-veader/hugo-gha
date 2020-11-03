---
title: Demo Second Project
summary: A placeholder! 
tags:
- Demo
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# Implementation

-   Pick your template. We used the Academic Resume template [https://github.com/wowchemy/starter-academic](https://github.com/wowchemy/starter-academic)
    

  

-   Fork it into your own Git Hub account.
    
-   In your new repository, efit the file hugo-gha/config/_default/config.toml to set your new baseurl to be your Github Pages url. Ours was:
    

  

baseurl = https://r-veader.github.io/hugo-gha

-   Follow the directions in the Github Actions for Hugo repo's README at [https://github.com/peaceiris/actions-hugo](https://github.com/peaceiris/actions-hugo)
    
-   Make sure to use Hugo Extended
    
-   This will be primarily copying and pasting the provided lines into a YAML file in the .github folder
-   Make your changes to the markdown files in your repo that defines your webpages and widgets.
    
-   [https://wowchemy.com/docs/get-started/](https://wowchemy.com/docs/get-started/) defines where in the repo to make changes.
    
-   After each commit, the Github Action that was setup will instantiate a Docker image with Hugo on Github Actions, build your site, and then copy it to the gh_pages branch that GitHub Pages uses to deliver your site!

