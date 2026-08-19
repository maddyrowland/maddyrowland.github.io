---
layout: splash
title: "Welcome to My Site"
permalink: /
classes:
  - wide
  - dark-theme
header:
  overlay_image: /assets/splash/laika.jpg
  overlay_filter: 0.5
  actions:
    - label: "Enter Site"
      url: /blog/
    - label: "Learn More"
      url: /about/
---
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

{% include feature_row id="intro" type="center" %}

feature_row:
  - image_path: /assets/images/feature-1.jpg
    alt: "Feature One"
    title: "Our Services"
    excerpt: "Discover what we can do to help you scale your projects."
    url: "/services/"
    btn_class: "btn--primary"
    btn_label: "Explore"
  - image_path: /assets/images/feature-2.jpg
    alt: "Feature Two"
    title: "Portfolio"
    excerpt: "Check out our latest open-source contributions."
    url: "/portfolio/"
    btn_class: "btn--success"
    btn_label: "View Work"
