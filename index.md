---
title: Software for Communities
layout: layout_home
---

# Coronavirus

## English

### Essentials

### Real-Time Updates for your City

### Small Business Owners

### Recent Posts

<ul>
  {% for post in site.posts_EN %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &rarr; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Khmer

### Essentials

### Real-Time Updates for your City

### Small Business Owners

### Recent Posts

<ul>
  {% for post in site.posts_KM %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &rarr; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
