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

I am a incoming Ph.D. student in Computer Science at **University of Illinois Urbana-Champaign (UIUC)**. 

Before this, I received my Bachelor’s degree (2017-2021, computer science), Master's degree (2021-2024, computer science) from **Shandong University** and **Xiamen University**, respectively. I also worked as researcher at **DAMO Academy, Alibaba Group** from August, 2024 to June, 2025.


🤔 Currently, my research interests are primarily focused on Large Language Models (LLMs), covering the following topics:
- **Knowledge-Augmented LLMs** allow LLMs to make full use of external knowledge to solve real-world problems.
- **LLM-Agent** that creates interfaces to help LLMs and humans communicate, interact, and exchange knowledge. I believe all these questions are fundamental for bridging the gap between LLMs and human intelligence, and their solutions will play significant roles in implementing a knowledge-centric AI.
- **Reinforcement Learning** that can train the model without human knowledge and even beyond human performance.
- **Large-Vision Language Models (LVLMs)** that enables LVLMs to better understand images, comprehend user intent, and mitigate hallucination issues.

🤝 **Looking for collaboration! If you are interested in working with me with any topics, please drop me an email.**

# 🔥 News
- *2024.11*: &nbsp;🎉🎉 One paper ([MVP](https://arxiv.org/pdf/2408.17150)) is accepted by COLING 2025!
- *2024.09*: &nbsp;🎉🎉 One paper ([ConflictBank](https://arxiv.org/pdf/2408.12076)) is accepted by NeurIPS 2024 Track Datasets and Benchmarks! 
- *2024.09*: &nbsp;🎉🎉 One paper ([SURf](https://arxiv.org/abs/2409.14083#:~:text=Large%20Vision-Language%20Models%20(LVLMs)%20have%20become%20pivotal%20at)) is accepted by EMNLP 2024! 
- *2024.08*: &nbsp;🎉🎉 Starting a new position as Research Engineer at DAMO Academy, Alibaba Group!
- *2024.03*: &nbsp;🎉🎉 One paper (TableLLM) is accepted by IJCNN 2024!
- *2024.03*: &nbsp;🎉🎉 Two papers ([Iter-CoT](https://arxiv.org/abs/2304.11657), [Guide-Align](https://arxiv.org/pdf/2403.11838.pdf)) are accepted by NAACL 2024!
- *2024.02*: &nbsp;🎉🎉 One paper ([APOLLO](https://arxiv.org/abs/2212.07249)) is accepted by COLING 2024! 
- *2024.02*: &nbsp;🎉🎉 One paper ([Think-on-Graph](https://arxiv.org/abs/2307.07697)) is accepted by ICLR 2024! 

# 📝 Publications <a href='https://scholar.google.com/citations?user=JCUiEM4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

1. ``ICLR 2024`` [Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph](https://arxiv.org/pdf/2307.07697.pdf), **Jiashuo Sun**&ast;, Chengjin Xu&ast;, Lumingyuan Tang&ast;, Saizhuo Wang&ast;, Chen Lin, Yeyun Gong, Lionel M. Ni, Heung-Yeung Shum, Jian Guo.

2. ``COLING 2024`` [APOLLO: An Optimized Training Approach for Long-form Numerical Reasoning](https://arxiv.org/abs/2212.07249), **Jiashuo Sun**, Hang Zhang, Chen Lin, Yeyun Gong, Jian Guo, Nan Duan.

3. ``NAACL 2024 Findings`` [Enhancing Chain-of-Thoughts Prompting with Iterative Bootstrapping in Large Language Models](https://arxiv.org/pdf/2304.11657.pdf), **Jiashuo Sun**&ast;, Yi Luo&ast;, Yeyun Gong, Chen Lin, Yelong Shen, Jian Guo, Nan Duan.

4. ``EMNLP 2024`` [SURf: Teaching Large Vision-Language Models to Selectively Utilize Retrieved Information](https://arxiv.org/abs/2409.14083#:~:text=Large%20Vision-Language%20Models%20(LVLMs)%20have%20become%20pivotal%20at), **Jiashuo Sun**, Jihai Zhang, Chengyu Zhou, Zhaochen Su, Xiaoye Qu, Yu Cheng

5. ``COLING 2025`` [Look, Compare, Decide: Alleviating Hallucination in Large Vision-Language Models via Multi-View Multi-Path Reasoning](https://arxiv.org/pdf/2408.17150), Xiaoye Qu, **Jiashuo Sun**, Wei Wei, Daizong Liu, Jianfeng Dong, Yong Deng, Weitao Zheng, Yu Cheng

6. ``NAACL 2024`` [Ensuring Safe and High-Quality Outputs: A Guideline Library Approach for Language Models](https://arxiv.org/abs/2403.11838), Yi Luo, Zhenghao Lin, Yuhao Zhang, **Jiashuo Sun**, Chen Lin, Chengjin Xu, Xiangdong Su, Yelong Shen, Jian Guo, Yeyun Gong.

7. ``NeurIPS 2024 Track Datasets and Benchmarks`` [ConflictBank: A Benchmark for Evaluating Knowledge Conflicts in Large Language Models](https://arxiv.org/pdf/2408.12076), Zhaochen Su, Jun Zhang, Xiaoye Qu, Tong Zhu, Yanshu Li, **Jiashuo Sun**, Juntao Li, Min Zhang, Yu Cheng.

8. ``TOMM 2025`` [Alleviating Hallucination in Large Vision-Language Models with Active Retrieval Augmentation](https://arxiv.org/pdf/2408.00555), Xiaoye Qu, Qiyuan Chen, Wei wei, **Jiashuo Sun**, Jianfeng Dong.

9. ``Submission to ICCV 2025`` [2.5 Years in Class: A Multimodal Textbook for Vision-Language Pretraining](https://www.arxiv.org/pdf/2501.00958), Wenqi Zhang, Hang Zhang, Xin Li, **Jiashuo Sun**, Yongliang Shen, Weiming Lu, Deli Zhao, Yueting Zhuang, Lidong Bing

10. ``Submission to ACMM 2025`` [From Captions to Rewards (CaReVL): Leveraging Large Language Model Experts for Enhanced Reward Modeling in Large Vision-Language Models](https://arxiv.org/abs/2503.06260), Muzhi Dai, **Jiashuo Sun**, Zhiyuan Zhao, Shixuan Liu, Rui Li, Junyu Gao, Xuelong Li

11. ``Submission to NeurIPS 2025`` [DynamicRAG: Leveraging Outputs of Large Language Model as Feedback for Dynamic Reranking in Retrieval-Augmented Generation](https://www.arxiv.org/abs/2505.07233), **Jiashuo Sun**, Xianrui Zhong, Sizhe Zhou, Jiawei Han

12. ``Submission to NeurIPS 2025 Track Datasets and Benchmarks`` [Benchmarking Multimodal Mathematical Reasoning with Explicit Visual Dependency](https://arxiv.org/abs/2504.18589), Zhikai Wang&ast;, **Jiashuo Sun**&ast;, Wenqi Zhang, Zhiqiang Hu, Xin Li, Fan Wang, Deli Zhao

# 👨‍💻 Open-Source Projects
- [NanoRAG: Simple implementation of Retrieval-Augmented Generation System](https://github.com/GasolSun36/NanoRAG)

- [PiXiu: Instruct-tuning Large Language Models with Chinese Financial Knowledge Graph](https://github.com/GasolSun36/pixiu/blob/main/README.md)


# 🎖 Honors and Awards
-  2022.11 [FinQA Competition Leaderboard](https://codalab.lisn.upsaclay.fr/competitions/4138) **Rank 1**
- 2022.11 [ConvFinQA Competition Leaderboard](https://codalab.lisn.upsaclay.fr/competitions/8582) **Rank 1**

# 📖 Educations
- *2021.09 - 2024.06*, M.S. in Computer Science, Xiamen University 
- *2017.09 - 2021.06*, B.S. in Computer Science, Shandong University.

# 💁 Volunteer
- Area Chair: ARR, ACL, EMNLP
- Conference Reviewer: ARR, ICLR, NeurIPS, ACL, EMNLP, ICCV, NAACL, ACMM, TKDE
- *2022.09 - 2023.03*, Object Oriented Programming (2022 Fall) **Teaching Assistant**



# 💻 Internships and Work Experiences
- *2024.08 - Present*, DAMO Academy, Alibaba Group, Research Engineer
- *2024.01 - 2024.07*, Shanghai AI Laboratory General Technology Research, Research Intern
- *2023.04 - 2023.12*, International Digital Economy Academy Fin-AI Group, Research Intern
- *2022.09 - 2023.04*, Microsoft Research Asia NLC Group, Research Assitant


# 🎨 Miscellaneous

- I am an **amateur singer** 🎤 and have won the **Top Ten Singer Award** at Xiamen University twice (you can check out my competition videos at [this](https://www.bilibili.com/video/BV1Hs421T7JD/?spm_id_from=333.999.0.0)). I also enjoy playing instruments, such as the piano 🎹 and guitar 🎸. When I'm not coding, I love listening to music and making music (R&B is my favourite).
- If you have similar interests or would like to connect with me, feel free to email me anytime!

