---
layout: home
title: "Welcome to My Blog!"
---

# 🚀 Welcome to My Web3 & Blockchain Blog!

Hi, I'm **Doel Sumbing**!  
I share insights about **Web3, Blockchain, Smart Contracts, and Decentralized Technologies**.

## 📝 Latest Posts
{% for post in site.posts %}
- 📅 **{{ post.date | date: "%B %d, %Y" }}** - [{{ post.title }}]({{ post.url }})
{% endfor %}

---

Thanks for visiting! 🚀✨
