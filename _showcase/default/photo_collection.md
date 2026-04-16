---
show: true
width: 6
date: 2024-01-11 00:01:00 +0800
height: 380px
images:
- src: https://images.unsplash.com/photo-1472214103451-9374bd1c798e?w=800&q=80
  title: Golden Meadow
  desc: Late afternoon light across rolling hills
- src: https://images.unsplash.com/photo-1574158622682-e40e69881006?w=800&q=80
  title: Curious Cat
  desc: Those eyes see everything
- src: https://images.unsplash.com/photo-1587300003388-59208cc962cb?w=800&q=80
  title: Happy Dog
  desc: Pure joy on four legs
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
