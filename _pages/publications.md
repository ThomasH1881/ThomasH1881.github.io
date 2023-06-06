---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Kai Zhong, Shulin Zeng, **Wentao Hou**, Guohao Dai, Zhenhua Zhu, Xuecang Zhang, Shihai Xiao, Huazhong Yang, Yu Wang, "CoGNN: An Algorithm-Hardware Co-Design Approach to Accelerate GNN Inference with Mini-Batch Sampling", to appear in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), IEEE, 2023

**Wentao Hou**\*, Kai Zhong\*, Shulin Zeng, Guohao Dai, Huazhong Yang, Yu Wang, "NTGAT: A Graph Attention Network Accelerator with Runtime Node Tailoring", 28th Asia and South Pacific Design Automation Conference (ASP-DAC 2023)
