---
permalink: /friends/
title: "Friends"

friends:
  - name: Zihan Zheng
    link: https://zhengzihan.com/
  - name: iBug
    link: https://ibug.io/
  - name: myl7
    link: https://myl.moe/
  - name: totoroyyw
    link: https://yyw.moe/
  - name: Elsa Granger
    link: https://elsagranger.com/

---

*Ordered randomly*

{% for item in page.friends %}
- {{ item.name }}\: [<i class="fas fa-globe-americas"></i> {{ item.link }}]({{ item.link }})
{% endfor %}


<style type="text/css">
ul { list-style-type: none; }
</style>