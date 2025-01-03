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


Xincheng Xie, **Wentao Hou**, Zerui Guo, and Ming Liu, "Building Massive MIMO Baseband Processing on a Single-Node Supercomputer", in USENIX Symposium on Networked Systems Design and Implementation (NSDI), 2025

**Wentao Hou**, Jie Zhang, Zeke Wang, and Ming Liu, "Understanding Routable PCIe Performance for Composable Infrastructures", in USENIX Symposium on Networked Systems Design and Implementation (NSDI), 2024

Kai Zhong, Shulin Zeng, **Wentao Hou**, Guohao Dai, Zhenhua Zhu, Xuecang Zhang, Shihai Xiao, Huazhong Yang, Yu Wang, "CoGNN: An Algorithm-Hardware Co-Design Approach to Accelerate GNN Inference with Mini-Batch Sampling", in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 4883-4896, 42,12, IEEE, 2023

**Wentao Hou**\*, Kai Zhong\*, Shulin Zeng, Guohao Dai, Huazhong Yang, Yu Wang, "NTGAT: A Graph Attention Network Accelerator with Runtime Node Tailoring", in Asia and South Pacific Design Automation Conference (ASP-DAC), 2023



