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

I am currently a third year Ph.D. student at <a href="https://sg-vilab.github.io/people/">VI-Lab</a>, Nanyang Technological University, supervised by Prof. <a href="https://scholar.google.com/citations?user=uYmK-A0AAAAJ&hl=en&oi=ao">Shijian Lu</a>. I received my B.S. degree from <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjOteGdxb2BAxWBoGMGHQvJAkcQFnoECBIQAQ&url=https%3A%2F%2Fwww.zju.edu.cn%2Fenglish%2F&usg=AOvVaw3Z42KzM3Yu8rBgysZ5oIcc&opi=89978449">Zhejiang University</a> in 2021, supervised by Prof. Hong Zhou. 

My research interests lie in vision-language pre-training and foundation model adaptation.

<span class='anchor' id='news'></span>

# 🔥 News
- *2024.11*: Delighted to be one of the <a href="https://neurips.cc/Conferences/2024/ProgramCommittee"><b>Top Reviewers</b></a> at <b>NeurIPS 2024.</b>
- *2024.09*: One paper is accepted by <b>NeurIPS 2024.</b>
- *2024.07*: One paper is accepted by <b>ECCV 2024.</b>
- *2024.03*: One paper is accepted by <b>CVPR 2024.</b>
- *2023.09*: One paper is accepted by <b>NeurIPS 2023.</b>
- *2022.07*: One paper is accepted by <b>ECCV 2022.</b>

<span class='anchor' id='publications'></span>

# 📝 Publications 

[//]: # (----------- NeurIPS 2024 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/cca_attn.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<b>Mitigating Object Hallucination via Concentric Causal Attention</b>](https://arxiv.org/abs/2410.15926) 

<u><b>Yun Xing</b></u>\*, Yiheng Li\*, Ivan Laptev, Shijian Lu

<i>NeurIPS, 2024</i>

[<a href="https://arxiv.org/abs/2410.15926">paper</a>] [<a href="https://github.com/xing0047/cca-llava">code</a>] 

</div>
</div>


[//]: # (----------- ECCV 2024 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/ECCV24_CAT_SAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<b>CAT-SAM: Conditional Tuning Network for Few-Shot Adaptation of Segmentation Anything Model</b>](https://arxiv.org/pdf/2402.03631.pdf) 

Aoran Xiao\*, Weihao Xuan\*, Heli Qi, <u><b>Yun Xing</b></u>, Ruijie Ren, Xiaoqin Zhang, Ling Shao, Shijian Lu

<i>ECCV, 2024</i>

[<a href="https://arxiv.org/pdf/2402.03631.pdf">paper</a>] [<a href="https://github.com/weihao1115/cat-sam">code</a>] 

</div>
</div>



[//]: # (----------- CVPR 2024 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR24_IFA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<b>Cross-Domain Few-Shot Segmentation via Iterative Support-Query Correspondence Mining</b>](https://arxiv.org/pdf/2401.08407.pdf) 

Jiahao Nie*, <u><b>Yun Xing</b></u>\*, Gongjie Zhang, Pei Yan, Aoran Xiao, Yap-Peng Tan, Alex C. Kot, Shijian Lu

<i>CVPR, 2024</i>

[<a href="https://arxiv.org/pdf/2401.08407.pdf">paper</a>] [<a href="https://github.com/niejiahao1998/IFA">code</a>]

</div>
</div>



[//]: # (----------- NeurIPS 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/NIPS23_CoCu.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<b>Rewrite Caption Semantics: Bridging Semantic Gaps for Language Supervised Semantic Segmentation</b>](https://arxiv.org/pdf/2309.13505.pdf) 

<u><b>Yun Xing</b></u>, Jian Kang, Aoran Xiao, Jiahao Nie, Ling Shao, Shijian Lu

<i>NeurIPS, 2023</i>

[<a href="https://arxiv.org/pdf/2309.13505.pdf">paper</a>] [<a href="https://github.com/xing0047/rewrite">code</a>]

</div>
</div>



[//]: # (----------- ECCV 2022 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/ECCV22_TPS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<b>Domain Adaptive Video Segmentation via Temporal Pseudo Supervision</b>](https://arxiv.org/pdf/2207.02372.pdf) 

<u><b>Yun Xing</b></u>\*, Dayan Guan*, Jiaxing Huang, Shijian Lu

<i>ECCV, 2022</i>

[<a href="https://arxiv.org/pdf/2207.02372.pdf">paper</a>] [<a href="https://github.com/xing0047/TPS">code</a>]

</div>
</div>



<span class='anchor' id='education'></span>

# 📖 Education
- *2023.01 - Present:* Doctor of Philosophy, School of Computer Science and Engineering, Nanyang Technological University
- *2021.08 - 2022.11:* Master in Artificial Intelligence, School of Computer Science and Engineering, Nanyang Technological University
- *2017.09 - 2021.07:* Bachelor in Biomedical Engineering and Instrument Science, Zhejiang University


<span class='anchor' id='service'></span>
# 💻 Service
## Conference Reviewer
- CVPR/ICML/ECCV/NeurIPS 2024 (Top Reviewers@NeurIPS)
- ICLR/AISTATS/CVPR/ICML 2025

<span class='anchor' id='teaching'></span>
# Teaching
- [SC1015](https://www.ntu.edu.sg/docs/librariesprovider124/economics-and-data-science/sc1015-introduction-to-data-science-ai.pdf?Status=Master&sfvrsn=b6e8f226_4): Introduction to Data Science and Artificial Intelligence, NTU, 2024 Spring

[//]: # (**Contact:** xing0047@e.ntu.edu.sg)

**Last Update:** Nov 6, 2024

[//]: # (Thanks for the template of <a href="https://github.com/RayeRen/acad-homepage.github.io">Yi Ren</a>)
