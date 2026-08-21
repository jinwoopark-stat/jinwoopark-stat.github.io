---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student in Statistics, <a href="https://stat.uchicago.edu/">University of Chicago</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Department of Statistics</p>
    <p>University of Chicago</p>
    <p>Chicago, IL 60637</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am an incoming Ph.D. student in the [Department of Statistics](https://stat.uchicago.edu/) at the University of Chicago, starting in Fall 2026. I received my B.S. in Statistics from [Seoul National University](https://stat.snu.ac.kr/), where I worked with Professor [Byeong U. Park](https://stat.snu.ac.kr/bupark/) in the Nonparametric Inference Lab.

My work so far has been on **nonparametric inference for locally stationary time series**. In my [first paper](https://arxiv.org/abs/2511.12948), I established uniform convergence rates for multivariate locally linear estimators under strong mixing, and used the resulting error expansion to build bias-corrected transfer learning estimators that let a sparsely observed series borrow strength from densely observed related sources.

More broadly, I am interested in nonparametric and high-dimensional inference, time series, and transfer learning. I am now looking for a new direction for my doctoral work, and I am especially drawn to questions where statistical theory meets deep learning and large language models.

Outside of research I play tennis, watch far too much football, and build AI agents for the fun of it.

<!--
  Person entity for search engines. The theme's head only emits a WebSite node with a
  bare author name (al_folio_core/_includes/metadata.liquid); this adds the affiliation,
  alumni, and profile links that let Google tie the page to the right "Jinwoo Park".
  JSON-LD is valid anywhere in the document, so it lives here instead of a head override.
  Keep the facts in sync with _data/cv.yml and _data/socials.yml.
-->
<script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Jinwoo Park",
    "givenName": "Jinwoo",
    "familyName": "Park",
    "url": "{{ site.url }}{{ site.baseurl }}/",
    "image": "{{ site.url }}{{ site.baseurl }}/assets/img/prof_pic.jpg",
    "jobTitle": "Ph.D. Student in Statistics",
    "affiliation": {
      "@type": "CollegeOrUniversity",
      "name": "University of Chicago",
      "department": {
        "@type": "Organization",
        "name": "Department of Statistics"
      },
      "url": "https://stat.uchicago.edu/"
    },
    "alumniOf": {
      "@type": "CollegeOrUniversity",
      "name": "Seoul National University",
      "url": "https://stat.snu.ac.kr/"
    },
    "knowsAbout": [
      "Nonparametric inference",
      "Locally stationary time series",
      "Transfer learning",
      "High-dimensional inference",
      "Statistical machine learning"
    ],
    "sameAs": [
      "https://github.com/jinwoopark-stat"
    ]
  }
</script>
