---
layout: post
title: "Mexican Papaya: A Guide to Growing in Phoenix"
date: 2024-09-24
categories: [plants, Phoenix]
---
## Mexican Papaya in Phoenix Gardens

The Mexican papaya is a resilient plant that thrives in the warm, sunny conditions of Phoenix. In this post, we’ll cover everything from planting tips to harvesting your papayas...

### Planting Tips
- Choose a sunny location.
- Water deeply, but not too often...

### Conclusion
Mexican papayas are a great choice for your Phoenix garden if you’re looking for a hardy, delicious fruit.
---
layout: default
title: Blog
---

# Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
