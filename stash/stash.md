---
layout: default
---

## 8/2 unmercerized cotton

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "unmercerized" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}
