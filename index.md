---
title: "Hi"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/FHT_Pano.jpeg
excerpt: "Welcome to my website! A place where you can read things that I have written about myself."
intro: 
  - excerpt: |
      If you ain't got the sauce, then you lost. But you can also get lost in the sauce  
      - Gucci Mane

# feature_row:
#   - image_path: a ssets/images/unsplash-gallery-image-1-th.jpg
#     alt: "placeholder image 1"
#     title: "Placeholder 1"
#     excerpt: "This is some sample content that goes here with **Markdown** formatting."
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
#     alt: "placeholder image 2"
#     title: "Placeholder 2"
#     excerpt: "This is some sample content that goes here with **Markdown** formatting."
#     url: "/about"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
#   - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
#     title: "Placeholder 3"
#     excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/RobotFram.png
    alt: "projects preview"
    title: "Portfolio"
    excerpt: "The fact that you then try to make excuses for breaking user space, and blaming some external program that used to work, is just shameful. It's not how we work. Fix your f*cking \"compliance tool\", because it is obviously broken. And fix your approach to kernel programming."
    url: "/portfolio"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}

<!-- {% include feature_row %} -->

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}