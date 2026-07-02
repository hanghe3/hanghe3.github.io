---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

<span class="lang-en">
I am an incoming Ph.D. student at the [FudanNLP Lab](https://nlp.fudan.edu.cn/), [Fudan University](https://www.fudan.edu.cn/), and [Shanghai Innovation Institute](https://www.sii.edu.cn/), advised by Prof. [Tao Gui (桂韬)](https://guitaowufeng.github.io/) and Prof. [Xuanjing Huang (黄萱菁)](https://xuanjing-huang.github.io/).
I am currently a second-year graduate student at [East China Normal University](https://www.ecnu.edu.cn/) (2024-2027), co-advised by Prof. [Chengcheng Wan (万成城)](https://chengcheng-wan.github.io/) and Prof. [Ting Su (苏亭)](https://tingsu.github.io/). I received my B.S. from [China University of Petroleum, Beijing](https://www.cup.edu.cn/) in 2024.</span><span class="lang-zh">我即将加入[复旦大学自然语言处理实验室](https://nlp.fudan.edu.cn/)和[上海创智学院](https://www.sii.edu.cn/)攻读博士学位，在[桂韬](https://guitaowufeng.github.io/)老师和[黄萱菁](https://xuanjing-huang.github.io/)老师的指导下开展研究。目前我是[华东师范大学](https://www.ecnu.edu.cn/)二年级研究生（2024-2027），师从[万成城](https://chengcheng-wan.github.io/)研究员与[苏亭](https://tingsu.github.io/)教授。我于 2024 年在[中国石油大学（北京）](https://www.cup.edu.cn/)获得学士学位。</span>

<span class="lang-en">My research interests include **Agent & Harness**, **Agentic RL (Tool Call)**, and **Multimodal large language models**.</span><span class="lang-zh">我的研究兴趣包括**智能体与任务执行框架（Agent & Harness）**、**面向工具调用的智能体强化学习（Agentic RL for Tool Call）**与**多模态大语言模型**。</span>

<span class="lang-en">Feel free to reach out by email; I am always happy to discuss research ideas and collaborations. ✉️</span><span class="lang-zh">欢迎通过邮件联系我，我很乐意交流研究想法与合作机会。✉️</span>

# 🔥 <span class="lang-en">News</span><span class="lang-zh">最新动态</span> {#news}
- *2026.06*: <span class="lang-en">🎉🎉 **[VistaHop](https://arxiv.org/abs/2606.03273)** is released on arXiv!</span><span class="lang-zh">🎉🎉 **[VistaHop](https://arxiv.org/abs/2606.03273)** 已发布于 arXiv！</span>
- *2026.05*: <span class="lang-en">🎉🎉 **[LocalSearchBench](https://arxiv.org/abs/2512.07436)** is accepted by **SIGKDD 2026**!</span><span class="lang-zh">🎉🎉 **[LocalSearchBench](https://arxiv.org/abs/2512.07436)** 已被 **SIGKDD 2026** 录用！</span>
- *2026.05*: <span class="lang-en">🎉🎉 **[A Very Big Video Reasoning Suite](https://arxiv.org/abs/2602.20159)** is accepted by **ICML 2026**!</span><span class="lang-zh">🎉🎉 **[A Very Big Video Reasoning Suite](https://arxiv.org/abs/2602.20159)** 已被 **ICML 2026** 录用！</span>
- *2025.12*: <span class="lang-en">🎉🎉 **[Promoting Efficient Reasoning with Verifiable Stepwise Reward](https://arxiv.org/abs/2508.10293)** is accepted by **AAAI 2026**!</span><span class="lang-zh">🎉🎉 **[Promoting Efficient Reasoning with Verifiable Stepwise Reward](https://arxiv.org/abs/2508.10293)** 已被 **AAAI 2026** 录用！</span>
- *2025.04*: <span class="lang-en">🎉🎉 **[Clover](https://arxiv.org/abs/2504.00521)** is released on arXiv!</span><span class="lang-zh">🎉🎉 **[Clover](https://arxiv.org/abs/2504.00521)** 已发布于 arXiv！</span>

# 📝 <span class="lang-en">Publications</span><span class="lang-zh">论文发表</span> {#publications}

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD 2026</div><a href="../images/localsearchbench-overview.png"><img src='../images/localsearchbench-overview.png' alt="LocalSearchBench overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### LocalSearchBench: Benchmarking Agentic Search in Real-World Local Life Services

**Hang He**, _Chuhuai Yue, Chengqi Dong, Mingxue Tian, Hao Chen, Zhenfeng Liu, Jiajun Chai*, Xiaohan Wang, Yufei Zhang, Qun Liao, Guojun Yin†, Wei Lin, Chengcheng Wan†, Haiying Sun, Ting Su†_

- <span class="lang-en">Accepted by **SIGKDD 2026** <span style="color: red;">(CCF A)</span>.</span><span class="lang-zh">录用于 **SIGKDD 2026**，<span style="color: red;">CCF A</span>。</span>
- <span class="lang-en">LocalSearchBench is the first comprehensive benchmark for agentic search in local life services, built around real-world merchant data, multi-hop user queries, and constraints such as location, time, ratings, prices, and service availability.</span><span class="lang-zh">LocalSearchBench 是首个面向本地生活服务场景的综合 Agentic Search 评测基准，围绕真实商户数据、多跳用户查询，以及位置、时间、评分、价格、服务可用性等约束构建。</span>
- <span class="lang-en">It introduces LocalPlayground, a unified tool-interaction environment for evaluating whether agents can plan, retrieve, reason, and faithfully synthesize answers across complex local-service workflows.</span><span class="lang-zh">我们进一步构建 LocalPlayground 统一工具交互环境，用于评估智能体在复杂本地生活服务流程中进行规划、检索、推理，并可靠地综合答案的能力。</span>
- <span class="pub-links"><a class="pub-badge pub-badge--hf" href="https://huggingface.co/datasets/localsearchbench/localsearchbench"><span class="pub-badge__icon">🤗</span>Hugging Face</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2512.07436"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--slide" href="../files/LocalSearchBench.pdf?v=20260625"><i class="fas fa-file-powerpoint"></i>Slide</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--video" href="https://www.bilibili.com/video/BV1nm786eEjC/?spm_id_from=333.1387.homepage.video_card.click"><span class="pub-badge__icon pub-badge__icon--bilibili"><img src="../images/bilibili.svg" alt="" aria-hidden="true"></span>Video</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--website" href="https://localsearchbench.github.io/"><i class="fas fa-globe-americas"></i>Website</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--report" href="https://mp.weixin.qq.com/s/-zVRQe4ISf_Sbanc_tVtzg"><i class="fab fa-weixin"></i>Report (美团技术团队)</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><a href="../images/vistahop-overview.png"><img src='../images/vistahop-overview.png' alt="VistaHop overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### VistaHop: Benchmarking Multi-hop Visual Reasoning for Visual DeepSearch

**Hang He**, _Chuhuai Yue, Chengqi Dong, Chengcheng Wan†, Ting Su, Haiying Sun, Jiajun Chai, Xiaohan Wang, Guojun Yin†_

- <span class="lang-en">VistaHop is a benchmark for Visual DeepSearch, evaluating whether multimodal agents can repeatedly inspect images, ground intermediate reasoning in visual evidence, and connect fine-grained clues across long reasoning chains.</span><span class="lang-zh">VistaHop 是面向 Visual DeepSearch 的评测基准，用于评估多模态智能体能否反复检查图像、将中间推理扎根于视觉证据，并在长推理链中连接细粒度线索。</span>
- <span class="lang-en">It contains 300 high-resolution images, 25 visual search scenarios, and 350 multi-hop VQA tasks, together with VistaArena, a unified tool-interaction environment for visual retrieval, image inspection, and evidence-grounded reasoning.</span><span class="lang-zh">VistaHop 包含 300 张高分辨率图像、25 类视觉搜索场景与 350 个多跳视觉问答任务，并构建 VistaArena 统一工具交互环境，支持视觉检索、图像检查与基于证据的推理。</span>
- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2606.03273"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--code" href="https://github.com/ahang0712/vistahop"><i class="fab fa-github"></i>Code</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><a href="../images/clover-overview.png"><img src='../images/clover-overview.png' alt="Clover overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### Automated Detection of Atomicity Violations in Large-Scale Systems

**Hang He***, Yixing Luo*, _Chengcheng Wan†, Ting Su†, Haiying Sun, Geguang Pu_

- <span class="lang-en">Clover is a multi-agent framework for detecting atomicity violations in real-world interrupt-driven programs.</span><span class="lang-zh">Clover 是一个用于检测真实中断驱动程序中原子性违反问题的多智能体框架。</span>
- <span class="lang-en">It combines a Plan Agent with static analysis tools and Expert-Judge agent pairs, enabling iterative detection and validation of atomicity-violation patterns in real aerospace software code.</span><span class="lang-zh">Clover 将 Plan Agent、静态分析工具与 Expert-Judge 智能体对结合起来，支持在真实航天软件代码中对原子性违反模式进行迭代检测与验证。</span>
- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2504.00521"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><a href="../images/stepwise-reward-case.png"><img src='../images/stepwise-reward-case.png' alt="Promoting Efficient Reasoning overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### Promoting Efficient Reasoning with Verifiable Stepwise Reward

Chuhuai Yue, _Chengqi Dong, Yinan Gao, **Hang He**, Jiajun Chai, Guojun Yin, Wei Lin_

- <span class="lang-en">Accepted by **AAAI 2026** <span style="color: red;">(CCF A)</span>.</span><span class="lang-zh">录用于 **AAAI 2026**，<span style="color: red;">CCF A</span>。</span>
- <span class="lang-en">This work targets the overthinking problem in large reasoning models, where models spend excessive tokens on simple questions and sacrifice inference efficiency.</span><span class="lang-zh">该工作关注大推理模型中的过度思考问题，即模型在简单问题上消耗过多推理 token，从而降低推理效率。</span>
- <span class="lang-en">It proposes a rule-based Verifiable Stepwise Reward Mechanism (VSRM) that rewards effective intermediate reasoning states and penalizes ineffective steps, reducing output length while preserving reasoning performance.</span><span class="lang-zh">我们提出基于规则的可验证逐步奖励机制（VSRM），对有效中间推理状态给予奖励、对无效步骤进行惩罚，在保持推理性能的同时显著缩短输出长度。</span>
- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2508.10293"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--report" href="https://mp.weixin.qq.com/s/8OiJucbM3TkZ0FUTVGnAIA"><i class="fab fa-weixin"></i>Report (量子位)</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><a href="../images/vbvr-teaser.png"><img src='../images/vbvr-teaser.png' alt="A Very Big Video Reasoning Suite teaser" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### A Very Big Video Reasoning Suite

Maijunxian Wang, Ruisi Wang, _..._, **Hang He**, _..._, Alan Yuille, Yilun Du, Ziming Liu, Bo Li, Dahua Lin, Ziwei Liu, Vikash Kumar, Yijiang Li, Lei Yang, Zhongang Cai, Hokin Deng

- <span class="lang-en">Accepted by **ICML 2026** <span style="color: red;">(CCF A)</span>.</span><span class="lang-zh">录用于 **ICML 2026**，<span style="color: red;">CCF A</span>。</span>
- <span class="lang-en">VBVR is a large-scale suite for studying video reasoning beyond visual quality, focusing on spatiotemporal structure such as continuity, interaction, and causality.</span><span class="lang-zh">VBVR 是一个面向视频推理的大规模研究套件，不仅关注视觉质量，还系统考察连续性、交互关系与因果关系等时空结构推理能力。</span>
- <span class="lang-en">It introduces a dataset spanning 200 curated reasoning tasks and over one million video clips, together with VBVR-Bench, a verifiable evaluation framework with rule-based, human-aligned scorers.</span><span class="lang-zh">该工作构建了覆盖 200 类精心设计推理任务、超过 100 万个视频片段的数据集，并提出 VBVR-Bench 可验证评测框架，通过基于规则且符合人类判断的评分器进行可复现评估。</span>
- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2602.20159"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--website" href="https://video-reason.com/"><i class="fas fa-globe-americas"></i>Website</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--code" href="https://github.com/Video-Reason/VBVR-EvalKit"><i class="fab fa-github"></i>Code</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--report" href="https://mp.weixin.qq.com/s/XaLnom_nFvnoeFJR506-8w"><i class="fab fa-weixin"></i>Report (新智元)</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><a href="../images/rlfactory-framework.png"><img src='../images/rlfactory-framework.png' alt="RLFactory framework" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### RLFactory: A Plug-and-Play Reinforcement Learning Post-Training Framework for LLM Multi-Turn Tool-Use

Jiajun Chai, _Guojun Yin, Zekun Xu, Chuhuai Yue, Yi Jia, Siyu Xia, Xiaohan Wang, Jiwen Jiang, Xiaoguang Li, Chengqi Dong, **Hang He**, Wei Lin_

- <span class="lang-en">RLFactory is a plug-and-play reinforcement learning post-training framework for multi-turn tool-use agents, integrating rollout generation, reward design, and RL training into a unified workflow.</span><span class="lang-zh">RLFactory 是一个面向多轮工具调用智能体的即插即用式强化学习后训练框架，将轨迹生成、奖励设计与强化学习训练整合到统一流程中。</span>
- <span class="lang-en">It supports efficient training for LLM agents across text and multimodal tool-use scenarios, making it easier to build, evaluate, and iterate on tool-augmented agent systems.</span><span class="lang-zh">该框架支持在文本与多模态工具调用场景中高效训练大模型智能体，便于构建、评估和迭代工具增强型智能体系统。</span>
- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2509.06980"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--code" href="https://github.com/Simple-Efficient/RL-Factory"><i class="fab fa-github"></i>Code</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--report" href="https://mp.weixin.qq.com/s/jvqBJU1gsvkKkeBX_R0fnw"><i class="fab fa-weixin"></i>Report (深度学习与自然语言处理)</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--stars" href="https://github.com/Simple-Efficient/RL-Factory" data-github-stars="Simple-Efficient/RL-Factory"><i class="fas fa-star"></i><span class="github-stars-count">Stars</span></a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><a href="../images/tapo-model.png"><img src='../images/tapo-model.png' alt="TAPO overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### TAPO: Tool-Aware Policy Optimization via Credit Transfer for Multimodal Search Agents

Chengqi Dong, Chuhuai Yue, **Hang He**, _Yandong Liu, Fenghe Tang, S Kevin Zhou, Xiaohan Wang, Jiajun Chai, Guojun Yin_

- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2606.05784"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><a href="../images/toolforge-overview.png"><img src='../images/toolforge-overview.png' alt="ToolForge overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### ToolForge: A Data Synthesis Pipeline for Multi-Hop Search without Real-World APIs

Hao Chen, Zhexin Hu, Jiajun Chai, Haocheng Yang, **Hang He**, _Xiaohan Wang, Wei Lin, Luhang Wang, Guojun Yin, Zhuofeng Zhao_

- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2512.16149"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a><span class="pub-separator">|</span><a class="pub-badge pub-badge--code" href="https://github.com/Buycar-arb/ToolForge"><i class="fab fa-github"></i>Code</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><a href="../images/miva-model.png"><img src='../images/miva-model.png' alt="Training Multi-Image Vision Agents overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

### Training Multi-Image Vision Agents via End2End Reinforcement Learning

_Chengqi Dong, Chuhuai Yue_, **Hang He**, _Rongge Mao, Fenghe Tang, S Kevin Zhou, Zekun Xu, Xiaohan Wang, Jiajun Chai, Wei Lin, Guojun Yin_

- <span class="pub-links"><a class="pub-badge pub-badge--paper" href="https://arxiv.org/abs/2512.08980"><span class="pub-badge__icon pub-badge__icon--arxiv"><img src="../images/arxiv.svg" alt="" aria-hidden="true"></span>Paper</a></span>

</div>
</div>

# 💻 <span class="lang-en">Internship</span><span class="lang-zh">实习经历</span> {#internship}

- <span style="display: inline-flex; align-items: center; justify-content: center; width: 160px; height: 75px; vertical-align: middle; margin-right: 10px;"><img src="../images/NEX.svg" alt="NEX-AGI" style="max-width: 160px; max-height: 50px;"></span><span style="display: inline-block; vertical-align: middle;"><span class="lang-en">**NEX-AGI**, Shanghai Qiji Zhifeng Co., Ltd., Shanghai</span><span class="lang-zh">**NEX-AGI**，上海奇绩智峰，上海</span></span><br><span class="lang-en">*Research directions: General Agent (long-horizon agent task synthesis and Agentic RL)*</span><span class="lang-zh">*研究方向：通用智能体（长程智能体任务合成及其 Agentic RL）*</span>
- <span class="lang-en">Advised by [Zhou Shao (邵洲)](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&hl=zh-CN&user=d7Aflf0AAAAJ), and [Rui Zheng (郑锐)](https://scholar.google.com/citations?hl=en&user=7Z0V_SoAAAAJ&view_op=list_works&sortby=pubdate).</span><span class="lang-zh">由[邵洲](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&hl=zh-CN&user=d7Aflf0AAAAJ)与[郑锐](https://scholar.google.com/citations?hl=en&user=7Z0V_SoAAAAJ&view_op=list_works&sortby=pubdate)指导。</span>
- <span style="display: inline-flex; align-items: center; justify-content: center; gap: 8px; width: 125px; height: 58px; vertical-align: middle; margin-right: 10px;"><img src="../images/themes/美团.png" alt="Meituan" style="max-width: 54px; max-height: 46px;"><img src="../images/themes/wenxiaotuan.png" alt="Wenxiaotuan" style="max-width: 44px; max-height: 44px;"></span><span style="display: inline-block; vertical-align: middle;"><span class="lang-en">**Meituan**, Search and Recommendation Platform Department, Agentic System X (ASX) Team</span><span class="lang-zh">**美团**，搜索和推荐平台部，Agentic System X (ASX) 团队</span></span><br><span class="lang-en">*Research directions: reinforcement learning, multimodal post-training, and multimodal retrieval*</span><span class="lang-zh">*研究方向：强化学习、多模态后训练与多模态检索*</span>
- <span class="lang-en">Advised by [Jiajun Chai](https://scholar.google.com/citations?user=yDdfap0AAAAJ&hl=en), and [Guojun Yin](https://gjyin.github.io/).</span><span class="lang-zh">由[柴嘉骏](https://scholar.google.com/citations?user=yDdfap0AAAAJ&hl=en)与[殷国君](https://gjyin.github.io/)指导。</span>

# 🎤 <span class="lang-en">Service and Talks</span><span class="lang-zh">服务与报告</span> {#service-and-talks}

1. <span class="lang-en">Reviewer for ACL ARR, SIGKDD 2026, ACM MM 2026, CVPR 2026, and WWW 2026.</span><span class="lang-zh">ACL ARR、SIGKDD 2026、ACM MM 2026、CVPR 2026 与 WWW 2026 审稿人。</span>
2. <span class="lang-en">Transformer Seminar Host.</span><span class="lang-zh">Transformer Seminar 主持人。</span>

# 🎖 <span class="lang-en">Awards</span><span class="lang-zh">荣誉奖项</span> {#awards}

1. <span class="lang-en">National Scholarship, 2022.</span><span class="lang-zh">国家奖学金，2022。</span>
2. <span class="lang-en">Outstanding Graduate Award, Beijing, 2024.</span><span class="lang-zh">北京市优秀毕业生，2024。</span>
3. <span class="lang-en">Sinopec Talent Scholarship, 2021.</span><span class="lang-zh">中国石化英才奖学金，2021。</span>

# 📖 <span class="lang-en">Education</span><span class="lang-zh">教育经历</span> {#education}

- <span class="lang-en">*2024 - Present*, Graduate student, **East China Normal University**.</span><span class="lang-zh">*2024 - 至今*，研究生，**华东师范大学**。</span>
- <span class="lang-en">*2020 - 2024*, B.S., **China University of Petroleum, Beijing**.</span><span class="lang-zh">*2020 - 2024*，学士，**中国石油大学（北京）**。</span>

<section class="visitor-map" id="visitor-map">
  <h1><span class="lang-en">Visitor Statistics</span><span class="lang-zh">访客统计</span></h1>
  <div class="visitor-map-container">
    <a href="https://info.flagcounter.com/pXJO" target="_blank" rel="noopener noreferrer">
      <img src="https://s01.flagcounter.com/map/pXJO/size_s/txt_000000/border_CCCCCC/pageviews_1/viewers_0/flags_0/" alt="Visitor map" />
    </a>
  </div>
</section>

<script>
  document.querySelectorAll('[data-github-stars]').forEach(function (badge) {
    var repo = badge.getAttribute('data-github-stars');
    var count = badge.querySelector('.github-stars-count');

    fetch('https://api.github.com/repos/' + repo)
      .then(function (response) {
        if (!response.ok) throw new Error('GitHub API unavailable');
        return response.json();
      })
      .then(function (data) {
        if (typeof data.stargazers_count === 'number') {
          count.textContent = data.stargazers_count.toLocaleString();
        }
      })
      .catch(function () {
        count.textContent = 'Stars';
      });
  });
</script>
