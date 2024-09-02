---
layout: default
title: Home
---

# Welcome to TheBitGuardian

## Exploring the Realms of Network Administration and Cybersecurity

Welcome to my GitHub Pages site! I am an aspiring network administrator and cybersecurity professional, and this site serves as a hub for my current projects, learning experiences, and technical insights. My current role is titled "Support Specialist II" however my duties resemble that of a jr network/system admin.

---

## Current Projects

### **Test Lab**
I am currently working on developing a home lab. This lab will be used to better hone my understanding of network infrastructure. I'm also using tools like packet tracer to further identify how data transverses a network. 

---

## Learning Journal

As I progress on my journey to becoming a network administrator and cybersecurity expert, I’m documenting my learning experiences. Here’s a glimpse into what I’ve been up to:

- **Firewall Configurations**: Understanding the setup and management of firewalls to protect network infrastructure.
- **Intrusion Detection Systems (IDS)**: Exploring the implementation and use of IDS to monitor network traffic for suspicious activities. I currently work with DarkTrace. 
- **Penetration Testing**: Learning the techniques to test network and web applications for vulnerabilities.
- **CCNA**: I am currently working toward obtaining my CCNA certification. 
---

## Connect with Me

I'm always open to connecting with others in the tech community. Feel free to check out my work on [GitHub](https://github.com/TheBitGuardian)
---

### Latest Blog Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}

---

Thank you for visiting my site! Stay tuned for more updates as I continue to learn and grow in the field of network administration and cybersecurity.
