---
layout: default
---

## 8/2 unmercerized cotton

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "unmercerized" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 3/2 perle cotton

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "perle3/2" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 5/2 perle cotton

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "perle5/2" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 10/2 perle cotton

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "perle10/2" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## Cotton warp
![]({{ sitebase.url }}/stash/img/{{ cotton-rug.jpg }})

|Color | Cones | Yards |  
|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "cotton-rug" %}
| {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 20/2 cottolin

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "cottolin" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 8/2 bamboo

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "bamboo8/2" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 16/2 bamboo

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "bamboo16/2" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}


## 8/2 tencel

|---|Color | Cones | Yards |  
|---|---|---|---|{% for yarn in site.data.yarn %}{% if yarn.tag contains "tencel8/2" %}
| ![]({{ sitebase.url }}/stash/img/{{ yarn.img }}) | {{ yarn.color }} | {{yarn.amount}} | {{ yarn.yards }} |{% endif %}{% endfor %}
