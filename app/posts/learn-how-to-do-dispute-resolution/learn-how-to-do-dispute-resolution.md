---
layout: collection
title: Learn how to do dispute resolution
description: A service to educate Claimants on the early conciliation process
related:
  items:
    - text: Prototype
      description: |
        Username: `..`
        Password: `..`
      href: https://herokuapp.com/
pagination:
  data: collections.learn-how-to-do-dispute-resolution
  reverse: true
  size: 50
permalink: "learn-how-to-do-dispute-resolution/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
