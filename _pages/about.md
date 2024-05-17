---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

✨ Hi everyone! I am currently a final-year PhD candidate in [PolyU NLP Group](https://polyunlp.github.io/) at the Hong Kong Polytechnic University, fortunately supervised by Prof. [Maggie Wenjie Li](https://www4.comp.polyu.edu.hk/~cswjli/). 
Before that, I received my B.S. degree (in 2017) and M.S. degree (in 2020) from Fudan University under the supervision of Assoc. Prof. [Zhipeng Xie](https://scholar.google.com/citations?user=-zlBDNIAAAAJ&hl=en).

My research focuses on Large Language Model, Math Reasoning, and Retrieval-Augmented Generation. 

🚀 Currently, I work closely with Assoc. Prof. [Pengfei Liu](http://pfliu.com/) at [GAIR Lab](https://plms.ai/) on Large Language Models (LLMs).

🔔 I am on the 2024-2025 job market. (Last Update on May 2024)

<a href='https://scholar.google.com/citations?user=M7g3H9YAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
<a href='./uploads/Shichao_Sun_Resume.pdf'><img src="https://img.shields.io/badge/-Shichao's Resumé-299DE7?logo=gitbook&logoColor=white"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=http%3A%2F%2Fshichaosun.github.io&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=page+hits&edge_flat=false"/></a>

<div id="educations" markdown="1"> 
# 📖 Educations
</div>
- *2020.09 - 2024.08 (Expected)*, Ph.D., The Hong Kong Polytechnic University.
- *2017.09 - 2020.01*, M.S., Fudan University.
- *2013.09 - 2017.03*, B.S., Fudan University.

<div id="publications" markdown="1"> 
# 📝 Selected Publications
</div>

(* indicates equal contribution)

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">The Critique of Critique
</b>
\\
**Shichao Sun**, Junlong Li, Weizhe Yuan, Ruifeng Yuan, Wenjie Li, Pengfei Liu\\
**ACL Findings, 2024** |  [PDF](https://arxiv.org/abs/2401.04518) | [Code](https://github.com/GAIR-NLP/MetaCritique)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Prompt Chaining or Stepwise Prompt? Refinement in Text Summarization
</b>
\\
**Shichao Sun**, Ruifeng Yuan, Ziqiang Cao, Wenjie Li, Pengfei Liu\\
**ACL Findings, 2024** 
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Dissecting Human and LLM Preferences
</b>
\\
Junlong Li, Fan Zhou, **Shichao Sun**, Yikai Zhang, Hai Zhao, Pengfei Liu\\
**ACL, 2024** |  [PDF](https://arxiv.org/abs/2402.11296) | [Code](https://github.com/GAIR-NLP/Preference-Dissection)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Generative Judge for Evaluating Alignment
</b>
\\
Junlong Li, **Shichao Sun**, Weizhe Yuan, Run-Ze Fan, Hai Zhao, Pengfei Liu \\
**ICLR, 2024** |  [PDF](https://arxiv.org/abs/2310.05470) | [Code](https://github.com/GAIR-NLP/auto-j) | [Page](https://gair-nlp.github.io/auto-j/)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Dialogue acts enhanced extract–abstract framework for meeting summarization
</b>
\\
**Shichao Sun**, Ruifeng Yuan, Wenjie Li, Ziqiang Cao, Sujian Li\\
**IPM, 2024** |  [PDF](https://www.sciencedirect.com/science/article/abs/pii/S0306457323003722)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Contrastive Preference Learning for Neural Machine Translation
</b>
\\
Jianfei He, **Shichao Sun**, Sen Peng, Jie Xu, Xiaohua Jia, Wenjie Li\\
**NAACL Findings, 2024** 
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Aligning Language Models with Human Preferences via a Bayesian Approach
</b>
\\
Jiashuo Wang, Haozhao Wang, **Shichao Sun**, Wenjie Li\\
**NeurIPS, 2023** |  [PDF](https://arxiv.org/abs/2310.05782) | [Code](https://github.com/wangjs9/aligned-dpm)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Data Selection Curriculum for Abstractive Text Summarization
</b>
\\
**Shichao Sun**, Ruifeng Yuan, Jianfei He, Ziqiang Cao, Wenjie Li, Xiaohua Jia\\
**EMNLP Findings, 2023** |  [PDF](https://aclanthology.org/2023.findings-emnlp.537/)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Separating Context and Pattern: Learning Disentangled Sentence Representations for Low-Resource Extractive Summarization
</b>
\\
Ruifeng Yuan, **Shichao Sun**, Zili Wang, Ziqiang Cao, Wenjie Li\\
**ACL Findings, 2023** |  [PDF](https://aclanthology.org/2023.findings-acl.479/) | [Code](https://github.com/RuifengYuan/Distangled-Ext-Sum)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Improving Sentence Similarity Estimation for Unsupervised Extractive Summarization
</b>
\\
**Shichao Sun**, Ruifeng Yuan, Wenjie Li, Sujian Li \\
**ICASSP, 2023** |  [PDF](https://ieeexplore.ieee.org/abstract/document/10096137/) | [Code](https://github.com/ShichaoSun/SS4Sum)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Rethinking the framework constructed by counterfactual functional model
</b>
\\
Chao Wang, Linfang Liu, **Shichao Sun**, Wei Wang \\
**Applied Intelligence, 2022** |  [PDF](https://link.springer.com/article/10.1007/s10489-022-03161-8)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Alleviating Exposure Bias via Contrastive Learning for Abstractive Text Summarization
</b>
\\
**Shichao Sun**, Wenjie Li \\
**arXiv, 2021** |  [PDF](https://arxiv.org/abs/2108.11846) | [Code](https://github.com/ShichaoSun/ConAbsSum)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">A Goal-Driven Tree-Structured Neural Model for Math Word Problems
</b>
\\
Zhipeng Xie\*, **Shichao Sun**\*\\
**IJCAI, 2019** |  [PDF](https://www.ijcai.org/proceedings/2019/0736.pdf) | [Code](https://github.com/ShichaoSun/math_seq2tree)
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">BiLSTM-Based Models for Metaphor Detection
</b>
\\
**Shichao Sun**, Zhipeng Xie \\
**NLPCC, 2017** |  [PDF](https://link.springer.com/chapter/10.1007/978-3-319-73618-1_36) | [Code](https://github.com/ShichaoSun/metaphor)
</div>

<div id="honors" markdown="1"> 
# 🎖 Honors and Awards
</div>
- Excellent Graduates in Shanghai, 2020
- National Scholarship, 2019
- Excellent Student in Fudan University, 2018
- Scholarship for Outstanding Students in Fudan University, 2018
- National Encouragement Scholarship, 2014, 2015, 2016

