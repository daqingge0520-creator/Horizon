---
layout: default
title: "Horizon Summary: 2026-07-04 (ZH)"
date: 2026-07-04
lang: zh
---

> 从 20 条内容中筛选出 12 条重要资讯。

---

1. [GLM5.2 on AMD MI355X at 2626 tok/s/node at over 2x lower cost than Blackwell](#item-1) ⭐️ 9.0/10
2. [调查间谍软件的欧洲议会议员被飞马间谍软件入侵](#item-2) ⭐️ 9.0/10
3. [对比解码差异法（CDD）通过灰盒 Logit 访问恢复 LLM 微调数据](#item-3) ⭐️ 9.0/10
4. [SearXNG：注重隐私的元搜索引擎在本地 AI 模型和代理中获得新关注](#item-4) ⭐️ 8.0/10
5. [Jamesob 的本地运行最先进大型语言模型指南](#item-5) ⭐️ 8.0/10
6. [Open Source AI Gap Map](#item-6) ⭐️ 8.0/10
7. [Quoting Josh W. Comeau](#item-7) ⭐️ 8.0/10
8. [Fable's judgement](#item-8) ⭐️ 8.0/10
9. [H64LM: A 249M-parameter Mixture-of-Experts Transformer built from scratch in PyTorch (P)](#item-9) ⭐️ 8.0/10
10. [Giant trees have no trouble pumping water to top branches](#item-10) ⭐️ 7.0/10
11. [Leanstral 1.5: Proof abundance for all](#item-11) ⭐️ 6.0/10
12. [June 2026 newsletter](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM5.2 on AMD MI355X at 2626 tok/s/node at over 2x lower cost than Blackwell](https://www.wafer.ai/blog/glm52-amd) ⭐️ 9.0/10

A new benchmark showcases GLM5.2 achieving 2626 tokens/second/node on AMD MI355X, claiming over 2x lower cost for LLM inference compared to Nvidia Blackwell.

hackernews · latchkey · 7月3日 21:49 · [社区讨论](https://news.ycombinator.com/item?id=48780417)

**标签**: `#AI Hardware`, `#LLM Inference`, `#Benchmarking`, `#AMD`, `#Cost Efficiency`

---

<a id="item-2"></a>
## [调查间谍软件的欧洲议会议员被飞马间谍软件入侵](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 9.0/10

公民实验室报告称，一名正在积极调查间谍软件的欧洲议会议员（MEP）Kouloglou，其 iPhone 于 2022 年 10 月 21 日左右以及 2023 年 3 月 6 日和 7 日被“飞马”（Pegasus）间谍软件成功入侵。这一发现是在 Kouloglou 于 2026 年 5 月联系公民实验室进行取证分析后得出的。 这一事件意义重大，因为它表明国家支持的监视直接针对正在积极调查间谍软件的民选官员，从而破坏了民主机构，并引发了对数字隐私和立法程序完整性的严重担忧。它凸显了先进间谍软件对政治人物的普遍威胁以及对人权和治理的更广泛影响。 这位欧洲议会议员设备的感染日期与此前发现的针对欧洲俄语和白俄罗斯语流亡记者及活动家的“飞马”（Pegasus）行动存在重叠，这表明可能存在一个获授权在多个欧洲国家进行间谍活动的“飞马”客户。同时，人们也担心同一部受感染的手机可能泄露了机密的个人医疗信息和政府文件。

hackernews · ledoge · 7月3日 20:38 · [社区讨论](https://news.ycombinator.com/item?id=48779683)

**背景**: “飞马”（Pegasus）是由以色列网络武器公司 NSO Group 开发的一种复杂间谍软件，旨在秘密地远程安装到运行 iOS 和 Android 操作系统的手机上。它以无需用户交互即可渗透智能手机而闻名，允许其操作者提取大量数据并远程控制设备功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus ( spyware ) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区对此表示强烈担忧，认为这一事件是欧盟成员国滥用“飞马”（Pegasus）间谍软件的更广泛模式的一部分，特别是提到了希腊和波兰的案例，并强调了一位调查间谍软件的欧洲议会议员被攻击的讽刺意味。评论者暗示这可能与针对记者和活动家的更广泛行动有关，并质疑欧洲议会在工作和个人设备分离方面的政策。

**标签**: `#Cybersecurity`, `#Pegasus Spyware`, `#State-sponsored Hacking`, `#European Politics`, `#Digital Privacy`

---

<a id="item-3"></a>
## [对比解码差异法（CDD）通过灰盒 Logit 访问恢复 LLM 微调数据](https://www.reddit.com/r/MachineLearning/comments/1umn2dk/contrastive_decoding_diffing_cdd_recovering/) ⭐️ 9.0/10

一种名为对比解码差异法（CDD）的新方法，仅通过灰盒 Logit 访问，即可从经过窄范围微调的大型语言模型（LLM）中恢复逐字的微调数据，而无需完整的权重访问或探测语料库。该方法显著优于先前的白盒技术，如激活差异透镜（ADL），在 SDF 基准测试中，对各种模型实现了 4+/5 的逐字恢复分数。 这一突破对人工智能领域的数据隐私、模型安全和知识产权具有重大影响，因为它展示了一种即使在有限模型访问权限下也能高保真地提取敏感训练数据的方法。这凸显了微调 LLM 的脆弱性，并要求重新评估当前部署和共享此类模型的安全实践。 CDD 通过直接对比基础模型和微调模型的 Logit 来操作，这是一种与 ADL 激活差异引导相对应的“输出级模拟”，并且在无需进行个体校准或层选择的情况下，实现了卓越的逐字恢复（4+/5，而 ADL 低于 3/5）。一个意外发现是，在不同的微调领域中，始终恢复出了虚构人物“Dr. Elena Rodriguez”，揭示了 LLM 生成合成训练数据中存在的偏见。

reddit · r/MachineLearning · /u/CebulkaZapiekana · 7月3日 19:01

**背景**: 大型语言模型（LLM）通常会针对特定数据集进行“微调”，以适应特定任务或领域，这可能会嵌入独特的信息。“灰盒 Logit 访问”是指可以观察模型对每个 token 的输出概率（Logit），但无法访问权重或激活等内部状态的情况，它比黑盒模型提供更多访问权限，但少于白盒模型。通常，对比解码涉及比较输出或内部状态，以引导生成朝向期望的特征。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grey_box_model">Grey box model - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2510.13900v2">Narrow Finetuning Leaves Clearly Readable Traces in Activation ...</a></li>
<li><a href="https://arxiv.org/abs/2309.09117">[2309.09117] Contrastive Decoding Improves Reasoning in Large Language Models</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#LLMs`, `#Data Privacy`, `#Model Security`, `#Finetuning`

---

<a id="item-4"></a>
## [SearXNG：注重隐私的元搜索引擎在本地 AI 模型和代理中获得新关注](https://github.com/searxng/searxng) ⭐️ 8.0/10

SearXNG，一个免费开源的元搜索引擎，因其隐私保护特性以及在为本地 AI 模型和代理提供搜索功能方面的新兴作用而受到社区的重新关注。尽管其原始创建者已转向 Hister 等新项目，SearXNG 仍在持续发展并保持其相关性。 这意义重大，因为它将一个成熟的注重隐私的工具置于新兴 AI 应用的前沿，为 AI 代理和本地 LLM 提供了一种去中心化且保护隐私的信息获取方法。它解决了快速扩展的本地 AI 生态系统中对安全高效数据检索日益增长的需求。 TinySearch 被强调为 SearXNG 的一个封装器，它在信息到达 AI 代理之前优化上下文，从而避免了令牌浪费。SearXNG 还支持 JSON 结果，使其适用于集成到内部文档搜索或 RAG（检索增强生成）应用中，尽管其元搜索性质有时会导致速度变慢或出现验证码挑战。

hackernews · theanonymousone · 7月3日 20:15 · [社区讨论](https://news.ycombinator.com/item?id=48779454)

**背景**: 本地 LLM 是指直接在用户本地计算机或内部网络上运行的大型语言模型，确保所有处理都在设备上进行，从而增强隐私并减少对云服务的依赖。AI 代理是能够通过设计工作流和利用可用工具自主执行任务的系统，它们展现出一定程度的自主性，超越了简单的程序指令。Hister 是 SearXNG 原始创建者的新项目，它是一个全文索引器，可以保存渲染的网页和本地文件，从而实现离线访问和搜索。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/local-llm-when-running-ai-in-house-becomes-smarter-choice-neil-sahota-glgge">Local LLM: When Running AI In-House Becomes the Smarter Choice</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-agents">What Are AI Agents ? | IBM</a></li>
<li><a href="https://github.com/asciimoo/hister">GitHub - asciimoo/hister: Your own search engine · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区对 SearXNG 的隐私优势表达了强烈支持，长期用户赞扬其避免主流搜索引擎的能力。原始创建者 asciimoo 分享了对元搜索概念局限性的见解，并介绍了他的新项目 Hister，而其他人则强调了实际应用，例如 TinySearch 用于优化 SearXNG 与 AI 代理的结合，以及将其用于本地 LLM 的工具调用。用户也提到了偶尔出现的性能问题和验证码挑战，但他们认为这是为了隐私而接受的权衡。

**标签**: `#Metasearch Engine`, `#Privacy`, `#Open Source`, `#AI Agents`, `#Local LLMs`

---

<a id="item-5"></a>
## [Jamesob 的本地运行最先进大型语言模型指南](https://github.com/jamesob/local-llm) ⭐️ 8.0/10

Jamesob 在 GitHub 上发布了一份详细指南，阐述了在本地机器上运行最先进（SOTA）大型语言模型（LLM）的方法和硬件配置。该指南旨在帮助用户搭建用于高级 AI 模型推理的个人系统，但其成本效益主张引发了社区的广泛讨论。 在本地运行大型语言模型（LLM）为用户提供了更高的隐私性、数据控制权，并可能比基于云的服务节省长期成本，这对开发者和研究人员影响深远，使他们能够独立进行实验和定制。这种方法促进了创新，减少了对外部 API 的依赖，使个人更容易接触到先进的人工智能。 该指南提出了约 4 万美元的配置方案，但社区评论指出，由于 GPU 成本，实际可能超过 5 万美元，旨在通过对 GLM-5.2 等模型使用 REAP 剪枝和 Int8-mix NVFP4 量化等技术，实现“接近 Claude Opus”的性能。它还建议了更经济的选择，例如两块 RTX 3090 显卡提供 48GB 显存，以运行 Qwen3.6-27B 等模型。

hackernews · livestyle · 7月3日 15:03 · [社区讨论](https://news.ycombinator.com/item?id=48775921)

**背景**: 最先进（SOTA）大型语言模型（LLM）是高度先进的人工智能模型，能够执行复杂的语言任务，如生成、翻译和问答，它们利用了海量数据集和强大的计算能力。在本地运行这些模型意味着在个人硬件上执行它们，而不是依赖基于云的 API，这通常会带来巨大的挑战，因为它们对内存和处理能力，特别是 GPU 显存有极高的要求，而显存是未经激进量化处理的大型模型在本地运行的主要瓶颈。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rajuhemanth456.medium.com/state-of-the-art-in-large-language-models-llms-a-deep-dive-into-the-cutting-edge-ai-technology-a080283d0729">State-of-the-Art in Large Language Models (LLMs): A Deep Dive into the Cutting-Edge AI Technology | by Hemanth Raju Koneti | Medium</a></li>
<li><a href="https://www.geeksforgeeks.org/deep-learning/recommended-hardware-for-running-llms-locally/">Recommended Hardware for Running LLMs Locally - GeeksforGeeks</a></li>
<li><a href="https://www.kunalganglani.com/blog/running-local-llms-2026-hardware-setup-guide">Local LLM Hardware Guide 2026: VRAM, GPUs, Setup [Tested]</a></li>

</ul>
</details>

**社区讨论**: 社区对该指南的成本效益主张进行了激烈辩论，许多评论者认为，所声称的 4 万美元预算严重低估了实现“接近 Claude Opus”性能的实际成本，一些人认为这需要更昂贵的硬件。人们对高度量化或剪枝模型的质量和安全性表示担忧，同时也有人提出了替代解决方案，例如用于 DeepSeek V4 flash 等模型的 128GB 显存配置，或更经济的 2 块 RTX 3090 配置。

**标签**: `#Local LLMs`, `#AI Hardware`, `#Machine Learning`, `#Open Source AI`, `#Cost Analysis`

---

<a id="item-6"></a>
## [Open Source AI Gap Map](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 8.0/10

Current AI, a non-profit backed by $400m, has launched its Open Source AI Gap Map, an ambitious project to index and categorize 421 open-source AI products across various layers and categories, with a goal to map the entire ecosystem.

rss · Simon Willison · 7月3日 22:04

**标签**: `#Open Source AI`, `#AI Ecosystem`, `#Resource Mapping`, `#Non-profit Initiative`, `#AI Governance`

---

<a id="item-7"></a>
## [Quoting Josh W. Comeau](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 8.0/10

Josh W. Comeau reports a significant decline in his developer course sales, attributing the trend, also observed by other creators, to developers' AI-induced job uncertainty and the rise of LLMs as personalized tutors.

rss · Simon Willison · 7月3日 21:25

**标签**: `#AI Impact`, `#Developer Education`, `#Content Creation`, `#Economic Impact`, `#Career Development`

---

<a id="item-8"></a>
## [Fable's judgement](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 8.0/10

Simon Willison shares expert advice on prompting advanced large language models like Fable/Opus, suggesting that giving them more autonomy and letting them use their own judgment for tasks like testing or model selection can lead to better results and cost efficiency.

rss · Simon Willison · 7月3日 18:51

**标签**: `#Prompt Engineering`, `#Large Language Models`, `#AI Best Practices`, `#Claude AI`, `#Software Development`

---

<a id="item-9"></a>
## [H64LM: A 249M-parameter Mixture-of-Experts Transformer built from scratch in PyTorch (P)](https://www.reddit.com/r/MachineLearning/comments/1umqfd2/h64lm_a_249mparameter_mixtureofexperts/) ⭐️ 8.0/10

H64LM is a 249M-parameter Mixture-of-Experts Transformer implemented entirely from scratch in PyTorch, designed as a research project to provide a deep understanding of modern LLM architectures and their components.

reddit · r/MachineLearning · /u/Loose_Literature6090 · 7月3日 21:18

**标签**: `#Large Language Models`, `#Mixture-of-Experts`, `#PyTorch`, `#Transformer Architecture`, `#Deep Learning Implementation`

---

<a id="item-10"></a>
## [Giant trees have no trouble pumping water to top branches](https://news.exeter.ac.uk/faculty-of-environment-science-and-economy/giant-trees-have-no-trouble-pumping-water-to-top-branches/) ⭐️ 7.0/10

A university news article claims that giant trees efficiently pump water to their highest branches, a finding that appears to challenge previous scientific understanding and theoretical limits.

hackernews · hhs · 7月3日 22:40 · [社区讨论](https://news.ycombinator.com/item?id=48780870)

**标签**: `#Plant Physiology`, `#Botany`, `#Scientific Research`, `#Biology`, `#Environmental Science`

---

<a id="item-11"></a>
## [Leanstral 1.5: Proof abundance for all](https://mistral.ai/news/leanstral-1-5/) ⭐️ 6.0/10

Mistral AI released Leanstral 1.5, a new model for formal verification with Lean 4, but its claims regarding bug detection and performance benchmarks are met with skepticism in the community discussion.

hackernews · programLyrique · 7月3日 22:33 · [社区讨论](https://news.ycombinator.com/item?id=48780801)

**标签**: `#AI`, `#LLM`, `#Formal Verification`, `#Lean 4`, `#Mistral AI`

---

<a id="item-12"></a>
## [June 2026 newsletter](https://simonwillison.net/2026/Jul/3/june-newsletter/#atom-everything) ⭐️ 6.0/10

Simon Willison announces the June edition of his sponsors-only newsletter, outlining topics such as new LLM releases (Claude Fable 5, GPT-5.6, GLM-5.2), AI trends, and updates on his projects like Datasette and sqlite-utils.

rss · Simon Willison · 7月3日 14:50

**标签**: `#AI/ML`, `#LLMs`, `#Datasette`, `#WebAssembly`, `#Tech Trends`

---