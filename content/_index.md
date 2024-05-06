---
title: "My Page"
sections:
- block: hero
  content:
      resumés, conferences, and tech blogs.\n\n<!--Custom spacing-->\n<div class=\"mb-3\"></div>\n
date: "2022-04-30"
  design:
    background:
      gradient_end: '#1976d2'
      gradient_start: '#004ba0'
      text_color_light: yes
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: skills
  content:
    text: '* Regression, Classification, Clustering, PCA, Random Forest, Neural Network,
      Bayesian statistics, Generalized Linear Models, A/B testing, Big datasets, Hypothesis
      Testing * R (e.g., ggplot2), SQL, Tableau'
    title: Skills
    username: admin
  design:
    columns: '1'
- block: collection
  content:
    count: 5
    filters:
      author: ''
      category: ''
      exclude_featured: no
      exclude_future: no
      exclude_past: no
      folders: post
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    subtitle: ''
    text: ''
    title: Recent Posts
  design:
    columns: '2'
    view: compact
  id: posts
  demo: yes
type: landing
---
