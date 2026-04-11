---
permalink: /
title: ""
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

I am a first-year PhD student at the Hong Kong Polytechnic University, under the supervison of <a href='https://www4.comp.polyu.edu.hk/~csqli/'>Prof. Qing Li</a>. I was a mphil at <a href='http://39.103.203.133/'>Information Retrieval and Knowledge Mining Laboratory</a> under the supervision by <a href='https://sim.whu.edu.cn/info/1631/13983.htm'>Prof. Wei Lu</a> and <a href='https://simjwz.whu.edu.cn/info/1391/11051.htm'>Dr. Yu</a>.

My research interest includes recommender system and large language model. Please feel free to contact me by email if you are seeking related academic collaborations.

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=gPBckEwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=gPBckEwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News

- *2026.04*: &nbsp; Our paper “*ReRec: Reasoning-Augmented LLM-based Recommendation Assistant via Reinforcement Fine-tuning*” has been accepted by **ACL 2026**.

- *2025.10*: &nbsp; Our benchmark paper “*Towards Next-Generation Recommender Systems: A Benchmark for Personalized Recommendation Assistant with LLMs*” has been accepted by **WSDM 2026**.

<!-- - *2025.10*: &nbsp; Check out our paper on <a href='https://arxiv.org/pdf/2510.14629'>“*MR.Rec: Synergizing Memory and Reasoning for Personalized Recommendation Assistant with LLMs*”</a>.

- *2025.03*: &nbsp; Check out our paper on <a href='https://arxiv.org/abs/2503.09382'>"*Towards Next-Generation Recommender Systems: A Benchmark for Personalized Recommendation Assistant with LLMs*"</a>. -->
- *2025.03*: &nbsp; Our survey paper on "*Graph Machine Learning in the Era of Large Language Models (LLMs)*" has been accepted by **ACM TIST**.
<!-- - *2024.04*: &nbsp; Check our newest survey <a href='https://arxiv.org/abs/2404.14928'>"*Graph Machine Learning in the Era of Large Language Models (LLMs)*"</a>. -->
- *2024.04*: &nbsp;🎉🎉 Our paper has been accepted by ACM Computing Surveys. 

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='../images/papers/ReRec.png' alt='ReRec publication teaser'>
  </div>
  <div class='paper-box-text'>
    <div class='paper-title'>ReRec: Reasoning-Augmented LLM-based Recommendation Assistant via Reinforcement Fine-tuning</div>
    <div class='paper-authors'><strong>Jiani Huang</strong>, Shijie Wang, Liangbo Ning, Wenqi Fan, Qing Li</div>
    <div class='paper-venue'>ACL 2026</div>
    <div class='paper-summary'>We introduce ReRec, a reasoning-augmented recommendation assistant trained with reinforcement fine-tuning to better align multi-step recommendation decisions with user preferences and improve recommendation quality in conversational settings.</div>
    <div class='paper-links'>
      <a href='https://arxiv.org/abs/2604.07851'>Paper</a>
      <a href='https://github.com/jiani-huang/ReRec'>Code</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='../images/papers/recbench.png' alt='RecBench publication teaser'>
  </div>
  <div class='paper-box-text'>
    <div class='paper-title'>Towards Next-Generation Recommender Systems: A Benchmark for Personalized Recommendation Assistant with LLMs</div>
    <div class='paper-authors'><strong>Jiani Huang</strong>, Shijie Wang, Liangbo Ning, Wenqi Fan, Shuaiqiang Wang, Dawei Yin, Qing Li</div>
    <div class='paper-venue'>WSDM 2026</div>
    <div class='paper-summary'>This work builds a benchmark for personalized recommendation assistants with LLMs, covering realistic user requests, item candidates, and evaluation dimensions that expose where current models still struggle with preference understanding and recommendation reasoning.</div>
    <div class='paper-links'>
      <a href='https://arxiv.org/abs/2503.09382'>Paper</a>
      <a href='https://github.com/jiani-huang/RecBench'>Code</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='../images/papers/graph-llm.png' alt='Graph LLM survey teaser'>
  </div>
  <div class='paper-box-text'>
    <div class='paper-title'>Graph Machine Learning in the Era of Large Language Models (LLMs)</div>
    <div class='paper-authors'>Shijie Wang*, <strong>Jiani Huang*</strong>, Wenqi Fan, Zhikai Chen, Yu Song, Wenzhuo Tang, Haitao Mao, Hui Liu, Xiaorui Liu, Dawei Yin, Qing Li</div>
    <div class='paper-venue'>ACM Transactions on Intelligent Systems and Technology</div>
    <div class='paper-summary'>This survey reviews the fast-growing intersection between graph machine learning and large language models, summarizing how LLMs enhance graph tasks, how graph techniques support LLMs, and which benchmarks and open problems matter next.</div>
    <div class='paper-links'>
      <a href='https://arxiv.org/abs/2404.14928'>Paper</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='../images/papers/figure-table-detection.png' alt='Figure and table detection publication teaser'>
  </div>
  <div class='paper-box-text'>
    <div class='paper-title'>An effective method for figures and tables detection in academic literature</div>
    <div class='paper-authors'>Fengchang Yu, <strong>Jiani Huang</strong>, Wei Lu</div>
    <div class='paper-venue'>Information Processing &amp; Management</div>
    <div class='paper-summary'>We propose a practical method for detecting figures and tables in academic documents, combining page layout and visual cues to improve extraction accuracy across complex scholarly article formats.</div>
    <div class='paper-links'>
      <a href='https://www.sciencedirect.com/science/article/pii/S0306457323000237'>Paper</a>
    </div>
  </div>
</div>


# 🎖 Honors and Awards
- *2021.09* Graduate Entrance Scholarship (**top 10%**), *Wuhan University*
- *2020.11* The National Bronze Award in The 11th Challenge Cup Competition, *Ministry of Education of China*
- *2019.09* Outstanding Student First-Class Scholarship, *Wuhan University*
- *2018.11* The Third Prize of the 10th National University Mathematics Competition, *Ministry of Education of China*

# 📖 Educations
- *2021.09 - 2024.06*, Mphil, Wuhan University. 
- *2017.09 - 2021.06*, Undergraduate, Wuhan University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
<!-- - *2020.05 - 2020.10*, [Lorem](https://github.com/), China. -->
- *2023.04 - 2023.10*, PingAn Technology , Shenzhen.
- *2020.05 - 2020.10*, NetEase, Beijing.
