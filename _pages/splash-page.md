---
layout: splash
permalink: /splash-page/
title: "Your Page Title"
header:
  overlay_image: /assets/images/ME.jpeg
  overlay_filter: 0.5 # Adjust the overlay transparency (optional)
  caption: "Your caption here" # Optional
feature_row:
  - image_path: /assets/images/ME.jpeg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/ME.jpeg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/ME.jpeg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
