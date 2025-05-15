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

# 👀 About Me

I am a PhD student in the College of Computer Science and Technology of Nanjing University of Aeronautics and Astronautics.

My research focuses on **Intelligent Software Engineering**, with a spotlight on the following key areas: 

- Reliability 
- Robustness 
- Security 
- Economy 
- Evaluation Metrics 
- Others

My advisor is Professor [Yu Zhou](https://csyuzhou.github.io/) (周宇),  [Xiang Chen](https://smartse.github.io/) (陈翔), and [David Lo](http://www.mysmu.edu/faculty/davidlo/).
I have published over 30 papers <a href='https://scholar.google.com/citations?user=JFoOXQwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the international SE conferences (e.g., SANER, ICSME) and journals (e.g., TSE, TOSEM, EMSE).

# 🔥 News
- *2025.05*: &nbsp;🎉 One paper is accepted by **ACL Main**!
- *2025.05*: &nbsp;🎉 One paper is accepted by **TSE**!
- *2025.05*: &nbsp;🎉 One paper is accepted by **TOSEM**!
- *2025.05*: &nbsp;🎉 One paper is accepted by **TOSEM**!
- *2025.02*: &nbsp;🎉 One paper is accepted by **IST**!

# 📖 Educations
- *2024.08 - 2025.07*, Visiting Ph.D student, Singapore Management University, Singapore.
- *2022.09 - present*, Nanjing University of Aeronautics and Astronautics, major in Software Engineering. 
- *2019.09 - 2022.06*, Nantong University, major in Computer Technology.
- *2015.09 - 2019.06*, Nantong University, major in Software Engineering.
  
# 📝 Selected Publications
1. ``TOSEM'25`` **Less is More: DocString Compression in Code Generation**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, WEI CHENG, XIANGYU ZHANG, Xiang Chen, Terry Yue Zhuo, KE LIU, XIN ZHOU, David Lo, and Taolue Chen
    In *ACM Transactions on Software Engineering and Methodology*, To Appear. 2025. 

    __IF2024: 6.6__, <span style="color:red">CCF-A</span>  
    [[Code](https://github.com/NTDXYG/ShortenDoc)]
    [[DOI]()]

2. ``TOSEM'25`` **DeCE: Deceptive Cross-Entropy Loss Designed for Defending Backdoor Attacks**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiang Chen, Xiangyu Zhang, Terry Yue Zhuo, David Lo, and Taolue Chen.   
    In *ACM Transactions on Software Engineering and Methodology*, To Appear. 2025.

    __IF2024: 6.6__, <span style="color:red">CCF-A</span>  
    [[Code](https://github.com/NTDXYG/DeCE)]
    [[DOI]()]

3. ``TSE'24`` **Chain-of-Thought in Neural Code Generation: From and For Lightweight Language Models**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiang Chen, Xiangyu Zhang, Terry Yue Zhuo, and Taolue Chen.   
    In *Transactions on Software Engineering*, Sept. 2024. 

    __IF2024: 6.5__, <span style="color:red">CCF-A</span>  
    [[Code](https://github.com/NTDXYG/COTTON)]
    [[DOI](https://doi.org/10.1109/TSE.2024.3440503)]

4. ``TOSEM'24`` **How Important are Good Method Names in Neural Code Generation? A Model Robustness Perspective**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Wenhua Yang, Tao Yue, Xiang Chen, and Taolue Chen.  
    In *ACM Transactions on Software Engineering and Methodology*, March, 2024. 

    __IF2024: 6.6__, <span style="color:red">CCF-A</span>   
    [[Code](https://github.com/NTDXYG/RADAR)]
    [[DOI](https://dl.acm.org/doi/10.1145/3630010)]

5. ``TSE'25`` **Anchor Attention, Small Cache: Code Generation with Large Language Models**.  
    Xiangyu Zhang, Yu Zhou, <span style="color:blue">Guang Yang</span>, Harald C. Gall, Taolue Chen.  
    In *Transactions on Software Engineering*, To appear, 2025. 

    __IF2025: 6.6__, <span style="color:red">CCF-A</span>   

6. ``ACL Main'25`` **Beyond Sequences: Two-dimensional Representation and Dependency Encoding for Code Generation**.  
    Xiangyu Zhang, Yu Zhou, <span style="color:blue">Guang Yang</span>, Wei Cheng, Taolue Chen.  
    In *The 63rd Annual Meeting of the Association for Computational Linguistics*, To appear, 2025. 

    <span style="color:red">CCF-A</span>  

7. ``计算机研究与发展'24`` **CodeScore-R：用于评估代码合成功能准确性的自动化鲁棒指标**.  
    <span style="color:blue">杨光</span>, 周宇, 陈翔,  张翔宇.  
    In *计算机研究与发展*, 2024. 

    __IF2024: 4.149__, <span style="color:red">中文 CCF-A</span>   
    [[DOI](https://doi.org/10.7544/issn1000-1239.202330715)]

8. ``软件学报'21`` **代码注释自动生成方法综述**.  
    陈翔, <span style="color:blue">杨光</span>, 崔展齐, 孟国柱, 王赞.  
    In *软件学报*, July, 2021. 

    __IF2021: 3.993__, <span style="color:red">中文 CCF-A</span>  
    [[DOI](https://doi.org/10.13328/j.cnki.jos.006258)]

9. ``KBS'22`` **CCGIR: Information Retrieval-based Code Comment Generation Method for Smart Contracts**.  
    <span style="color:blue">Guang Yang</span>, Ke Liu, Xiang Chen, Yanlin Zhou, Chi Yu, and Hao Lin.  
    In *Knowledge-Based Systems*, February, 2022. 

    __IF2022: 8.139__, <span style="color:red">SCI-Q1</span>  
    [[Code](https://github.com/NTDXYG/CCGIR)]
    [[DOI](https://doi.org/10.1016/j.knosys.2021.107858)]

# 🔍 Services

## Journal Reviewing

- ``CCF-B`` Automated Software Engineering
- ``CCF-B`` Information Processing & Management
- ``CCF-C`` Expert Systems With Applications
- ``CCF-C`` Soft Computing
- ``CCF-C`` Engineering Applications of Artificial Intelligence

## Conference Activities

- ``CCF-A`` ACL 2025, PC Member
- ``CCF-A`` IJCAI 2025, PC Member
- ``CCF-C`` IJCNN 2025, Reviewer
- ``ICLR`` ICLR 2025, Reviewer
- ``ICLR workshop``DL4C@ICLR 2025, Reviewer
- ``CCF-B workshop`` MSR4P&S@SANER 2025, PC Member
- ``CCF-B`` EMNLP 2023, Reviewer
