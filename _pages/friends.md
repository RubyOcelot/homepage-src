---
permalink: /friends/
title: "Friends"

friends:
  - name: Zihan Zheng
    github: zzh1996
    link: https://zhengzihan.com/
  - name: iBug
    github: iBug
    link: https://ibug.io/
  - name: myl7
    github: myl7
    link: https://myl.moe/
  - name: totoroyyw
    github: totoroyyw
    link: https://yyw.moe/
  - name: Elsa Granger
    github: zeyugao
    link: https://elsagranger.com/
  - name: Hypercube
    github: SmartHypercube
    link: https://0x01.me/
  - name: Sirius1242
    github: Sirius1242
    link: https://sirius1242.github.io/
  - name: xyy
    github: ustcqzy
    link: https://ustcqzy.github.io/

---

*Ordered randomly*

{% for item in page.friends %}
- {{ item.name }}{% if item.github %} [<i class="fab fa-github"></i>](https://github.com/{{ item.github }}){% endif %}\: [<i class="fas fa-globe-americas"></i> {{ item.link }}]({{ item.link }})
{% endfor %}


<style type="text/css">
ul { list-style-type: none; }
</style>
