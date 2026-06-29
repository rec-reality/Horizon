---
layout: default
title: "Horizon Summary: 2026-06-29 (ZH)"
date: 2026-06-29
lang: zh
---

> 从 78 条内容中筛选出 12 条重要资讯。

---

1. [美国最高法院裁定地理围栏搜查令需受宪法保护](#item-1) ⭐️ 9.0/10
2. [谷歌 AI 审稿人处理 1 万篇论文，周转时间缩至 30 分钟](#item-2) ⭐️ 9.0/10
3. [vLLM v0.24.0：支持 MiniMax-M3 并优化 DeepSeek-V4](#item-3) ⭐️ 8.0/10
4. [火箭实验室拟 80 亿美元收购铱星](#item-4) ⭐️ 8.0/10
5. [WATaBoy：Game Boy JIT 编译至 WASM 超越原生解释器](#item-5) ⭐️ 8.0/10
6. [运行 CUDA 内核时会发生什么？](#item-6) ⭐️ 8.0/10
7. [欧洲 ISP 要求版权方为过度屏蔽负责](#item-7) ⭐️ 8.0/10
8. [Meta 利用 Instagram 照片为智能眼镜做广告](#item-8) ⭐️ 8.0/10
9. [Ornith-1.0：用于代理式编程的开源权重 LLM](#item-9) ⭐️ 8.0/10
10. [比亚迪自研智驾芯片璇玑 A3 预计 2027 年首搭](#item-10) ⭐️ 8.0/10
11. [EML 树被证明是通用逼近器](#item-11) ⭐️ 8.0/10
12. [长鑫存储与腾讯签近 30 亿美元 DRAM 供应协议](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [美国最高法院裁定地理围栏搜查令需受宪法保护](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

美国最高法院裁定，允许执法部门获取特定区域内所有移动设备位置数据的地理围栏搜查令，必须遵守第四修正案关于合理根据和特定性的保护要求。 这一里程碑式的裁决极大地限制了无证地理定位搜查，是数字隐私的重大胜利，迫使执法部门对此类搜索必须获得针对性的搜查令。 该案源于一起银行抢劫调查，谷歌的 Sensorvault 提供了案发地点附近 19 台设备的位置数据；法院驳回了政府关于用户对与第三方共享的数据缺乏合理隐私期待的主张。

hackernews · cdrnsf · 6月29日 15:54 · [社区讨论](https://news.ycombinator.com/item?id=48720924)

**背景**: 地理围栏搜查令是一种反向搜查令，强制谷歌等技术公司识别虚拟地理边界内的所有设备。这种搜查令被广泛使用，但因允许无嫌疑的大规模监控而受到批评。第四修正案保护免受不合理搜查，但法院对自愿与第三方共享的位置数据是否仍受隐私保护存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant</a></li>
<li><a href="https://techcrunch.com/2026/06/29/in-major-privacy-win-supreme-court-rules-geofence-warrants-are-protected-by-privacy-rights/">In major privacy win, Supreme Court rules geofence warrants are ...</a></li>

</ul>
</details>

**社区讨论**: 评论者注意到该裁决对 Flock 摄像头等技术的影响，并讨论了阿利托、托马斯和巴雷特大法官的异议。一些人提到了地理定位监视的历史案例（如保拉·布罗德韦尔的识别），其他人则对裁决的范围持谨慎乐观态度。

**标签**: `#privacy`, `#supreme court`, `#geofence`, `#fourth amendment`, `#surveillance`

---

<a id="item-2"></a>
## [谷歌 AI 审稿人处理 1 万篇论文，周转时间缩至 30 分钟](https://www.reddit.com/r/MachineLearning/comments/1uio9rb/googles_agentic_peerreviewer_handled_10k_papers/) ⭐️ 9.0/10

谷歌部署了一个代理式 AI 系统，对提交给 ICML 和 STOC 会议的约 1 万篇论文进行审稿，实现 30 分钟周转时间，比零样本提示多检测出 34%的数学错误。研究结果现已正式发表在一篇论文中。 这表明大规模 AI 辅助同行评审的可行性，可能通过减轻审稿人负担和加快出版周期来改变科学出版流程。它为学术会议的自动化质量控制树立了先例。 该代理式 AI 系统自主运行，使用多个专门代理来分析论文的数学正确性和清晰度。相比零样本提示的 34%改进凸显了结构化基于代理的推理相对于直接 LLM 查询的优势。

reddit · r/MachineLearning · /u/Justgototheeffinmoon · 6月29日 10:05

**背景**: 代理式 AI 指能够在有限人类监督下自主追求目标的 AI 系统，通常使用多个专门代理。零样本提示是一种不给 LLM 任何示例就让其执行任务的技术，仅依赖其预训练知识。这项研究将代理式 AI 应用于同行评审这一传统上人力密集的任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-ai">What is agentic AI? Definition and differentiators | Google Cloud</a></li>
<li><a href="https://aws.amazon.com/what-is/agentic-ai/">What is Agentic AI? - Agentic AI Explained - AWS</a></li>
<li><a href="https://www.linkedin.com/pulse/prompt-engineering-course-essential-few-shot-zero-shot-prompting-3vcnc">Prompt Engineering Course Essential: Few-Shot and Zero - Shot ...</a></li>
<li><a href="https://medium.com/@albert_88839/zero-in-on-the-right-responses-with-zero-shot-and-few-shot-prompting-f50fb154af4d">Zero in on the Right Responses with Zero - Shot and... | Medium</a></li>
<li><a href="https://promplify.ai/blog/zero-shot-prompting/">Zero - Shot Prompting : How to Get Great Results... — Promplify Blog</a></li>

</ul>
</details>

**标签**: `#AI`, `#peer review`, `#machine learning`, `#scientific review`, `#Google`

---

<a id="item-3"></a>
## [vLLM v0.24.0：支持 MiniMax-M3 并优化 DeepSeek-V4](https://github.com/vllm-project/vllm/releases/tag/v0.24.0) ⭐️ 8.0/10

vLLM v0.24.0 已发布，新增了对 MiniMax-M3 模型的支持，并对 DeepSeek-V4 进行了重大优化。该版本包含来自 256 位贡献者的 571 次提交。 此版本标志着 vLLM 作为高性能推理引擎的重大进步，增强了对前沿模型的支持并提高了效率。对 DeepSeek-V4 的优化和 Model Runner V2 的扩展使整个 LLM 服务生态受益。 重要技术新增包括 MiniMax 稀疏注意力（MSA）支持，附带 BF16/FP8 索引器和 MXFP4，为 DeepSeek-V4 引入 FlashInfer 稀疏索引缓存（TTFT 提升 2-4%），以及统一工具调用/推理解析的新的流式解析引擎。该版本还集成了 DeepEP v2 以实现专家并行，并将设备选择移出内部的 CUDA_VISIBLE_DEVICES 管理。

github · khluu · 6月29日 19:41

**背景**: vLLM 是一个用于快速 LLM 推理和服务的开源库，以其高吞吐量和灵活性而广泛使用。MiniMax-M3 是近期以长上下文推理著称的多模态模型，而 DeepSeek-V4 是一个主要语言模型，通过稀疏注意力和专家并行等先进优化技术受益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/flashinfer-ai/flashinfer">GitHub - flashinfer-ai/flashinfer: FlashInfer: Kernel Library for LLM Serving · GitHub</a></li>
<li><a href="https://vllm.ai/blog/2026-06-12-minimax-m3-vllm">MiniMax M3 in vLLM: Day-0 Serving for 1M-Token Multimodal Reasoning</a></li>
<li><a href="https://arxiv.org/abs/2501.01005">[2501.01005] FlashInfer: Efficient and Customizable Attention Engine for LLM Inference Serving</a></li>

</ul>
</details>

**标签**: `#vllm`, `#LLM inference`, `#model optimization`, `#open source`, `#release`

---

<a id="item-4"></a>
## [火箭实验室拟 80 亿美元收购铱星](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-acquire-iridium-historic-deal-creating-fully) ⭐️ 8.0/10

火箭实验室于 6 月 29 日宣布，将以现金加股票的方式收购铱星通信公司，交易价值约 80 亿美元，每股收购价为 54 美元。该交易已获双方董事会批准，预计 2027 年年中完成，尚需监管机构和股东批准。 此次合并将打造一家完全集成的太空公司，融合火箭实验室的发射和航天器制造能力与铱星的全球低轨卫星网络、L 波段频谱及 500 多家合作伙伴。这使火箭实验室能够进入卫星物联网、直连设备及 PNT 服务市场，同时确保稳定的发射基线，类似 SpaceX 的星链策略。 铱星运营着 66 颗活跃低轨卫星，2025 年营收为 8.717 亿美元，EBITDA 利润率为 57%。火箭实验室已获得 36 亿美元过桥贷款承诺以资助此次收购。

hackernews · everfrustrated · 6月29日 14:09 · [社区讨论](https://news.ycombinator.com/item?id=48719485)

**背景**: 铱星卫星星座最初由摩托罗拉开发，于 1998 年投入运营，由 66 颗活跃低轨卫星组成，通过 L 波段和星间链路提供全球语音和数据覆盖。它服务于超过 255 万用户，包括卫星电话和物联网设备，是唯一提供真正全球极地全覆盖的网络。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Iridium_satellite_constellation">Iridium satellite constellation</a></li>
<li><a href="https://grokipedia.com/page/Iridium_satellite_constellation">Iridium satellite constellation</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：有人担忧太空垃圾增加和环境影响，也有人强调其战略价值类似 SpaceX 利用星链拉动发射需求。有评论指出火箭实验室从新西兰企业转变为美国主体。

**标签**: `#space`, `#acquisition`, `#satellite`, `#rocket-lab`, `#iridium`

---

<a id="item-5"></a>
## [WATaBoy：Game Boy JIT 编译至 WASM 超越原生解释器](https://humphri.es/blog/WATaBoy/) ⭐️ 8.0/10

一位本科开发者撰文介绍了 WATaBoy，这是一款 Game Boy 模拟器，通过动态将 SM83 指令重新编译为 WebAssembly，利用浏览器的 JIT 异常，在 iOS 上比原生解释器表现更好。 这项研究展示了一种巧妙的方法，在苹果限制 JIT（仅浏览器例外）的 iOS 上实现 JIT 编译，从而在浏览器环境中实现高性能模拟。 WATaBoy 利用浏览器的 WebAssembly JIT 在运行时编译热门的 Game Boy 代码路径，性能超越了同一设备上的原生解释器。

hackernews · energeticbark · 6月29日 15:02 · [社区讨论](https://news.ycombinator.com/item?id=48720190)

**背景**: 苹果的 iOS 限制阻止应用程序进行 JIT 编译，但浏览器的 JavaScript 引擎除外。通过针对 WebAssembly（在浏览器 JIT 内运行），WATaBoy 有效绕过了这一限制。Game Boy 模拟通常依赖解释 SM83 CPU 指令，这比 JIT 编译慢。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://humphri.es/blog/WATaBoy/">WATaBoy: JIT-ing Game Boy Instructions to Wasm Beats a Native Interpreter</a></li>
<li><a href="https://news.ycombinator.com/item?id=48720190">WATaBoy: JIT-Ing Game Boy Instructions to WASM Beats a Native Interpreter | Hacker News</a></li>
<li><a href="https://github.com/EnergeticBark/WATaBoy">GitHub - EnergeticBark/WATaBoy: A Game Boy emulator with an...</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞该项目对本科生来说令人印象深刻。有人指出 Firefox 比 Chrome/Safari 慢 25%，引发了对浏览器差异的好奇。其他人强调 WASM 开销（约 20%）远小于解释器开销（约 1000%），因此加速在预料之中，但仍然很酷。

**标签**: `#JIT`, `#WebAssembly`, `#GameBoy emulation`, `#performance`, `#browser tech`

---

<a id="item-6"></a>
## [运行 CUDA 内核时会发生什么？](https://fergusfinn.com/blog/what-happens-when-you-run-a-gpu-kernel/) ⭐️ 8.0/10

一篇详细的博客文章，解释了从 CUDA 内核启动到 GPU 执行的全过程，涵盖了门铃（doorbell）和 QMD 机制。

hackernews · mezark · 6月29日 13:11 · [社区讨论](https://news.ycombinator.com/item?id=48718863)

**标签**: `#CUDA`, `#GPU`, `#kernel launch`, `#NVIDIA`, `#graphics programming`

---

<a id="item-7"></a>
## [欧洲 ISP 要求版权方为过度屏蔽负责](https://torrentfreak.com/european-isps-want-rightsholders-held-accountable-for-overblocking-damage/) ⭐️ 8.0/10

欧洲互联网服务提供商（ISP）正在推动在法律上让版权方对过度屏蔽（overblocking）造成的损害负责，即在版权执法过程中错误地屏蔽合法内容。 这一政策转变可能会遏制滥用删除通知的行为，保护互联网自由，影响整个欧洲版权执法与言论自由间的平衡。 过度屏蔽通常由自动内容过滤器或模糊的法院命令导致，其屏蔽范围超出预定目标。ISP 认为版权方应为这种过度行为承担责任。

hackernews · Brajeshwar · 6月29日 16:07 · [社区讨论](https://news.ycombinator.com/item?id=48721072)

**背景**: 过度屏蔽是指互联网过滤器或屏蔽命令意外地屏蔽了合法内容。在欧洲，围绕欧盟版权指令第 17 条的持续辩论凸显了自动过度屏蔽的问题。ISP 现在寻求法律途径，让版权方对造成的损害负责。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://de.wikipedia.org/wiki/Overblocking">Overblocking – Wikipedia</a></li>
<li><a href="https://www.techdirt.com/tag/overblocking/">Overblocking stories at Techdirt.</a></li>
<li><a href="https://legalblogs.wolterskluwer.com/copyright-blog/youtube-copyright-transparency-report-overblocking-is-real/">YouTube Copyright Transparency Report: Overblocking is real | Kluwer Copyright Blog</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍支持让版权方承担责任，一些用户指出美国 DMCA 系统也存在类似问题。但仍有人对此持怀疑态度，认为版权垄断者往往能逃避后果，这种问责可能难以落实。

**标签**: `#internet governance`, `#copyright`, `#censorship`, `#ISP`, `#policy`

---

<a id="item-8"></a>
## [Meta 利用 Instagram 照片为智能眼镜做广告](https://twitter.com/i/status/2071277885646868536) ⭐️ 8.0/10

Meta 正在将 Instagram 用户的照片整合到其 Ray-Ban Meta 智能眼镜的广告中，无需用户明确同意，这重新引发了隐私讨论。这种做法与 Facebook 在 2013 年的类似政策如出一辙。 此举引发了重大的隐私担忧，因为它在未经直接同意的情况下利用用户生成的内容，可能会削弱用户对 Meta 平台的信任。这也凸显了社交媒体中盈利策略与用户权利之间的持续矛盾。 根据社区评论，Meta 的服务条款允许在商业内容中使用个人资料照片，这一做法可追溯到 Facebook 2013 年的政策。Ray-Ban Meta 眼镜于 2023 年发布，配备 1200 万像素摄像头和直播功能，但隐私问题已因指示灯较小而受到批评。

hackernews · notRobot · 6月29日 13:26 · [社区讨论](https://news.ycombinator.com/item?id=48719027)

**背景**: Ray-Ban Meta 智能眼镜是 Meta 与 Ray-Ban 联合开发的第二代产品，配备了改进的摄像头、音频和 Meta AI 集成。Instagram 拥有超过十亿的月活跃用户，使其成为广告中用户生成内容的丰富来源。Meta 将此类内容用于广告的做法从 Facebook 早期起就是一个反复出现的隐私问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meta_glasses">Meta glasses</a></li>
<li><a href="https://www.yellowhead.com/blog/user-generated-content-ugc-ads/">User Generated Content : Why Brands Love UGC... - yellowHEAD</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了沮丧和无奈，指出这种做法在服务条款下已持续多年。一些人强调了广告使用朋友照片的荒谬性，而另一些人建议离开该平台。还有少数人指出这与 Meta 去年使用照片进行 AI 训练的做法类似。

**标签**: `#privacy`, `#meta`, `#instagram`, `#advertising`, `#smartglasses`

---

<a id="item-9"></a>
## [Ornith-1.0：用于代理式编程的开源权重 LLM](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce 发布了 Ornith-1.0 系列开源权重 LLM（MIT 许可），专为代理式编程设计，在编程基准测试上达到最优性能，模型规模最高达 397B 参数。 该发布提供了一个强大且采用宽松许可的编程模型，能够自主运行代理框架，可能加速 AI 辅助软件开发并减少对专有模型的依赖。 Ornith-1.0 提供四种变体：9B 密集、31B 密集、35B MoE 和 397B MoE，基于 Gemma 4（Apache 2.0）和 Qwen 3.5（Apache 2.0）构建。初步测试显示，35B GGUF 量化模型能够熟练处理多工具调用。

rss · Simon Willison · 6月29日 16:17

**背景**: 自脚手架 LLM 通过强化学习迭代生成脚手架代码，以提升模型在任务中的表现。代理式编程指 AI 代理自主规划、编写、测试和修改代码，人工干预极少。Ornith-1.0 结合了这些概念，创建了一个能在编程任务中自举推理链的模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/data-science-in-your-pocket/ornith-1-0-self-learning-llm-for-coding-318c9a830bfc">Ornith 1.0 : Self Learning LLM for Coding | by Mehul Gupta | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases | Google Cloud</a></li>

</ul>
</details>

**标签**: `#LLM`, `#open-source`, `#coding`, `#agentic`, `#deep-reinforce`

---

<a id="item-10"></a>
## [比亚迪自研智驾芯片璇玑 A3 预计 2027 年首搭](https://36kr.com/newsflashes/3874197541344262?f=rss) ⭐️ 8.0/10

比亚迪宣布其自研智驾芯片璇玑 A3 将于 2027 年在腾势量产车上首次搭载。该芯片采用 4nm 工艺，单颗算力超 700 TOPS，三颗协同总算力超 2100 TOPS。 这标志着国产芯片在高端自动驾驶领域取得重大突破，比亚迪加入英伟达等巨头行列。此举有望降低对外国供应商的依赖，并加速 L3/L4 自动驾驶在大众市场车型中的普及。 该芯片支持 L3 和 L4 自动驾驶，并已开始量产。比亚迪称，璇玑 A3 单位算力功耗较同级产品低 20%，结合自研算法优化后，算力利用率提升 100%。

rss · 36氪 · 6月29日 11:57

**背景**: 自动驾驶芯片如英伟达 Orin X 通常提供 254 TOPS 用于 L3 系统，而比亚迪 A3 单颗算力超 700 TOPS。4nm 工艺目前是半导体行业最先进工艺之一，此前主要由台积电等公司主导。比亚迪自主研发芯片反映了车企垂直整合以掌控关键部件的广泛趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.sina.com.cn/cj/2026-06-01/doc-inhzwckt8538724.shtml">24年半导体长跑：深度解析 比 亚 迪 璇 玑 A 3 与全产业链布局__财经头条</a></li>
<li><a href="https://laoyaoba.com/n/1043032">比 亚 迪 发布中国首款4nm智驾 芯 片 璇 玑 A 3 ，官宣为城市领航安全兜底</a></li>
<li><a href="http://www.smahz.com/612/2060007304748597248.htm">补齐智驾核心短板， 比 亚 迪 发布国产首款4nm...</a></li>

</ul>
</details>

**标签**: `#自动驾驶`, `#芯片`, `#比亚迪`, `#电动汽车`, `#智能驾驶`

---

<a id="item-11"></a>
## [EML 树被证明是通用逼近器](https://www.reddit.com/r/MachineLearning/comments/1uipl1t/eml_trees_are_universal_approximators_r/) ⭐️ 8.0/10

研究人员证明了 EML 树（初等函数的组合）是连续函数的通用逼近器，这一结果与神经网络的经典结论相平行。 这一理论结果扩展了已知通用逼近器的架构集合，为超越神经网络的函数逼近提供了新视角，并可能启发新型机器学习模型。 该证明（详细见论文附录）显式构造了二元运算、多项式、双曲正切和近似单位划分的 EML 表示，并将它们用作模块。一个技术难题在于自然对数对非正输入无定义，通过符号分解和仿射映射得到解决。

reddit · r/MachineLearning · /u/JoeGermany · 6月29日 11:16

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Universal_approximation_theorem">Universal approximation theorem</a></li>
<li><a href="https://github.com/Brumbelow/uninum/blob/main/docs/eml_explained.md">uninum/docs/ eml _explained.md at main · Brumbelow/uninum · GitHub</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#approximation theory`, `#universal approximation`, `#EML trees`, `#theoretical result`

---

<a id="item-12"></a>
## [长鑫存储与腾讯签近 30 亿美元 DRAM 供应协议](https://www.reuters.com/world/china/chinas-cxmt-wins-3-billion-memory-supply-deal-with-tencent-sources-say-2026-06-29/) ⭐️ 8.0/10

长鑫存储（CXMT）已与腾讯签署一项价值超 200 亿元人民币（约 29.4 亿美元）的长期 DRAM 内存供应协议，覆盖数年服务器供货。三位知情人士披露了此前未报道的交易，合约期限为 3 至 5 年。 该协议凸显了中国推动半导体自主化的战略意图，可能重塑全球 DRAM 供应链。同时也表明长鑫存储作为重要内存制造商的能力提升，有助于中国科技巨头减少对外国供应商的依赖。 合约期限尚不确定，两位消息人士称三年，另一位称五年。据传长鑫存储还在与其他中国互联网公司谈判，包括阿里云、字节跳动和小米。

telegram · zaihuapd · 6月29日 09:31

**背景**: DRAM（动态随机存取存储器）是一种易失性内存，广泛应用于服务器、个人电脑等设备。长鑫存储（CXMT）是中国领先的 DRAM 制造商，专注于设计、研发和生产。该协议正值全球半导体供应链紧张之际，中国正寻求内存芯片自主可控，尤其在另一中国芯片企业长江存储（YMTC）遭遇挫折之后。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dianzinav.com/sites/3286.html">CXMT ( 长 鑫 存 储 ) - 专注DRAM的设计、研发、生产与销售。 - 电子人导航</a></li>
<li><a href="https://gaohaojun.cn/Blog/2026/01/21/红色内存潮流长鑫存储的战略分析和围绕DRAM的地缘政治斗争/">内 存 的赤色潮流： 长 鑫 存 储 （ CXMT ... - Gao Haojun</a></li>

</ul>
</details>

**标签**: `#DRAM`, `#China`, `#Tencent`, `#semiconductor`, `#supply chain`

---