---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
summary: ""
author: []
tags: []
categories: []
date: {{ .Date }}
lastmod: {{ .Date }}
featured: false
draft: false
disable_jquery: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 1
  caption: ""
  focal_point: "smart"
  preview_only: false 
  alt_text: An optional description of the image for screen readers.

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

## To enable LaTeX math rendering for a page, you should include `math: true` in the page’s front matter.
##   I have enabled math on the homepage or for all pages, by globally setting `math = true` in `config/_default/params`
math: false

## The following parameters can be added to the front matter of 
##   a page (such as a blog post) to control its features:
reading_time: true  # Show estimated reading time?
share: true  # Show social sharing links?
profile: true  # Show author profile?
commentable: false  # Allow visitors to comment? Supported by the Page, Post, and Docs content types.
---
