---
layout: collection
title: Find a solution to your employment dispute
description: Notification service for engaging Acas
related:
  items:
    - text: Prototype
      description: |
        Username: `acas`
        Password: `acas777`
      href: https://acas-4.herokuapp.com/
pagination:
  data: collections.find-a-solution-to-your-employment-dispute
  reverse: true
  size: 50
permalink: "find-a-solution-to-your-employment-dispute/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
