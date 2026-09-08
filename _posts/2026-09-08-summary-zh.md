---
layout: default
title: "Horizon Summary: 2026-09-08 (ZH)"
date: 2026-09-08
lang: zh
---

> 从 23 条内容中筛选出 12 条重要资讯。

---

1. [Broadcom 撤回 VDDK 下载，VMware 迁移难度增加](#item-1) ⭐️ 9.0/10
2. [IEEE T-PAMI 主编确认被拒稿件存在缺失的正面审稿意见](#item-2) ⭐️ 9.0/10
3. [I've factored the RSA keys of a Certificate Authority from the 90s](#item-3) ⭐️ 8.0/10
4. [TALA Is Open-Source](#item-4) ⭐️ 8.0/10
5. [Jellyfin 发布 12.0 主要版本，修复性能问题](#item-5) ⭐️ 8.0/10
6. [Watch Los Angeles get built, one building at a time (1880–2026)](#item-6) ⭐️ 8.0/10
7. [Quoting Jakub Pachocki](#item-7) ⭐️ 8.0/10
8. [Video compressor](#item-8) ⭐️ 8.0/10
9. [Mercator ↔ Equal Earth](#item-9) ⭐️ 8.0/10
10. [Generating Bad Apple autonomously from a single initial state using a tiny recurrent dynamical system (417k params) (P)](#item-10) ⭐️ 8.0/10
11. [My lab found a way to migrate between embedding models with zero downtime. (R)](#item-11) ⭐️ 8.0/10
12. [Rustuna: A High-Performance Rust Implementation of Optuna (P)](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Broadcom 撤回 VDDK 下载，VMware 迁移难度增加](https://www.virtualizationhowto.com/2026/09/leaving-vmware-just-got-harder-after-broadcom-pulled-vddk-downloads/) ⭐️ 9.0/10

Broadcom 已撤回对 VMware 虚拟磁盘开发套件（VDDK）下载的访问权限，VDDK 是管理 VMware 虚拟磁盘的关键库，此举使客户从 VMware 生态系统迁移变得更加困难。 此举显著增加了 VMware 客户的供应商锁定，因为它阻碍了他们迁移到其他虚拟化平台的能力，在整个企业虚拟化社区引发了广泛担忧。 VDDK 对于包括备份解决方案在内的第三方软件读写 VMware 虚拟磁盘至关重要，其撤回迫使迁移依赖于更间接的方法或手动转换。尽管像 Linux `qemu-img`这样的工具仍然可以转换`.vmdk`镜像，但 VDDK 的缺失使在新虚拟机管理程序上创建正确的虚拟硬件配置的整个过程变得复杂。

hackernews · josephcsible · 9月7日 20:32 · [社区讨论](https://news.ycombinator.com/item?id=49602699)

**背景**: VMware 虚拟磁盘开发套件（VDDK）是一个关键库，它使外部软件（如备份工具和迁移实用程序）能够与 VMware 虚拟磁盘文件进行交互和管理。它允许应用程序直接读写虚拟机磁盘数据，而无需在虚拟机内部运行，这对于镜像级备份和高效的虚拟机迁移至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.shapeblue.com/broadcom-vddk-download-vmware-to-kvm/">Broadcom Removes VDDK Pages Without Explanation: What You Need to Know - ShapeBlue</a></li>
<li><a href="https://github.com/vmware-archive/virtual-disks">GitHub - vmware-archive/virtual-disks: Go Library for Virtual Disk Development Kit · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区对 Broadcom 的举动表达了深切的悲伤和失望，前 VMware 工程师感叹公司在 Broadcom 所有权下创新能力的衰退。用户分享了他们迁移到 Hyper-V 和 Proxmox 等替代虚拟化管理程序的经验，讨论了技术困难和潜在的解决方案，同时一些人指出 Proxmox 迁移对于小型设置来说可能出乎意料地简单。

**标签**: `#Virtualization`, `#VMware`, `#Broadcom`, `#Vendor Lock-in`, `#IT Infrastructure`

---

<a id="item-2"></a>
## [IEEE T-PAMI 主编确认被拒稿件存在缺失的正面审稿意见](https://www.reddit.com/r/MachineLearning/comments/1w9v43o/update_eic_confirmed_ghost_reviewerhow_to_get/) ⭐️ 9.0/10

IEEE T-PAMI 主编正式承认，一篇最初获得三份正面审稿意见但被拒的稿件，确实存在一份缺失的第四份正面审稿意见。这一确认是在 IEEE 计算机学会诚信委员会进行了长达六个月的调查后作出的。 这一事件揭露了顶级期刊在学术诚信和同行评审流程方面的严重漏洞，可能损害人们对科学出版和研究伦理的信任。它凸显了编辑监督和问责制中的关键问题，可能影响全球研究人员。 副主编（AE）最初根据一份据称来自“第四位审稿人”的负面意见做出了拒稿决定，而实际第四位审稿人的正面反馈却莫名其妙地从系统中消失了。主编的确认证实了作者关于审稿流程处理不当的说法，表明这是一次严重的程序性失误而非简单的疏忽。

reddit · r/MachineLearning · /u/cussealin · 9月7日 15:22

**背景**: IEEE T-PAMI（模式分析与机器智能汇刊）是由 IEEE 计算机学会出版的一份备受推崇的月度同行评审科学期刊，专注于模式分析和机器智能领域。同行评审是学术出版中的一个关键过程，专家们对学术作品进行评估，以确保其在发表前的质量和有效性。主编（EIC）负责监督整个期刊，而副主编（AE）则负责管理具体的稿件，包括协调同行评审和提出建议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IEEE_PAMI">IEEE PAMI</a></li>
<li><a href="https://scholar9.com/journal/ieee-transactions-on-pattern-analysis-and-machine-2069">IEEE Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI) | Scholar9</a></li>

</ul>
</details>

**标签**: `#Academic Integrity`, `#Peer Review`, `#Scientific Publishing`, `#Research Ethics`

---

<a id="item-3"></a>
## [I've factored the RSA keys of a Certificate Authority from the 90s](https://mcpherrin.ca/2026/09/07/rsa.html) ⭐️ 8.0/10

A researcher successfully factored the 512-bit RSA keys of a Certificate Authority from the 1990s, demonstrating historical cryptographic vulnerabilities using modern computing power and custom tools.

hackernews · ahlCVA · 9月8日 01:16 · [社区讨论](https://news.ycombinator.com/item?id=49604637)

**标签**: `#Cryptography`, `#Cybersecurity`, `#RSA`, `#Historical Systems`, `#Security Research`

---

<a id="item-4"></a>
## [TALA Is Open-Source](https://d2lang.com/blog/tala-is-open-source/) ⭐️ 8.0/10

TALA, an advanced auto-layout engine for D2 diagrams, has been open-sourced, making a previously commercial tool freely available to improve technical diagramming.

hackernews · alixanderwang · 9月7日 23:37 · [社区讨论](https://news.ycombinator.com/item?id=49604150)

**标签**: `#Diagramming`, `#Open Source`, `#Software Engineering`, `#Visualization`, `#Auto Layout`

---

<a id="item-5"></a>
## [Jellyfin 发布 12.0 主要版本，修复性能问题](https://jellyfin.org/posts/jellyfin-release-12.0/) ⭐️ 8.0/10

Jellyfin 正式发布了 12.0 版本，这是一个重要的更新，旨在解决之前版本中的性能问题，并为用户提供更流畅的升级体验。此版本经过数月的大量开发，包括七个发布候选版本。 这一主要版本对开源媒体服务器生态系统意义重大，它为 Plex 等专有解决方案提供了一个强大且高性能的替代方案，并赋予用户对其自托管媒体更大的控制权。改进的稳定性与性能可以促进更广泛的采用，并巩固 Jellyfin 作为领先的自由软件媒体系统的地位。 升级到 12.0 的用户报告称迁移过程快速且顺利，尽管一些用户提到媒体标题暂时消失，需要重新扫描才能恢复。开发过程包括七个发布候选版本，表明经过了彻底的测试阶段，但一些用户仍然报告持续的字幕问题，尤其是在 Android 客户端流式传输到 Chromecast 时。

hackernews · 0xC0ncord · 9月8日 01:56 · [社区讨论](https://news.ycombinator.com/item?id=49604861)

**背景**: Jellyfin 是一个免费开源的媒体系统，允许用户将个人数字媒体从自托管服务器流式传输到各种客户端设备。它是 Plex 和 Emby 等专有媒体服务器的社区驱动替代品，专注于用户控制、隐私，并且不收取订阅费或依赖外部第三方连接。自托管是指运行自己的服务器来托管应用程序和数据的做法，与基于云的服务相比，它为个人提供了增强的自主权和数据所有权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>
<li><a href="https://jellyfin.org/docs/general/about/">About Jellyfin | Jellyfin</a></li>
<li><a href="https://en.wikipedia.org/wiki/Self-hosting_(network)">Self-hosting (network) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论显示对 Jellyfin 12.0 普遍持积极态度，用户称赞升级体验快速且顺利，并对性能问题的解决充满信心。许多人将 Jellyfin 视为 Plex 等专有解决方案的重要开源替代品，但一些用户仍然报告持续的字幕问题，尤其是在 Android 客户端流式传输到 Chromecast 时。

**标签**: `#Media Server`, `#Open Source`, `#Software Release`, `#Self-hosting`, `#Community Feedback`

---

<a id="item-6"></a>
## [Watch Los Angeles get built, one building at a time (1880–2026)](https://lax-skyline.parcelscope.net/) ⭐️ 8.0/10

This interactive visualization maps the construction of Los Angeles buildings from 1880 to 2026, prompting a rich community discussion on urban development, housing policy, and historical infrastructure.

hackernews · rustywasm · 9月7日 18:52 · [社区讨论](https://news.ycombinator.com/item?id=49601655)

**标签**: `#Data Visualization`, `#Urban Planning`, `#History`, `#Los Angeles`, `#Housing Policy`

---

<a id="item-7"></a>
## [Quoting Jakub Pachocki](https://simonwillison.net/2026/Sep/7/jakub-pachocki/) ⭐️ 8.0/10

Jakub Pachocki, Chief Scientist at OpenAI, advocates for developing powerful, aligned AI for defense against other AI threats, while strongly cautioning against using this need as an excuse for reckless development.

rss · Simon Willison · 9月7日 22:26

**标签**: `#AI Safety`, `#AI Ethics`, `#OpenAI`, `#AI Development`, `#Future of AI`

---

<a id="item-8"></a>
## [Video compressor](https://simonwillison.net/2026/Sep/7/video-compressor/) ⭐️ 8.0/10

Simon Willison developed a web-based video compressor tool, powered by WebAssembly FFMPEG, with the significant assistance of Claude Fable 5.1 in Claude Code for web.

rss · Simon Willison · 9月7日 18:29

**标签**: `#AI-assisted development`, `#WebAssembly`, `#FFMPEG`, `#Web tools`, `#Video processing`

---

<a id="item-9"></a>
## [Mercator ↔ Equal Earth](https://simonwillison.net/2026/Sep/7/equal-earth/) ⭐️ 8.0/10

Simon Willison created an AI-assisted D3 tool to visually demonstrate the animated transition between the Mercator and Equal Earth map projections, prompted by a recent UN vote.

rss · Simon Willison · 9月7日 16:24

**标签**: `#geospatial`, `#data visualization`, `#AI-assisted development`, `#D3.js`, `#map projections`

---

<a id="item-10"></a>
## [Generating Bad Apple autonomously from a single initial state using a tiny recurrent dynamical system (417k params) (P)](https://www.reddit.com/r/MachineLearning/comments/1wa8rub/generating_bad_apple_autonomously_from_a_single/) ⭐️ 8.0/10

This work proposes a novel method to autonomously generate the entire Bad Apple video from a single initial state using a compact recurrent dynamical system that learns continuous temporal flow in latent space.

reddit · r/MachineLearning · /u/SEBADA321 · 9月8日 00:05

**标签**: `#Machine Learning`, `#Recurrent Neural Networks`, `#Generative Models`, `#Video Generation`, `#Implicit Neural Representations`

---

<a id="item-11"></a>
## [My lab found a way to migrate between embedding models with zero downtime. (R)](https://www.reddit.com/r/MachineLearning/comments/1wabmm7/my_lab_found_a_way_to_migrate_between_embedding/) ⭐️ 8.0/10

Researchers developed "embedflow," a method to migrate between embedding models with zero downtime by reranking a subset of documents, achieving comparable retrieval quality to the target model and significantly reducing upgrade time for large document corpuses.

reddit · r/MachineLearning · /u/Potential_Low_1183 · 9月8日 02:16

**标签**: `#Embedding Models`, `#RAG`, `#MLOps`, `#Information Retrieval`, `#System Design`

---

<a id="item-12"></a>
## [Rustuna: A High-Performance Rust Implementation of Optuna (P)](https://www.reddit.com/r/MachineLearning/comments/1w9nyhz/rustuna_a_highperformance_rust_implementation_of/) ⭐️ 8.0/10

Rustuna is a newly released high-performance, memory-efficient Rust implementation of the Optuna hyperparameter optimization framework, designed to be Optuna-compatible while eliminating Python dependencies and reducing memory footprint.

reddit · r/MachineLearning · /u/c-bata · 9月7日 10:01

**标签**: `#Machine Learning`, `#Hyperparameter Optimization`, `#Rust`, `#Performance`, `#Software Engineering`

---