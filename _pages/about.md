---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="lang-content" data-lang="en" markdown="1">

# {{ site.data.i18n.en.sections.about }} {#about-me}

{{ site.data.i18n.en.about.intro }}

{{ site.data.i18n.en.about.research }}

{{ site.data.i18n.en.about.email }}: <span class="email-placeholder"></span>

# {{ site.data.i18n.en.sections.news }} {#news}
{% for item in site.data.i18n.en.news %}
- *{{ item.date }}*: {{ item.content }}
{% endfor %}

# {{ site.data.i18n.en.sections.publications }} {#selected-publications}

- [Knowledge Distillation with Refined Logits](https://openaccess.thecvf.com/content/ICCV2025/html/Sun_Knowledge_Distillation_with_Refined_Logits_ICCV_2025_paper.html)<br>
  **Wujie Sun**, Defang Chen\*, Siwei Lyu, Genlang Chen, Chun Chen, Can Wang<br>
  *ICCV 2025, CCF-A*

- [Multi-Exit Self-Distillation with Appropriate Teachers](https://link.springer.com/article/10.1631/FITEE.2200644)<br>
  **Wujie Sun**, Defang Chen, Can Wang\*, Deshi Ye, Yan Feng, Chun Chen<br>
  *FITEE 2024, CCF-T1*

- [Accelerating Diffusion Sampling with Classifier-based Feature Distillation](https://ieeexplore.ieee.org/document/10219693)<br>
  **Wujie Sun**, Defang Chen, Can Wang, Deshi Ye\*, Yan Feng, Chun Chen<br>
  *ICME 2023, CCF-B*

- [Holistic Weighted Distillation for Semantic Segmentation](https://ieeexplore.ieee.org/document/10220035)<br>
  **Wujie Sun**, Defang Chen, Can Wang, Deshi Ye\*, Yan Feng, Chun Chen<br>
  *ICME 2023, CCF-B*

# {{ site.data.i18n.en.sections.apps }} {#personal-apps}

{{ site.data.i18n.en.apps.intro }}

- [JustWalk / 轻徒步](https://apps.apple.com/us/app/%E8%BD%BB%E5%BE%92%E6%AD%A5/id6756804999)<br>
  A simple, lightweight hiking app.<br>
  *iOS / watchOS*

- [JustRead / 轻文献](https://apps.apple.com/us/app/%E8%BD%BB%E6%96%87%E7%8C%AE/id6767557919) ([AI-enabled macOS DMG](https://github.com/zju-SWJ/JustRead_Public))<br>
  A macOS app for reading and organizing papers around a local literature library.<br>
  *macOS*

# {{ site.data.i18n.en.sections.education }} {#education--experience}
{% for item in site.data.i18n.en.education %}
- *{{ item.period }}*, {{ item.title }}
{% endfor %}

---
*{{ site.data.i18n.en.footer.updated }}: 2026-05-15*

</div>

<div class="lang-content" data-lang="zh" markdown="1">

# {{ site.data.i18n.zh.sections.about }} {#zh-about-me}

{{ site.data.i18n.zh.about.intro }}

{{ site.data.i18n.zh.about.research }}

{{ site.data.i18n.zh.about.email }}: <span class="email-placeholder"></span>

# {{ site.data.i18n.zh.sections.news }} {#zh-news}
{% for item in site.data.i18n.zh.news %}
- *{{ item.date }}*: {{ item.content }}
{% endfor %}

# {{ site.data.i18n.zh.sections.publications }} {#zh-selected-publications}

- [Knowledge Distillation with Refined Logits](https://openaccess.thecvf.com/content/ICCV2025/html/Sun_Knowledge_Distillation_with_Refined_Logits_ICCV_2025_paper.html)<br>
  **Wujie Sun**, Defang Chen\*, Siwei Lyu, Genlang Chen, Chun Chen, Can Wang<br>
  *ICCV 2025, CCF-A*

- [Multi-Exit Self-Distillation with Appropriate Teachers](https://link.springer.com/article/10.1631/FITEE.2200644)<br>
  **Wujie Sun**, Defang Chen, Can Wang\*, Deshi Ye, Yan Feng, Chun Chen<br>
  *FITEE 2024, CCF-T1*

- [Accelerating Diffusion Sampling with Classifier-based Feature Distillation](https://ieeexplore.ieee.org/document/10219693)<br>
  **Wujie Sun**, Defang Chen, Can Wang, Deshi Ye\*, Yan Feng, Chun Chen<br>
  *ICME 2023, CCF-B*

- [Holistic Weighted Distillation for Semantic Segmentation](https://ieeexplore.ieee.org/document/10220035)<br>
  **Wujie Sun**, Defang Chen, Can Wang, Deshi Ye\*, Yan Feng, Chun Chen<br>
  *ICME 2023, CCF-B*

# {{ site.data.i18n.zh.sections.apps }} {#zh-personal-apps}

{{ site.data.i18n.zh.apps.intro }}

- [轻徒步](https://apps.apple.com/us/app/%E8%BD%BB%E5%BE%92%E6%AD%A5/id6756804999)<br>
  一款简单、轻量的徒步应用。<br>
  *iOS / watchOS*

- [轻文献](https://apps.apple.com/us/app/%E8%BD%BB%E6%96%87%E7%8C%AE/id6767557919)（[带 AI 功能的 macOS DMG 版](https://github.com/zju-SWJ/JustRead_Public)）<br>
  一款围绕本地文献库做论文阅读和整理的 macOS 应用。<br>
  *macOS*

# {{ site.data.i18n.zh.sections.education }} {#zh-education--experience}
{% for item in site.data.i18n.zh.education %}
- *{{ item.period }}*, {{ item.title }}
{% endfor %}

---
*{{ site.data.i18n.zh.footer.updated }}: 2026-05-15*

</div>

<script>
// Email protection
var a = "sunwujie";
var b = "zju.edu.cn";
document.querySelectorAll('.email-placeholder').forEach(function(el) {
  el.innerHTML = '<a href="mailto:' + a + '@' + b + '">' + a + '@' + b + '</a>';
});
</script>
