---
permalink: /figure-skating/
title: ""
excerpt: ""
author_profile: true
---
# Figure Skating ⛸️

I have been skating for about **two years**, and I am currently working on my **single Loop** jump. 
My figure skating journey began at the **[National Ice Centre](https://national-ice-centre.com/)** in Nottingham. 
Now I mainly practice at **[City Ice Pavilion](https://www.cityicepavilion.com/)** in Long Island City, and sometimes at **[Chelsea Piers Sky Rink](https://www.chelseapiers.com/skyrink-chelsea)** in Manhattan.

## Post

{% raw %}{% assign posts = site.figureskating | sort: "date" | reverse %}

{% for post in posts %}
### {{ post.title }}

*{{ post.date | date: "%b %-d, %Y" }}*

{{ post.content }}
