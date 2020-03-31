---
title: Software for Communities
layout: layout_home
---

# Coronavirus

## English

### Essentials

**Update 2020-03-30**: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

[Here's a link to some content!](#)

[Here's a link to some more content!](#)

### Real-Time Updates for your City

* **(2020-03-30) City goes into lockdown**: [A quick, 1 sentence summary](#)
* **(2020-03-28) City replaces all the batteries in local birds**: [A quick, 1 sentence summary](#)
	* (2020-03-29) Retraction: birds are real
* Something else

### Small Business Owners

Find out how the...

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
