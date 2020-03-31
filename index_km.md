---
title: កម្មវិធីសម្រាប់សហគមន៍
layout: layout_home
---

# កូរ៉ូណាវ៉ាវី

## ព័ត៌មានចាំបាច់

Information related to the status of the SARS-CoV-2 (COVID-19).

* **Update 2020-03-30**: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
* [Updates from CDC](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/summary.html)
* [Here's a link to some more content!](#)

## Real-Time Updates

Updates on the status of various cities.

* **(2020-03-30) New York City: Avengers headquarters goes into lockdown**: [A quick, 1 sentence summary](#)
* **(2020-03-28) Washington DC: City replaces all the batteries in local birds**: [A quick, 1 sentence summary](#)
	* (2020-03-29) Retraction: birds are real
* Something else

<details><summary>Find updates for your city.</summary>

### Cities
* [Chicago](#)
* [Los Angeles (LA)](#)
* [New York City (NYC)](#)
* [Washington D.C. (DC)](#)

</details>

<p></p>

## Small Business Owners

Information to help small business owners get relief. 

## Recent Posts

Posts recently submitted to the site (in English).

<ul>
  {% for post in site.posts_EN %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &rarr; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<br></br>

