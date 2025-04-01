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
- *2025.05*: &nbsp;🎉 One paper is accepted by **TOSEM**!
- *2025.02*: &nbsp;🎉 One paper is accepted by **IST**!
- *2024.08*: &nbsp;🎉 One paper is accepted by **TSE**!

# 📖 Educations
- *2024.08 - 2025.08*, Visiting Ph.D student, Singapore Management University, Singapore.
- *2022.09 - present*, Nanjing University of Aeronautics and Astronautics, major in Software Engineering. 
- *2019.09 - 2022.06*, Nantong University, major in Computer Technology.
- *2015.09 - 2019.06*, Nantong University, major in Software Engineering.
  
# 📝 Selected Publications
1. ``TOSEM'25`` **DeCE: Deceptive Cross-Entropy Loss Designed for Defending Backdoor Attacks**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiang Chen, Xiangyu Zhang, Terry Yue Zhuo, David Lo, and Taolue Chen.   
    In *ACM Transactions on Software Engineering and Methodology*, To Appear. 2025. (__IF2024: 6.6__, <span style="color:red">CCF-A</span>)   
    [[Code](https://github.com/NTDXYG/DeCE)]
    [[DOI]()]

2. ``TSE'24`` **Chain-of-Thought in Neural Code Generation: From and For Lightweight Language Models**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiang Chen, Xiangyu Zhang, Terry Yue Zhuo, and Taolue Chen.   
    In *Transactions on Software Engineering*, Sept. 2024. (__IF2024: 6.5__, <span style="color:red">CCF-A</span>)   
    [[Code](https://github.com/NTDXYG/COTTON)]
    [[DOI](https://doi.org/10.1109/TSE.2024.3440503)]

3. ``TOSEM'24`` **How Important are Good Method Names in Neural Code Generation? A Model Robustness Perspective**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Wenhua Yang, Tao Yue, Xiang Chen, and Taolue Chen.  
    In *ACM Transactions on Software Engineering and Methodology*, March, 2024. (__IF2024: 6.6__, <span style="color:red">CCF-A</span>)   
    [[Code](https://github.com/NTDXYG/RADAR)]
    [[DOI](https://dl.acm.org/doi/10.1145/3630010)]

4. ``计算机研究与发展'24`` **CodeScore-R：用于评估代码合成功能准确性的自动化鲁棒指标**.  
    <span style="color:blue">杨光</span>, 周宇, 陈翔,  张翔宇.  
    In *计算机研究与发展*, 2024. (__IF2024: 4.149__, <span style="color:red">中文 CCF-A</span>)   
    [[DOI](https://doi.org/10.7544/issn1000-1239.202330715)]

5. ``KBS'22`` **CCGIR: Information Retrieval-based Code Comment Generation Method for Smart Contracts**.  
    <span style="color:blue">Guang Yang</span>, Ke Liu, Xiang Chen, Yanlin Zhou, Chi Yu, and Hao Lin.  
    In *Knowledge-Based Systems*, February, 2022. (__IF2022: 8.139__, <span style="color:red">SCI-Q1</span>)   
    [[Code](https://github.com/NTDXYG/CCGIR)]
    [[DOI](https://doi.org/10.1016/j.knosys.2021.107858)]

6. ``IST'25`` **Assessing and Improving Syntactic Adversarial Robustness of Pre-trained Models for Code Translation**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiangyu Zhang, Xiang Chen, Tingting Han, and Taolue Chen.  
    In *Information and Software Technology*, To Appear. 2025. (__IF2025: 3.8__, <span style="color:red">CCF-B</span>)   
    [[Code](https://github.com/NTDXYG/COTR)]
    [[DOI]()]

7. ``EMSE'23`` **A Syntax-Guided Multi-Task Learning Approach for Turducken-Style Code Generation**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiang Chen, Xiangyu Zhang, Yiran Xu, Tingting Han, and Taolue Chen.  
    In *Empirical Software Engineering*, October, 2023. (__IF2023: 4.1__, <span style="color:red">CCF-B</span>)   
    [[Code](https://github.com/NTDXYG/TurduckenGen)]
    [[DOI](https://doi.org/10.1007/s10664-023-10372-1)]

8. ``JSS'23`` **ExploitGen: Template-Augmented Exploit Code Generation Based on CodeBERT**.  
    <span style="color:blue">Guang Yang</span>, Yu Zhou, Xiang Chen, Xiangyu Zhang, Tingting Han, Taolue Chen.  
    In *Journal of Systems and Software*, March, 2023. (__IF2023: 3.5__, <span style="color:red">CCF-B</span>)   
    [[Code](https://github.com/NTDXYG/ExploitGen)]
    [[DOI](https://doi.org/10.1016/j.jss.2022.111577)]

9. ``SANER'22`` **DualSC: Automatic Generation and Summarization of ShellCode via Transformer and Dual Learning**.  
    <span style="color:blue">Guang Yang</span>, Xiang Chen, Yanlin Zhou, and Chi Yu.  
    In *Proceedings of the 29th IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER)*, March, 2022. (<span style="color:red">CCF-B</span>)  
    [[Code](https://github.com/NTDXYG/DualSC)]
    [[DOI](https://doi.org/10.1109/SANER53432.2022.00052)]

10. ``APSEC'21`` **Fine-grained Pseudo-code Generation Method via Code Feature Extraction and Transformer**.  
    <span style="color:blue">Guang Yang</span>, Yanlin Zhou, Xiang Chen, and Chi Yu.  
    In *Proceedings of the 28th Asia-Pacific Software Engineering Conference (APSEC)*, December, 2021. (<span style="color:red">CCF-C</span>)   
    [[Code](https://github.com/NTDXYG/DeepPseudo)]
    [[DOI](https://doi.org/10.1109/APSEC53868.2021.00029)]

11. ``SEKE'21`` **DeepSCC: Source Code Classification Based on Fine-Tuned RoBERTa**.  
     <span style="color:blue">Guang Yang</span>, Yanlin Zhou, Chi Yu, and Xiang Chen.  
     In *Proceedings of the 33rd International Conference on Software Engineering and Knowledge Engineering (SEKE)*, July, 2021. (<span style="color:red">CCF-C</span>)   
     [[Code](https://github.com/NTDXYG/DeepPseudo)]
     [[DOI](https://doi.org/10.18293/seke2021-005)]

# 🔍 Services

## Journal Reviewing

- ``CCF-B`` Automated Software Engineering
- ``CCF-B`` Information Processing & Management
- ``CCF-C`` Expert Systems With Applications
- ``CCF-C`` Soft Computing
- ``CCF-C`` Engineering Applications of Artificial Intelligence

## Conference Activities

- ``CCF-A`` IJCAI 2025, PC Member
- ``CCF-C`` IJCNN 2025, Reviewer
- ``ICLR`` ICLR 2025, Reviewer
- ``ICLR workshop``DL4C@ICLR 2025, Reviewer
- ``CCF-B workshop`` MSR4P&S@SANER 2025, PC Member
- ``CCF-B`` EMNLP 2023, Reviewer
