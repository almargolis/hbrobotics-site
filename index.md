---
layout: home
title: Home
---

# Welcome to East Bay Robotics Society

The East Bay Robotics Society (HBROBOTICS) is a community of robot enthusiasts who meet regularly in the San Francisco East Bay area to share knowledge, work on projects, and explore the exciting world of robotics.

## Upcoming Meetings

### General Meeting
- **When:** {{ site.meetings.general.schedule }}
- **Time:** {{ site.meetings.general.time }}
- **Where:** {{ site.meetings.general.location }}
- [Join via Zoom]({{ site.meetings.general.zoom_link }})

Join us for presentations, demonstrations, and discussions about robotics projects and technologies.

### Special Interest Group (SIG) Meeting
- **When:** {{ site.meetings.sig.schedule }}
- **Time:** {{ site.meetings.sig.time }}
- **Where:** {{ site.meetings.sig.location }}
- [Join via Zoom]({{ site.meetings.sig.zoom_link }})

Deep-dive sessions focused on specific robotics topics and technologies.

### Business Meeting
- **When:** {{ site.meetings.business.schedule }}
- **Time:** {{ site.meetings.business.time }}
- **Where:** {{ site.meetings.business.location }}
- [Join via Zoom]({{ site.meetings.business.zoom_link }})

Monthly organizational meeting for club members.

## Recent News

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

[Read more...]({{ post.url }})
{% endfor %}

---

*All meetings are open to the public. Beginners welcome!*
