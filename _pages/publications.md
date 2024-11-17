---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=81FfsvwAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

Selected Publications
======
- **(<font color="#DC143C">NeurIPS 2024</font>) Aligning target-aware molecule diffusion models with exact energy optimization**
  <br/>
  _Siyi Gu\*, Minkai Xu\*, Alexander Powers, Weili Nie, Tomas Geffner, Karsten Kreis, Jure Leskovec, Arash Vahdat, Stefano Ermon_
  <br/>
  [[Paper](https://arxiv.org/pdf/2407.01648)]
- **(SIGKDD 2025) DUE: Dynamic uncertainty-aware explanation supervision via 3d imputation**
  <br/>
  _Qilong Zhao, Yifei Zhang, Mengdan Zhu, Siyi Gu, Yuyang Gao, Xiaofeng Yang, Liang Zhao_
  <br/>
  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3637528.3671641)]
- **(IJCAI 2024) Visual Attention-Prompted Prediction and Learning**
  <br/>
  _Yifei Zhang, Siyi Gu, Bo Pan, Guangji Bai, Xiaofeng Yang, Liang Zhao_
  <br/>
  [[Paper](https://arxiv.org/pdf/2310.08420)]
- **(<font color="#DC143C">SIGKDD 2024</font>) ESSA: Explanation iterative supervision via saliency-guided data augmentation**
  <br/>
  _Siyi Gu\*, Yifei Zhang\*, Yuyang Gao, Xiaofeng Yang, Liang Zhao_
  <br/>
  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3580305.3599336)]
- **(Arxiv) XAI Benchmark for visual explanation**
  <br/>
  _Yifei Zhang, Siyi Gu, James Song, Bo Pan, Guangji Bai, Liang Zhao_
  <br/>
  [[Paper](https://arxiv.org/pdf/2310.08537)]
- **(ACM Computing Surveys) Going beyond xai: A systematic survey for explanation-guided learning**
  <br/>
  _Yuyang Gao, Siyi Gu, Junji Jiang, Sungsoo Ray Hong, Dazhou Yu, Liang Zhao_
  <br/>
  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3644073)]
- **(SIGKDD 2023) RES: A robust framework for guiding visual explanation**
  <br/>
  _Yuyang Gao, Tong Steven Sun, Guangji Bai, Siyi Gu, Sungsoo Ray Hong, Zhao Liang_
  <br/>
  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539419)]
- **(ICCV 2023) MAGI: Multi-annotated explanation-guided learning**
  <br/>
  _Yifei Zhang, Siyi Gu, Yuyang Gao, Bo Pan, Xiaofeng Yang, Liang Zhao_
  <br/>
  [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_MAGI_Multi-Annotated_Explanation-Guided_Learning_ICCV_2023_paper.pdf)]
- **(CIN 2024) Evaluating Natural Language Processing Packages for Predicting Hospital-Acquired Pressure Injuries From Clinical Notes**
  <br/>
  _Siyi Gu, Eric W Lee, Wenhui Zhang, Roy L Simpson, Vicki Stover Hertzberg, Joyce C Ho_
  <br/>
  [[Paper](https://journals.lww.com/cinjournal/fulltext/2024/03000/evaluating_natural_language_processing_packages.5.aspx)]

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
