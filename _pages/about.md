---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="lang-content" data-lang="en">

# {{ site.data.i18n.en.sections.about }}

{{ site.data.i18n.en.about.intro }}

{{ site.data.i18n.en.about.research }}

{{ site.data.i18n.en.about.email }}: <span class="email-placeholder"></span>

# {{ site.data.i18n.en.sections.news }}
{% for item in site.data.i18n.en.news %}
- *{{ item.date }}*: {{ item.content }}
{% endfor %}

# {{ site.data.i18n.en.sections.publications }}

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

# {{ site.data.i18n.en.sections.education }}
{% for item in site.data.i18n.en.education %}
- *{{ item.period }}*, {{ item.title }}
{% endfor %}

---
*{{ site.data.i18n.en.footer.updated }}: 2026-01-22*

</div>

<div class="lang-content" data-lang="zh" style="display:none;">

# {{ site.data.i18n.zh.sections.about }}

{{ site.data.i18n.zh.about.intro }}

{{ site.data.i18n.zh.about.research }}

{{ site.data.i18n.zh.about.email }}: <span class="email-placeholder"></span>

# {{ site.data.i18n.zh.sections.news }}
{% for item in site.data.i18n.zh.news %}
- *{{ item.date }}*: {{ item.content }}
{% endfor %}

# {{ site.data.i18n.zh.sections.publications }}

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

# {{ site.data.i18n.zh.sections.education }}
{% for item in site.data.i18n.zh.education %}
- *{{ item.period }}*, {{ item.title }}
{% endfor %}

---
*{{ site.data.i18n.zh.footer.updated }}: 2026-01-22*

</div>

<script>
// Email protection
var a = "sunwujie";
var b = "zju.edu.cn";
document.querySelectorAll('.email-placeholder').forEach(function(el) {
  el.innerHTML = '<a href="mailto:' + a + '@' + b + '">' + a + '@' + b + '</a>';
});
</script>
