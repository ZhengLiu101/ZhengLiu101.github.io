---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Zheng Liu is now a technique specialist on search and recommendation algorithms in Huawei 2012 Labs. He was affiliated with Microsoft Research Asia as a senior researcher in Social Computing and Natural Language Computation. He graduated from the Hong Kong University of Science and Technology with a PhD degree in computer science and engineering. His research covers a broad scope of problems in search and recommendation. Recently, he focuses on developing the **retrieval-oriented pre-training algorithms** and the **end-to-end optimized IR systems**. Aside from academic research, his has conducted a series of product-driven projects in Microsoft and Huawei, which contribute to Bing Sponsored Search, Microsoft News, Petal Search, etc. He is constantly serving as PC and reviewer for KDD, WWW, TKDE and TOIS, etc. He is an invited lecture for [CCF ADL on Embedding Learning and Search](https://www.ccf.org.cn/Focus/2022-09-30/775088.shtml), the convener and guest editor for [TOIS](https://dl.acm.org/journal/tois/calls-for-papers) special section on pre-trained models for IR (TBA).

### Research Highlights
* **[RetroMAE]** A family of pre-trained algorithms tailored for deep semantic retrieval: simple, low-cost, and remarkably competitive throughout different settings. (So far, one of the best retrieval-oriented pre-trained models on [MSMARCO](https://microsoft.github.io/msmarco/) and [BEIR](https://paperswithcode.com/sota/zero-shot-text-search-on-beir) benchmark)
  * Publications: [RetroMAE (EMNLP'22)](https://arxiv.org/abs/2205.12035), [RetroMAE v2](https://arxiv.org/abs/2211.08769) 
  * Codebase: [RetroMAE](https://github.com/staoxiao/RetroMAE)
  * Media coverage (in Chinese): [稠密检索新突破：华为提出掩码自编码预训练模型，大幅刷新多项基准](https://mp.weixin.qq.com/s/z9mwg1fFyY3K26Y2sTJjKQ)
* **[Uni-Retriever]**. A package solution of light-weight retrievers developed for Bing Sponsored Search, which is built upon the joint optimization of dense retriever and ANN index.
  * Publications: [Uni-Retriever (KDD'22)](https://dl.acm.org/doi/10.1145/3534678.3539212), [Distill-VQ (SIGIR'22)](https://dl.acm.org/doi/abs/10.1145/3477495.3531799), [BiDR (WWW'22)](https://arxiv.org/pdf/2201.05409.pdf), [MoPQ (EMNLP'21)](https://aclanthology.org/2021.emnlp-main.640/)
  * Codebase: [LibVQ](https://github.com/staoxiao/LibVQ)
  * The team championed [MS MARCO doc ranking leaderboard](https://microsoft.github.io/msmarco/) for two straight times in 2021/06/24 and 2021/07/14, leading to +1.3 points MRR@100 improvement in total!