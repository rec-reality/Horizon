---
layout: default
title: "Horizon Summary: 2026-06-29 (EN)"
date: 2026-06-29
lang: en
---

> From 78 items, 12 important content pieces were selected

---

1. [Supreme Court rules geofence warrants need constitutional protections](#item-1) ⭐️ 9.0/10
2. [Google's AI peer-reviewer processes 10K papers, cuts turnaround to 30 min](#item-2) ⭐️ 9.0/10
3. [vLLM v0.24.0: MiniMax-M3 Support and DeepSeek-V4 Optimizations](#item-3) ⭐️ 8.0/10
4. [Rocket Lab to Acquire Iridium in $8B Deal](#item-4) ⭐️ 8.0/10
5. [WATaBoy: JIT-ing Game Boy to WebAssembly Beats Native Interpreter](#item-5) ⭐️ 8.0/10
6. [What happens when you run a CUDA kernel?](#item-6) ⭐️ 8.0/10
7. [European ISPs Want Rightsholders Accountable for Overblocking Damage](#item-7) ⭐️ 8.0/10
8. [Meta uses Instagram photos in smart glasses ads](#item-8) ⭐️ 8.0/10
9. [Ornith-1.0: Open-weights LLM for agentic coding](#item-9) ⭐️ 8.0/10
10. [BYD's self-driving chip Xuanji A3 to debut in 2027](#item-10) ⭐️ 8.0/10
11. [EML Trees Proven as Universal Approximators](#item-11) ⭐️ 8.0/10
12. [CXMT and Tencent Sign $3 Billion DRAM Supply Deal](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Supreme Court rules geofence warrants need constitutional protections](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

The US Supreme Court ruled that geofence warrants, which allow law enforcement to obtain location data of all mobile devices within a specific area, are subject to Fourth Amendment protections requiring probable cause and particularity. This landmark decision significantly limits warrantless geolocation dragnets, marking a major victory for digital privacy and forcing law enforcement to obtain individualized warrants for such searches. The case originated from a bank robbery investigation where Google's Sensorvault provided location data of 19 devices near the crime scene; the Court rejected the government's argument that users lack a reasonable expectation of privacy in data shared with third parties.

hackernews · cdrnsf · Jun 29, 15:54 · [Discussion](https://news.ycombinator.com/item?id=48720924)

**Background**: A geofence warrant is a type of reverse search warrant that compels tech companies like Google to identify all devices within a virtual geographic boundary. These warrants have been widely used but criticized for enabling suspicionless mass surveillance. The Fourth Amendment protects against unreasonable searches, but courts have debated whether location data voluntarily shared with a third party retains privacy protections.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant</a></li>
<li><a href="https://techcrunch.com/2026/06/29/in-major-privacy-win-supreme-court-rules-geofence-warrants-are-protected-by-privacy-rights/">In major privacy win, Supreme Court rules geofence warrants are ...</a></li>

</ul>
</details>

**Discussion**: Commenters noted the ruling's impact on technologies like Flock cameras and debated the dissent by Justices Alito, Thomas, and Barrett. Some highlighted historical examples of geolocation surveillance, such as the identification of Paula Broadwell, while others expressed cautious optimism about the decision's scope.

**Tags**: `#privacy`, `#supreme court`, `#geofence`, `#fourth amendment`, `#surveillance`

---

<a id="item-2"></a>
## [Google's AI peer-reviewer processes 10K papers, cuts turnaround to 30 min](https://www.reddit.com/r/MachineLearning/comments/1uio9rb/googles_agentic_peerreviewer_handled_10k_papers/) ⭐️ 9.0/10

Google deployed an agentic AI system that reviewed approximately 10,000 papers submitted to ICML and STOC conferences, achieving a 30-minute turnaround time and detecting 34% more mathematical errors than zero-shot prompting. The results are now formally documented in a research paper. This demonstrates the feasibility of AI-assisted peer review at massive scale, potentially transforming the scientific publishing process by reducing reviewer workload and speeding up publication cycles. It sets a precedent for automated quality control in academic conferences. The agentic AI system operates autonomously, using multiple specialized agents to analyze papers for mathematical correctness and clarity. The 34% improvement over zero-shot prompting highlights the advantage of structured agent-based reasoning over direct LLM queries.

reddit · r/MachineLearning · /u/Justgototheeffinmoon · Jun 29, 10:05

**Background**: Agentic AI refers to autonomous AI systems that can pursue goals with limited human supervision, often using multiple specialized agents. Zero-shot prompting is a technique where an LLM is given a task without any examples, relying solely on its pre-trained knowledge. This research applies agentic AI to the peer-review process, a traditionally human-intensive task.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-ai">What is agentic AI? Definition and differentiators | Google Cloud</a></li>
<li><a href="https://aws.amazon.com/what-is/agentic-ai/">What is Agentic AI? - Agentic AI Explained - AWS</a></li>
<li><a href="https://www.linkedin.com/pulse/prompt-engineering-course-essential-few-shot-zero-shot-prompting-3vcnc">Prompt Engineering Course Essential: Few-Shot and Zero - Shot ...</a></li>
<li><a href="https://medium.com/@albert_88839/zero-in-on-the-right-responses-with-zero-shot-and-few-shot-prompting-f50fb154af4d">Zero in on the Right Responses with Zero - Shot and... | Medium</a></li>
<li><a href="https://promplify.ai/blog/zero-shot-prompting/">Zero - Shot Prompting : How to Get Great Results... — Promplify Blog</a></li>

</ul>
</details>

**Tags**: `#AI`, `#peer review`, `#machine learning`, `#scientific review`, `#Google`

---

<a id="item-3"></a>
## [vLLM v0.24.0: MiniMax-M3 Support and DeepSeek-V4 Optimizations](https://github.com/vllm-project/vllm/releases/tag/v0.24.0) ⭐️ 8.0/10

vLLM v0.24.0 has been released, featuring support for the MiniMax-M3 model and significant optimizations for DeepSeek-V4, among many other improvements. The release includes 571 commits from 256 contributors. This release marks a major step forward for vLLM as a high-performance inference engine, enhancing support for cutting-edge models and improving efficiency. The optimizations for DeepSeek-V4 and expansion of Model Runner V2 benefit the entire LLM serving ecosystem. Notable technical additions include MiniMax Sparse Attention (MSA) support with BF16/FP8 indexer and MXFP4, FlashInfer sparse index cache for DeepSeek-V4 (2–4% TTFT improvement), and a new streaming parser engine unifying tool-call/reasoning parsing. The release also integrates DeepEP v2 for expert parallelism and moves device selection out of internal CUDA_VISIBLE_DEVICES management.

github · khluu · Jun 29, 19:41

**Background**: vLLM is an open-source library for fast LLM inference and serving, widely used for its high throughput and flexibility. MiniMax-M3 is a recent multimodal model known for its long-context reasoning, while DeepSeek-V4 is a major language model that benefits from advanced optimization techniques like sparse attention and expert parallelism.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/flashinfer-ai/flashinfer">GitHub - flashinfer-ai/flashinfer: FlashInfer: Kernel Library for LLM Serving · GitHub</a></li>
<li><a href="https://vllm.ai/blog/2026-06-12-minimax-m3-vllm">MiniMax M3 in vLLM: Day-0 Serving for 1M-Token Multimodal Reasoning</a></li>
<li><a href="https://arxiv.org/abs/2501.01005">[2501.01005] FlashInfer: Efficient and Customizable Attention Engine for LLM Inference Serving</a></li>

</ul>
</details>

**Tags**: `#vllm`, `#LLM inference`, `#model optimization`, `#open source`, `#release`

---

<a id="item-4"></a>
## [Rocket Lab to Acquire Iridium in $8B Deal](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-acquire-iridium-historic-deal-creating-fully) ⭐️ 8.0/10

Rocket Lab announced on June 29 that it will acquire Iridium Communications in a cash-and-stock deal valued at approximately $8 billion, with a purchase price of $54 per share. The transaction, approved by both boards, is expected to close by mid-2027, pending regulatory and shareholder approvals. This merger creates a fully integrated space company combining Rocket Lab's launch and spacecraft manufacturing with Iridium's global LEO satellite network, L-band spectrum, and over 500 partners. It enables Rocket Lab to enter satellite IoT, direct-to-device, and PNT services, while securing a baseline of regular launches similar to SpaceX's Starlink strategy. Iridium operates 66 active LEO satellites and reported 2025 revenue of $871.7 million with an EBITDA margin of 57%. Rocket Lab has secured $3.6 billion in bridge loan commitments to finance the acquisition.

hackernews · everfrustrated · Jun 29, 14:09 · [Discussion](https://news.ycombinator.com/item?id=48719485)

**Background**: The Iridium satellite constellation, originally developed by Motorola and becoming operational in 1998, consists of 66 active satellites in low Earth orbit providing global voice and data coverage via L-band and inter-satellite links. It serves over 2.55 million subscribers including satellite phones and IoT devices, and is the only network offering truly global pole-to-pole coverage.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Iridium_satellite_constellation">Iridium satellite constellation</a></li>
<li><a href="https://grokipedia.com/page/Iridium_satellite_constellation">Iridium satellite constellation</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some express concerns about increased space debris and environmental impact, while others highlight the strategic value similar to SpaceX leveraging Starlink for launch demand. One comment notes the shift of Rocket Lab from New Zealand to US corporate identity.

**Tags**: `#space`, `#acquisition`, `#satellite`, `#rocket-lab`, `#iridium`

---

<a id="item-5"></a>
## [WATaBoy: JIT-ing Game Boy to WebAssembly Beats Native Interpreter](https://humphri.es/blog/WATaBoy/) ⭐️ 8.0/10

A blog post by an undergraduate developer details WATaBoy, a Game Boy emulator that dynamically recompiles SM83 instructions to WebAssembly, outperforming a native interpreter on iOS by exploiting the browser's JIT exception. This work demonstrates a clever way to achieve JIT compilation on iOS, where Apple restricts JIT except in browsers, enabling high-performance emulation in a browser environment. WATaBoy uses the browser's WebAssembly JIT to compile hot Game Boy code paths at runtime, achieving performance that beats a native interpreter running on the same device.

hackernews · energeticbark · Jun 29, 15:02 · [Discussion](https://news.ycombinator.com/item?id=48720190)

**Background**: Apple's iOS restrictions prevent apps from performing JIT compilation except for web browsers' JavaScript engines. By targeting WebAssembly, which runs inside the browser's JIT, WATaBoy effectively sidesteps this limitation. Game Boy emulation typically relies on interpreting the SM83 CPU instructions, which is slower than JIT compilation.

<details><summary>References</summary>
<ul>
<li><a href="https://humphri.es/blog/WATaBoy/">WATaBoy: JIT-ing Game Boy Instructions to Wasm Beats a Native Interpreter</a></li>
<li><a href="https://news.ycombinator.com/item?id=48720190">WATaBoy: JIT-Ing Game Boy Instructions to WASM Beats a Native Interpreter | Hacker News</a></li>
<li><a href="https://github.com/EnergeticBark/WATaBoy">GitHub - EnergeticBark/WATaBoy: A Game Boy emulator with an...</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project as impressive for an undergraduate. Some noted that Firefox was 25% slower than Chrome/Safari, sparking curiosity about browser differences. Others highlighted that WASM overhead (~20%) is much smaller than interpreter overhead (~1000%), making the speedup expected but still cool.

**Tags**: `#JIT`, `#WebAssembly`, `#GameBoy emulation`, `#performance`, `#browser tech`

---

<a id="item-6"></a>
## [What happens when you run a CUDA kernel?](https://fergusfinn.com/blog/what-happens-when-you-run-a-gpu-kernel/) ⭐️ 8.0/10

A detailed blog post explaining the full path from a CUDA kernel launch to GPU execution, covering doorbell and QMD mechanisms.

hackernews · mezark · Jun 29, 13:11 · [Discussion](https://news.ycombinator.com/item?id=48718863)

**Tags**: `#CUDA`, `#GPU`, `#kernel launch`, `#NVIDIA`, `#graphics programming`

---

<a id="item-7"></a>
## [European ISPs Want Rightsholders Accountable for Overblocking Damage](https://torrentfreak.com/european-isps-want-rightsholders-held-accountable-for-overblocking-damage/) ⭐️ 8.0/10

European ISPs are pushing to legally hold rightsholders accountable for damages caused by overblocking, where legitimate content is wrongly blocked during copyright enforcement. This policy shift could deter abusive takedown practices and protect internet freedom, affecting the balance between copyright enforcement and free expression across Europe. Overblocking often results from automated content filters or vague court orders that block more material than intended. ISPs argue that rightsholders should bear liability for such overreach.

hackernews · Brajeshwar · Jun 29, 16:07 · [Discussion](https://news.ycombinator.com/item?id=48721072)

**Background**: Overblocking refers to the accidental blocking of legitimate content by internet filters or blocking orders. In Europe, ongoing debates over Article 17 of the EU Copyright Directive have highlighted the problem of automated overblocking. ISPs are now seeking legal recourse to hold rightsholders accountable for damages.

<details><summary>References</summary>
<ul>
<li><a href="https://de.wikipedia.org/wiki/Overblocking">Overblocking – Wikipedia</a></li>
<li><a href="https://www.techdirt.com/tag/overblocking/">Overblocking stories at Techdirt.</a></li>
<li><a href="https://legalblogs.wolterskluwer.com/copyright-blog/youtube-copyright-transparency-report-overblocking-is-real/">YouTube Copyright Transparency Report: Overblocking is real | Kluwer Copyright Blog</a></li>

</ul>
</details>

**Discussion**: Community comments largely support holding rightsholders accountable, with some noting similar issues in the US DMCA system. However, skepticism remains about whether such accountability will actually be implemented, as copyright monopolists often avoid consequences.

**Tags**: `#internet governance`, `#copyright`, `#censorship`, `#ISP`, `#policy`

---

<a id="item-8"></a>
## [Meta uses Instagram photos in smart glasses ads](https://twitter.com/i/status/2071277885646868536) ⭐️ 8.0/10

Meta is incorporating Instagram users' photos into advertisements for its Ray-Ban Meta smart glasses without explicit opt-in, renewing privacy debates. This practice mirrors a similar policy from Facebook in 2013. This move raises significant privacy concerns as it leverages user-generated content without direct consent, potentially eroding trust in Meta's platforms. It also highlights the ongoing tension between monetization strategies and user rights in social media. According to community comments, Meta's terms of service allow use of profile photos in commercial content, a practice that dates back to Facebook's 2013 policy. The Ray-Ban Meta glasses, released in 2023, include a 12MP camera and livestreaming capabilities, but privacy concerns have been raised about the small recording indicator light.

hackernews · notRobot · Jun 29, 13:26 · [Discussion](https://news.ycombinator.com/item?id=48719027)

**Background**: The Ray-Ban Meta smart glasses are a second-generation product jointly developed by Meta and Ray-Ban, featuring improved cameras, audio, and Meta AI integration. Instagram has over a billion monthly active users, making it a rich source of user-generated content for advertising. Meta's use of such content for ads has been a recurring privacy issue since Facebook's early days.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meta_glasses">Meta glasses</a></li>
<li><a href="https://www.yellowhead.com/blog/user-generated-content-ugc-ads/">User Generated Content : Why Brands Love UGC... - yellowHEAD</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration and resignation, noting that this practice has occurred for years under the terms of service. Some highlighted the absurdity of ads using friends' photos, while others advised leaving the platform. A few pointed out the similarity to Meta's use of photos for AI training last year.

**Tags**: `#privacy`, `#meta`, `#instagram`, `#advertising`, `#smartglasses`

---

<a id="item-9"></a>
## [Ornith-1.0: Open-weights LLM for agentic coding](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce released Ornith-1.0, a family of open-weights LLMs (MIT licensed) for agentic coding, achieving state-of-the-art performance on coding benchmarks with sizes up to 397B parameters. This release provides a powerful, permissively licensed coding model that can run agent harnesses autonomously, potentially accelerating AI-assisted software development and reducing reliance on proprietary models. Ornith-1.0 comes in four variants: 9B Dense, 31B Dense, 35B MoE, and 397B MoE, built on top of Gemma 4 (Apache 2.0) and Qwen 3.5 (Apache 2.0). Initial tests with the 35B GGUF quantized model show proficient multi-tool call handling.

rss · Simon Willison · Jun 29, 16:17

**Background**: Self-scaffolding LLMs use reinforcement learning to iteratively generate scaffold code that improves the model's own performance on tasks. Agentic coding refers to AI agents that autonomously plan, write, test, and modify code with minimal human intervention. Ornith-1.0 combines these concepts to create a model that can bootstrap its own reasoning chain during coding tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/data-science-in-your-pocket/ornith-1-0-self-learning-llm-for-coding-318c9a830bfc">Ornith 1.0 : Self Learning LLM for Coding | by Mehul Gupta | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases | Google Cloud</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#open-source`, `#coding`, `#agentic`, `#deep-reinforce`

---

<a id="item-10"></a>
## [BYD's self-driving chip Xuanji A3 to debut in 2027](https://36kr.com/newsflashes/3874197541344262?f=rss) ⭐️ 8.0/10

BYD announced that its self-developed autonomous driving chip, Xuanji A3, will be first used in Denza production vehicles in 2027. The chip uses a 4nm process, delivers over 700 TOPS per chip, and three chips together exceed 2100 TOPS. This marks a significant breakthrough for China's domestic chip industry in high-performance autonomous driving, as BYD joins major players like Nvidia. It could reduce dependence on foreign suppliers and accelerate the adoption of L3/L4 autonomous driving in mass-market vehicles. The chip supports L3 and L4 autonomous driving and has already started mass production. BYD claims the chip's power efficiency per TOPS is 20% lower than competitors, and with self-developed algorithm optimization, computing power utilization is improved by 100%.

rss · 36氪 · Jun 29, 11:57

**Background**: Autonomous driving chips like Nvidia's Orin X typically provide up to 254 TOPS for L3 systems, while BYD's A3 offers over 700 TOPS per chip. The 4nm process is currently among the most advanced in the semiconductor industry, previously dominated by companies like TSMC. BYD's move into self-developed chips reflects a broader trend of automakers vertically integrating to control critical components.

<details><summary>References</summary>
<ul>
<li><a href="https://finance.sina.com.cn/cj/2026-06-01/doc-inhzwckt8538724.shtml">24年半导体长跑：深度解析 比 亚 迪 璇 玑 A 3 与全产业链布局__财经头条</a></li>
<li><a href="https://laoyaoba.com/n/1043032">比 亚 迪 发布中国首款4nm智驾 芯 片 璇 玑 A 3 ，官宣为城市领航安全兜底</a></li>
<li><a href="http://www.smahz.com/612/2060007304748597248.htm">补齐智驾核心短板， 比 亚 迪 发布国产首款4nm...</a></li>

</ul>
</details>

**Tags**: `#自动驾驶`, `#芯片`, `#比亚迪`, `#电动汽车`, `#智能驾驶`

---

<a id="item-11"></a>
## [EML Trees Proven as Universal Approximators](https://www.reddit.com/r/MachineLearning/comments/1uipl1t/eml_trees_are_universal_approximators_r/) ⭐️ 8.0/10

Researchers have proven that EML trees—compositions of elementary functions—are universal approximators for continuous functions, paralleling the classical result for neural networks. This theoretical result expands the set of architectures known to be universal approximators, offering a new perspective on function approximation beyond neural networks and potentially inspiring novel machine learning models. The proof (detailed in the paper's appendix) explicitly constructs EML representations of binary operations, polynomials, hyperbolic tangent, and approximate partitions of unity, using them as building blocks. A technical challenge arises from the natural logarithm's undefinedness for nonpositive inputs, handled via sign-based decompositions and affine maps.

reddit · r/MachineLearning · /u/JoeGermany · Jun 29, 11:16

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Universal_approximation_theorem">Universal approximation theorem</a></li>
<li><a href="https://github.com/Brumbelow/uninum/blob/main/docs/eml_explained.md">uninum/docs/ eml _explained.md at main · Brumbelow/uninum · GitHub</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#approximation theory`, `#universal approximation`, `#EML trees`, `#theoretical result`

---

<a id="item-12"></a>
## [CXMT and Tencent Sign $3 Billion DRAM Supply Deal](https://www.reuters.com/world/china/chinas-cxmt-wins-3-billion-memory-supply-deal-with-tencent-sources-say-2026-06-29/) ⭐️ 8.0/10

China's CXMT has signed a long-term DRAM supply agreement with Tencent valued at over 200 billion RMB (approximately $29.4 billion), covering server memory for several years. The previously unreported deal, disclosed by three sources, has a duration of 3 to 5 years. This deal highlights China's strategic push toward semiconductor self-sufficiency, potentially reshaping global DRAM supply chains. It also demonstrates CXMT's growing capability as a major memory manufacturer, which may reduce dependence on foreign suppliers for Chinese tech giants. The contract length is uncertain, with two sources saying three years and one saying five years. CXMT is also reportedly in talks with other Chinese internet companies such as Alibaba Cloud, ByteDance, and Xiaomi for similar supply deals.

telegram · zaihuapd · Jun 29, 09:31

**Background**: DRAM (Dynamic Random Access Memory) is a type of volatile memory used in servers, PCs, and other devices. CXMT (ChangXin Memory Technologies) is a leading Chinese DRAM manufacturer focused on design, R&D, and production. This deal comes amid global semiconductor supply chain tensions, with China seeking self-reliance in memory chips, especially after setbacks faced by other Chinese chip firms like YMTC.

<details><summary>References</summary>
<ul>
<li><a href="https://www.dianzinav.com/sites/3286.html">CXMT ( 长 鑫 存 储 ) - 专注DRAM的设计、研发、生产与销售。 - 电子人导航</a></li>
<li><a href="https://gaohaojun.cn/Blog/2026/01/21/红色内存潮流长鑫存储的战略分析和围绕DRAM的地缘政治斗争/">内 存 的赤色潮流： 长 鑫 存 储 （ CXMT ... - Gao Haojun</a></li>

</ul>
</details>

**Tags**: `#DRAM`, `#China`, `#Tencent`, `#semiconductor`, `#supply chain`

---