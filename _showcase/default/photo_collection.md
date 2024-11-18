---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: https://picsum.photos/seed/first1111/800/800
  title: Reality
  desc: is merely an illusion, albeit a very persistent one.
  link: https://picsum.photos/
- src: https://picsum.photos/seed/second22/800/800
  desc: What I cannot create, I do not understand.
- src: https://picsum.photos/seed/third33/800/800
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
