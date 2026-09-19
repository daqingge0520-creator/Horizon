---
layout: default
title: "Horizon Summary: 2026-09-19 (ZH)"
date: 2026-09-19
lang: zh
---

> 从 22 条内容中筛选出 10 条重要资讯。

---

1. [谷歌在 AOSP 发布前推出 Pixel 独占 Android API](#item-1) ⭐️ 9.0/10
2. [Cloudflare 通过数学优化节省 100TB 内存](#item-2) ⭐️ 9.0/10
3. [Xcode 27.1 Beta 发布，支持 iPhone Duo](#item-3) ⭐️ 9.0/10
4. [Photon-Emission-Guided Laser Fault Injection Enables RP2350 Secure Debug](#item-4) ⭐️ 9.0/10
5. [OpenJev](#item-5) ⭐️ 8.0/10
6. [Quoting Thariq Shihipar](#item-6) ⭐️ 7.0/10
7. [I'm a Principal Applied Scientist at AWS who builds AI services like Amazon Bedrock and Lex. AMA! (D)](#item-7) ⭐️ 7.0/10
8. [How is RLCD (jev) RL? (D)](#item-8) ⭐️ 7.0/10
9. [Cloudflare Quick Tunnels](#item-9) ⭐️ 6.0/10
10. [JMLR submission experience (D)](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [谷歌在 AOSP 发布前推出 Pixel 独占 Android API](https://grapheneos.social/@GrapheneOS/117282080803799576) ⭐️ 9.0/10

据报道，谷歌正在 Android 17 中推出 Pixel 独占的新 Android API，在将其发布到 Android 开源项目（AOSP）之前。这种在 AOSP 发布前保留新 API 的做法自 Android 3.x 以来从未出现过。 此举预示着 Android 可能偏离其开源原则，引发了对谷歌日益增长的平台控制和反竞争行为的担忧。这可能会严重影响定制 ROM 和替代 Android 实现的未来可行性。 这些新 API 是 Pixel 独占更新的一部分，这意味着依赖这些 API 的功能将仅在运行 Pixel SDK 版本的 Pixel 设备上可用，这可能导致 Android 生态系统碎片化。这标志着谷歌偏离了其通常将新 API 发布到 AOSP 供所有制造商和开发者使用的做法。

hackernews · theanonymousone · 9月18日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=49758736)

**背景**: Android 开源项目（AOSP）是 Android 操作系统的基础，它提供免费的开源代码，供制造商和开发者创建和定制基于 Android 的系统。传统上，新的 Android API 会发布到 AOSP，以确保所有 Android 实现都能访问相同的核心功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Android_(operating_system)">Android (operating system) - Wikipedia</a></li>
<li><a href="https://source.android.com/docs/setup/about">AOSP overview | Android Open Source Project</a></li>

</ul>
</details>

**社区讨论**: 社区对谷歌的行为表达了强烈担忧，认为其具有反竞争性，背叛了 Android 的开源精神，尤其影响了 GrapheneOS 等定制 ROM。许多用户呼吁进行监管，并探索替代方案以减少对谷歌服务和生态系统的依赖。

**标签**: `#Android`, `#Open Source`, `#Google`, `#Mobile OS`, `#Platform Control`

---

<a id="item-2"></a>
## [Cloudflare 通过数学优化节省 100TB 内存](https://blog.cloudflare.com/saving-100-tb-of-ram-with-math/) ⭐️ 9.0/10

Cloudflare 宣布了一项重大的工程成就，详细介绍了他们如何通过实施先进的数学优化技术，在其系统中额外节省了 100TB 的 RAM。这项优化代表了其大规模基础设施在内存效率方面的显著提升。 这种优化对于像 Cloudflare 这样的大规模云基础设施提供商至关重要，它展示了创新的内存管理如何在大规模分布式系统中带来显著的成本节约和效率提升。这突显了在数据需求不断增长的时代，深厚的工程专业知识持续的重要性。 此次内存节省是通过先进的数学技术实现的，社区讨论深入探讨了一致性哈希和 Ketama 等具体方法。一位评论者甚至提出了一种替代的哈希方案，通过优化服务器分区选择和哈希函数，可能额外节省 600TiB 的内存。

hackernews · f311a · 9月18日 18:51 · [社区讨论](https://news.ycombinator.com/item?id=49758580)

**背景**: 内存优化是管理大规模云基础设施的关键方面，旨在通过高效利用 RAM 来降低运营成本并提高性能。常用的技术包括识别和消除冗余数据，或采用概率数据结构，这些结构以近似答案为代价，显著减少内存占用。这对于处理大量数据的分布式系统至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://datatas.com/how-to-optimize-probabilistic-data-structures-for-large-scale-analytics/">How to Optimize Probabilistic Data Structures for Large-Scale ...</a></li>
<li><a href="https://martinuke0.github.io/posts/2026-01-03-mastering-probabilistic-data-structures-a-very-detailed-tutorial-from-simple-to-complex/">Mastering Probabilistic Data Structures: A Very Detailed ...</a></li>
<li><a href="https://www.researchgate.net/publication/316537067_Static_Memory_Deduplication_for_Performance_Optimization_in_Cloud_Computing">(PDF) Static Memory Deduplication for Performance Optimization in...</a></li>

</ul>
</details>

**社区讨论**: 社区普遍赞扬了 Cloudflare 在优化方面的努力，其中一位评论者提出了一种替代的哈希系统，可能额外节省 600TiB 的内存。讨论还涉及了对软件开发工作更广泛的影响，以及 AI 在理解复杂代码库方面的潜力。

**标签**: `#System Optimization`, `#Cloud Infrastructure`, `#Distributed Systems`, `#Memory Management`, `#Large Scale Systems`

---

<a id="item-3"></a>
## [Xcode 27.1 Beta 发布，支持 iPhone Duo](https://developer.apple.com/documentation/xcode-release-notes/xcode-27_1-release-notes) ⭐️ 9.0/10

苹果发布了 Xcode 27.1 Beta，为开发者提供了关键工具和模拟器，以便他们开始为即将推出的 iPhone Duo（一款具有独特外形尺寸的全新苹果设备）测试和优化其应用程序。 此次发布意义重大，因为它为即将推出的 iPhone Duo（一款具有独特折叠外形尺寸的全新苹果重要设备）引入了关键支持，这将通过要求应用程序进行适配和优化来影响庞大的开发者生态系统。 Xcode 27.1 Beta 包含了模拟器和 UIKit 应用程序现代化技能，以帮助开发者调整布局，适应 iPhone Duo 独特的折叠外形，该设备具有多个显示区域、屏下摄像头，并支持 Wi-Fi 7 和蓝牙 6。

hackernews · CameronBanga · 9月18日 18:39 · [社区讨论](https://news.ycombinator.com/item?id=49758419)

**背景**: iPhone Duo 是一款即将推出的苹果设备，其独特的折叠外形是其主要特征，这给开发者带来了新的挑战，即如何使应用程序在不同屏幕状态之间无缝过渡并利用多个显示区域。开发者必须考虑应用程序在设备折叠或展开时如何显示和运行，以及如何利用额外的显示空间和新的交互功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://fatbobman.com/en/weekly/issue-153">The Opportunities and Challenges of iPhone Duo -- Fatbobman's Swift Weekly #153</a></li>
<li><a href="https://www.devclass.com/development/2026/09/16/apple-iphone-duo-makes-developers-think-in-folds/5296425">Apple iPhone Duo makes developers think in folds</a></li>
<li><a href="https://en.wikipedia.org/wiki/IPhone_Duo">iPhone Duo - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区表达了兴奋和担忧并存的情绪，开发者们正在积极地在 iPhone Duo 模拟器上测试他们的应用程序。许多人预计，现有应用程序在新的折叠外形设备上最初可能看起来未优化或“损坏”，特别是旧应用程序，不过苹果的 UIKit 现代化工具被认为是帮助适配的有用资源。

**标签**: `#Xcode`, `#iOS Development`, `#Apple`, `#Mobile Development`, `#New Hardware`

---

<a id="item-4"></a>
## [Photon-Emission-Guided Laser Fault Injection Enables RP2350 Secure Debug](https://donjon.ledger.com/blog/rp2350-secure-debug-laser-fault-injection/) ⭐️ 9.0/10

Ledger's security researchers demonstrated a sophisticated photon-emission-guided laser fault injection attack to bypass the secure debug features of the new Raspberry Pi RP2350 microcontroller.

hackernews · synack · 9月18日 16:54 · [社区讨论](https://news.ycombinator.com/item?id=49757050)

**标签**: `#Hardware Security`, `#Fault Injection`, `#Microcontrollers`, `#Embedded Systems`, `#Cybersecurity`

---

<a id="item-5"></a>
## [OpenJev](https://openjev.com/) ⭐️ 8.0/10

OpenJev presents an open-source approach to structured output from large language models, sparking a robust community discussion on its novelty, technical implementation, and comparison to existing solutions.

hackernews · ilreb · 9月18日 09:42 · [社区讨论](https://news.ycombinator.com/item?id=49752041)

**标签**: `#Large Language Models`, `#Structured Output`, `#Open Source`, `#AI/ML Engineering`, `#Semantic Decoding`

---

<a id="item-6"></a>
## [Quoting Thariq Shihipar](https://simonwillison.net/2026/Sep/18/thariq-shihipar/) ⭐️ 7.0/10

Claude Code is introducing support for `AGENTS.md` files to define agent instructions, built upon an upcoming 'Claude Code mods' system that enables custom modifications and improves the tool's adaptability.

rss · Simon Willison · 9月18日 19:09

**标签**: `#AI Agents`, `#LLM Development`, `#Developer Tools`, `#Customization`, `#Open Source`

---

<a id="item-7"></a>
## [I'm a Principal Applied Scientist at AWS who builds AI services like Amazon Bedrock and Lex. AMA! (D)](https://www.reddit.com/r/MachineLearning/comments/1wjuki0/im_a_principal_applied_scientist_at_aws_who/) ⭐️ 7.0/10

A Principal Applied Scientist at AWS, who contributes to AI services such as Amazon Bedrock and Lex, hosts an Ask Me Anything session to share insights on their career, daily work, and research in conversational AI.

reddit · r/MachineLearning · /u/Amazon_Careers · 9月18日 16:13

**标签**: `#AI/ML`, `#AWS`, `#Applied Science`, `#Career Development`, `#Conversational AI`

---

<a id="item-8"></a>
## [How is RLCD (jev) RL? (D)](https://www.reddit.com/r/MachineLearning/comments/1wk6iei/how_is_rlcd_jev_rl_d/) ⭐️ 7.0/10

A user questions why RLCD (jev) is considered Reinforcement Learning, suggesting its differentiable outputs might make it solvable with supervised learning and asking about the nature of its RL environment.

reddit · r/MachineLearning · /u/Relative_Wallaby_823 · 9月18日 23:54

**标签**: `#Reinforcement Learning`, `#Machine Learning`, `#Supervised Learning`, `#RLCD`, `#Conceptual`

---

<a id="item-9"></a>
## [Cloudflare Quick Tunnels](https://try.cloudflare.com/) ⭐️ 6.0/10

Cloudflare has launched a new landing page for its existing Quick Tunnels service, sparking community discussion about the product's age, maintenance issues, and alternative secure tunneling solutions.

hackernews · jcbhmr · 9月18日 14:18 · [社区讨论](https://news.ycombinator.com/item?id=49754785)

**标签**: `#Cloudflare`, `#Networking`, `#Tunnels`, `#Infrastructure`, `#Security`

---

<a id="item-10"></a>
## [JMLR submission experience (D)](https://www.reddit.com/r/MachineLearning/comments/1wk9hwm/jmlr_submission_experience_d/) ⭐️ 6.0/10

A Comp Sci PhD student seeks advice on JMLR's current relevance and submission experience, as their statistics-focused supervisor wants to publish there for tenure, raising questions about journal vs. conference prestige in mainstream ML.

reddit · r/MachineLearning · /u/d_edge_sword · 9月19日 02:11

**标签**: `#Machine Learning`, `#Academic Publishing`, `#Research Strategy`, `#PhD Life`, `#JMLR`

---