---
layout: default
---

## 8/2 unmercerized cotton

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "unmercerized" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 3/2 perle cotton

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "perle3/2" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 5/2 perle cotton

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "perle5/2" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 10/2 perle cotton

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "perle10/2" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## Cotton warp

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "cotton-warp" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 20/2 cottolin

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "cottolin" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 8/2 bamboo

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "bamboo" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 8/2 tencel

| Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "tencel" %}
| {{ yarn.color }} | {{yarn.cones}} | {{ yarn.yards }} |{% endif %}{% endfor %}
