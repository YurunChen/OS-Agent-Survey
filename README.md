<h1 align="center">
<img src="image/title_log_v3.jpg" width="100" alt="ToRA" />
<br>
OS Agents: A Survey on MLLM-based Agents <br>for General Computing Devices Use
</h1>




<p align="center">
  <a href="https://os-agent-survey.github.io/"><b>[🌐 Website]</b></a> •
  <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey/blob/main/paper.pdf"><b>[📜 Paper]</b></a> •
  <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey/tree/main"><b>[🐱 GitHub]</b></a>
  <!-- <a href="https://9557c5365a6f44dc84.gradio.live"><b>[🐯 Gradio Demo]</b></a> -->
  <br>
  <!-- <a href="#-quick-start">Quick Start</a> • -->
  <!-- <a href="#%EF%B8%8F-citation">Citation</a> -->
</p>
 <!--
> [!CAUTION]
> This paper was **rejected by arXiv** with so-called **"Our moderators determined that your submission does not contain sufficient original or substantive scholarly research and is not of interest to arXiv"**. We attempted an **appeal**, but received the exact same rejection response as the initial submission, with **no further explanation** provided. The **resubmission** also proved **ineffective**. As a result, the only way to access it at the moment is through **this GitHub repository**. 
-->

This is the repo for [OS Agents: A Survey on MLLM-based Agents for General Computing Devices Use](https://github.com/OS-Agent-Survey/OS-Agent-Survey/blob/main/paper.pdf). The survey is aimed to consolidates the state of OS Agents research, providing insights to guide both academic inquiry and industrial development. In this repository, we have listed relevant papers related to our work in four areas: Foundation Models, Agent Frameworks, Evaluation & Benchmarks, and Safety & Privacy and this collection will be continuously updated. We aim to provide you with comprehensive knowledge in the OS Agent field, hoping it can help you quickly familiarize yourself with this research direction.

## ❗Why is there no arXiv link for this paper?

This paper was **rejected by arXiv** with the justification: "Our moderators determined that your submission **does not contain sufficient original or substantive scholarly research and is not of interest to arXiv**." This reasoning appears to be **inconsistent with the content and contribution of the paper**. We attempted an **appeal**, but unfortunately, this was unsuccessful, and **no further explanation was provided**. A resubmission did not resolve the issue either. As a result, the ONLY way to access the paper at the moment is through our [GitHub repository](https://github.com/OS-Agent-Survey/OS-Agent-Survey). We are disappointed by the lack of transparency in arXiv’s moderation process.

## 🔔We are hiring!

(Information will be continuously updated, please stay tuned.)

### [[OPPO](https://www.oppo.com/)] Personal AI Team Hiring Algorithm Interns / New Graduates / Experienced Candidates

[OPPO](https://www.oppo.com/) is dedicated to developing the most advanced foundation model technologies and creating personalized user experiences. Our mission is focused on developing revolutionary **AI Native Phones** that will shape the future. The Personal AI Team is primarily focused on cutting-edge research in (multimodal) LLMs, AI Agents and personalization. The team leverages OPPO’s ample platform resources, including data and computing power, to continuously invest in these key areas. We are currently hiring algorithm interns, new graduates, and experienced candidates. We expect you to be proficient in algorithms or engineering of large foundation models. If interested, please contact via email: zhouwangchunshu@oppo.com.

### [[01.AI](https://www.01.ai/)] Foundation Model Post-training Team Hiring Algorithm Interns / New Graduates / Experienced Candidates

[01.AI](https://www.01.ai/) is a global leader in technology and applications of large foundation models. Its latest flagship model, [Yi-Lightning](https://arxiv.org/abs/2412.01253), **ranked #1 in China** and **#6 globally** in the [LMSys Chatbot Arena](https://lmarena.ai/?leaderboard) updated on October 14, 2024. The post-training team is responsible for cutting-edge research and engineering of post-training techniques for foundation models. We are currently hiring algorithm interns, new graduates, and experienced candidates. We expect you to be proficient in algorithms or engineering of large foundation models.
If interested, please contact via email: huxueyu.zju@gmail.com.

## Table of Contents
- [Overview of OS Agent Survey](#overview-of-os-agent-survey)
- [Tables](#tables)
- [Full List](#full-list)
  - [Foundation Models](#foundation-models)
  - [Agent Frameworks](#agent-frameworks)
  - [Evaluation & Benchmark](#evaluation--benchmark)
  - [Safety & Privacy](#safety--privacy)
- [Useful Links](#useful-links)
- [Contact](#contact)
- [Citation](#citation)

## Overview of OS Agent Survey
<!--
This survey aims to make contributions to the research and development of OS Agents by providing readers with a comprehensive understanding of their essential capabilities, offering insights into methodologies for building OS Agents based on (M)LLMs, and highlighting the latest research trends, challenges and future in this field. Recognizing that OS Agents are still in their early stages of development, we acknowledge the rapid advancements that continue to introduce novel methodologies and applications. Through this work, we aspire to inspire further innovation, driving progress in both academic research and industrial applications of OS Agents.
-->
This survey aims to advance the research and development of OS Agents by providing a detailed exploration of their fundamental capabilities, methodologies for building them using (M)LLMs, and emerging trends in the field. While OS Agents are still in the early stages of growth, the rapid evolution of technology continues to introduce innovative approaches and applications. This work seeks to highlight ongoing challenges, future opportunities, and the latest developments, encouraging further research and industrial adoption. Ultimately, we hope this study will serve as a catalyst for innovation, driving meaningful progress in both academia and industry.

<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="image/survey_overview_2.jpg">



## Tables

**Table 1:** Recent foundation models for OS Agents. Arch.: Architecture, Exist.: Existing, Mod.: Modified, Concat.: Concatenated, PT: Pre-Train, SFT: Supervised Fine-Tune, RL: Reinforcement Learning.

| Paper                                                                                                         | Model               | Arch.         | PT   | SFT   | RL   | Date    | Link                                                        |
|:--------------------------------------------------------------------------------------------------------------|:--------------------|:--------------|:-----|:------|:-----|:--------|:------------------------------------------------------------|
| OS-ATLAS: A Foundation Action Model for Generalist GUI Agents                                                 | OS-Atlas            | Exist. MLLMs  | √    | √     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.23218)]                 |
| AutoGLM: Autonomous Foundation Agents for GUIs                                                                | AutoGLM             | Exist. LLMs   | √    | √     | √    | 10/2024 | [[paper](https://arxiv.org/abs/2411.00820)]                 |
| EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data                      | EDGE                | Exist. MLLMs  | -    | √     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.19461)]                 |
| Ferret-UI 2: Mastering Universal User Interface Understanding Across Platforms                                | Ferret-UI 2         | Exist. MLLMs  | -    | √     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.18967)]                 |
| ShowUI: One Vision-Language-Action Model for Generalist GUI Agent                                             | ShowUI              | Exist. MLLMs  | √    | √     | -    | 10/2024 | [[paper](https://openreview.net/forum?id=UXdxYnkJtX)]       |
| Harnessing Webpage UIs for Text-Rich Visual Understanding                                                     | UIX                 | Exist. MLLMs  | -    | √     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.13824)]                 |
| TinyClick: Single-Turn Agent for Empowering GUI Automation                                                    | TinyClick           | Exist. MLLMs  | √    | -     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.11871)]                 |
| Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents                          | UGround             | Exist. MLLMs  | -    | √     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.05243)]                 |
| NNetscape Navigator: Complex Demonstrations for Web Agents Without a Demonstrator                             | NNetNav             | Exist. LLMs   | -    | √     | -    | 10/2024 | [[paper](https://arxiv.org/abs/2410.02907)]                 |
| Synatra: Turning indirect knowledge into direct demonstrations for digital agents at scale                    | Synatra             | Exist. LLMs   | -    | √     | -    | 09/2024 | [[paper](https://arxiv.org/abs/2409.15637)]                 |
| MobileVLM: A Vision-Language Model for Better Intra- and Inter-UI Understanding                               | MobileVLM           | Exist. MLLMs  | √    | √     | -    | 09/2024 | [[paper](https://arxiv.org/abs/2409.14818)]                 |
| UI-Hawk: Unleashing the screen stream understanding for gui agents                                            | UI-Hawk             | Mod. MLLMs    | √    | √     | -    | 08/2024 | [[paper](https://www.preprints.org/manuscript/202408.2137)] |
| GUI Action Narrator: Where and When Did That Action Take Place?                                               | GUI Action Narrator | Exist. MLLMs  | -    | √     | -    | 07/2024 | [[paper](https://arxiv.org/abs/2406.13719)]                 |
| MobileFlow: A Multimodal LLM for Mobile GUI Agent                                                             | MobileFlow          | Mod. MLLMs    | √    | √     | -    | 07/2024 | [[paper](https://arxiv.org/abs/2407.04346)]                 |
| VGA: Vision GUI Assistant - Minimizing Hallucinations through Image-Centric Fine-Tuning                       | VGA                 | Exist. MLLMs  | -    | √     | -    | 06/2024 | [[paper](https://arxiv.org/abs/2406.14056)]                 |
| GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices                           | OdysseyAgent        | Exist. MLLMs  | -    | √     | -    | 06/2024 | [[paper](https://arxiv.org/abs/2406.08451)]                 |
| Tell Me What's Next: Textual Foresight for Generic UI Representations                                         | Textual Foresight   | Concat. MLLMs | √    | √     | -    | 06/2024 | [[paper](https://arxiv.org/abs/2406.07822)]                 |
| Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning | WebAI               | Concat. MLLMs | -    | √     | √    | 05/2024 | [[paper](https://arxiv.org/abs/2405.00516)]                 |
| Search Beyond Queries: Training Smaller Language Models for Web Interactions via Reinforcement Learning       | GLAINTEL            | Exist. LLMs   | -    | -     | √    | 04/2024 | [[paper](https://arxiv.org/abs/2404.10887)]                 |
| Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs                                              | Ferret-UI           | Exist. MLLMs  | -    | √     | -    | 04/2024 | [[paper](https://arxiv.org/abs/2404.05719)]                 |
| AutoWebGLM: A Large Language Model-based Web Navigating Agent                                                 | AutoWebGLM          | Exist. LLMs   | -    | √     | √    | 04/2024 | [[paper](https://arxiv.org/abs/2404.03648)]                 |
| Large Language Models Can Self-Improve At Web Agent Tasks                                                     | -                   | Exist. LLMs   | -    | √     | -    | 03/2024 | [[paper](https://arxiv.org/abs/2405.20309v2)]               |
| ScreenAI: A Vision-Language Model for UI and Infographics Understanding                                       | ScreenAI            | Exist. MLLMs  | √    | √     | -    | 02/2024 | [[paper](https://arxiv.org/abs/2402.04615)]                 |
| Dual-View Visual Contextualization for Web Navigation                                                         | Dual-VCR            | Concat MLLMs  | -    | √     | -    | 02/2024 | [[paper](https://arxiv.org/abs/2402.04476)]                 |
| SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents                                             | SeeClick            | Exist. MLLMs  | √    | √     | -    | 01/2024 | [[paper](https://arxiv.org/abs/2401.10935)]                 |
| CogAgent: A Visual Language Model for GUI Agents                                                              | CogAgent            | Mod. MLLMs    | √    | √     | -    | 12/2023 | [[paper](https://arxiv.org/abs/2312.08914)]                 |
| ILuvUI: Instruction-tuned Language-Vision modeling of UIs from Machine Conversations                          | ILuvUI              | Mod. MLLMs    | -    | √     | -    | 10/2023 | [[paper](https://arxiv.org/abs/2310.04869)]                 |
| Reinforced UI Instruction Grounding: Towards a Generic UI Task Automation API                                 | RUIG                | Concat. MLLMs | -    | -     | √    | 10/2023 | [[paper](https://arxiv.org/abs/2310.04716)]                 |
| A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis                        | WebAgent            | Concat. MLLMs | √    | √     | -    | 07/2023 | [[paper](https://arxiv.org/abs/2307.12856)]                 |
| Multimodal Web Navigation with Instruction-Finetuned Foundation Models                                        | WebGUM              | Concat. MLLMs | -    | √     | -    | 05/2023 | [[paper](https://arxiv.org/abs/2305.11854)]                 |


**Table 2:** Recent agent frameworks for OS Agents. TD: Textual Description, GS: GUI Screenshots, VG: Visual Grounding, SG: Semantic Grounding, DG: Dual Grounding, GL: Global, IT: Iterative, AE: Automated Exploration, EA: Experience-Augmented, MA: Management, IO: Input Operations, NO: Navigation Operations, EO: Extended Operations.

| Paper                                                                                                                 | Model          | Perception   | Planning   | Memory   | Action    | Date    | Link                                                   |
|:----------------------------------------------------------------------------------------------------------------------|:---------------|:-------------|:-----------|:---------|:----------|:--------|:-------------------------------------------------------|
| OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization        | OpenWebVoyager | GS,SG        | -          | -        | IO,NO     | 10/2024 | [[paper](https://arxiv.org/abs/2410.19609)]            |
| OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning                                             | OSCAR          | GS,DG        | IT         | AE       | EO        | 10/2024 | [[paper](https://arxiv.org/abs/2410.18963)]            |
| Large Language Models Empowered Personalized Web Agents                                                               | PUMA           | TD           | -          | -        | IO,NO,EO  | 10/2024 | [[paper](https://arxiv.org/abs/2410.17236)]            |
| AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents                                                     | AgentOccam     | TD           | IT         | MA       | IO,NO     | 10/2024 | [[paper](https://arxiv.org/abs/2410.13825)]            |
| Agent S: An Open Agentic Framework that Uses Computers Like a Human                                                   | Agent S        | GS,SG        | GL         | EA,AE,MA | IO,NO     | 10/2024 | [[paper](https://arxiv.org/abs/2410.08164)]            |
| ClickAgent: Enhancing UI Location Capabilities of Autonomous Agents                                                   | ClickAgent     | GS           | IT         | AE       | IO,NO     | 10/2024 | [[paper](https://arxiv.org/abs/2410.11872)]            |
| From Commands to Prompts: LLM-based Semantic File System for AIOS                                                     | LSFS           | GS,SG        | -          | -        | EO        | 09/2024 | [[paper](https://arxiv.org/abs/2410.11843)]            |
| NaviQAte: Functionality-Guided Web Application Navigation                                                             | NaviQate       | GS,SG        | -          | -        | IO        | 09/2024 | [[paper](https://arxiv.org/abs/2409.10741)]            |
| PeriGuru: A Peripheral Robotic Mobile App Operation Assistant based on GUI Image Understanding and Prompting with LLM | PeriGuru       | GS,DG        | IT         | EA,AE    | IO,NO     | 09/2024 | [[paper](https://arxiv.org/abs/2409.09354)]            |
| OpenWebAgent: An Open Toolkit to Enable Web Agents on Large Language Models                                           | OpenWebAgent   | GS,DG        | -          | -        | IO        | 08/2024 | [[paper](https://aclanthology.org/2024.acl-demos.8/)]  |
| Towards LLMCI: Multimodal AI for LLM-Vision UI Operation                                                              | LLMCI          | GS,SG        | -          | -        | EO        | 07/2024 | [[paper](https://doi.org/10.21203/rs.3.rs-4653823/v1)] |
| Agent-e: From autonomous web navigation to foundational design principles in agentic systems                          | Agent-E        | TD           | IT         | AE,MA    | IO,NO     | 07/2024 | [[paper](https://arxiv.org/abs/2407.13032)]            |
| Cradle: Empowering Foundation Agents Towards General Computer Control                                                 | Cradle         | GS           | IT         | EA,AE,MA | EO        | 03/2024 | [[paper](https://arxiv.org/abs/2403.03186v3)]          |
| Android in the zoo: Chain-of-action-thought for gui agents                                                            | CoAT           | GS           | IT         | -        | IO,NO     | 03/2024 | [[paper](https://arxiv.org/abs/2403.02713)]            |
| On the Multi-turn Instruction Following for Conversational Web Agents                                                 | Self-MAP       | -            | IT         | EA       | IO        | 02/2024 | [[paper](https://arxiv.org/abs/2402.15057)]            |
| OS-Copilot: Towards Generalist Computer Agents with Self-Improvement                                                  | OS-Copilot     | TD           | GL         | EA,AE    | IO,EO     | 02/2024 | [[paper](https://arxiv.org/abs/2402.07456)]            |
| Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception                                       | Mobile-Agent   | GS,SG        | IT         | AE       | IO,NO     | 01/2024 | [[paper](https://arxiv.org/abs/2401.16158)]            |
| WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models                                             | WebVoyager     | GS,VG        | IT         | MA       | IO,NO     | 01/2024 | [[paper](https://arxiv.org/abs/2401.13919)]            |
| MobileAgent: enhancing mobile control via human-machine interaction and SOP integration                               | AIA            | GS,VG        | GL         | -        | IO,NO     | 01/2024 | [[paper](https://arxiv.org/abs/2401.04124)]            |
| GPT-4V(ision) is a Generalist Web Agent, if Grounded                                                                  | SeeAct         | GS,SG        | -          | AE       | IO        | 01/2024 | [[paper](https://arxiv.org/abs/2401.01614)]            |
| AppAgent: Multimodal Agents as Smartphone Users                                                                       | AppAgent       | GS,DG        | IT         | AE       | IO,NO     | 12/2023 | [[paper](https://arxiv.org/abs/2312.13771)]            |
| Assistgui: Task-oriented desktop graphical user interface automation                                                  | ACE            | TD           | GL         | AE       | IO,NO     | 12/2023 | [[paper](https://arxiv.org/abs/2312.13108)]            |
| MobileGPT: Augmenting LLM with Human-like App Memory for Mobile Task Automation                                       | MobileGPT      | TD           | GL         | MA       | IO,NO     | 12/2023 | [[paper](https://arxiv.org/abs/2312.03003v3)]          |
| GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation                                 | MM-Navigator   | GS,VG        | -          | MA       | IO,NO     | 11/2023 | [[paper](https://arxiv.org/abs/2311.07562)]            |
| WebWISE: Web Interface Control and Sequential Exploration with Large Language Models                                  | WebWise        | TD           | -          | MA       | IO,NO     | 10/2023 | [[paper](https://arxiv.org/abs/2310.16042)]            |
| A Zero-Shot Language Agent for Computer Control with Structured Reflection                                            | -              | TD           | IT         | AE       | IO,NO     | 10/2023 | [[paper](https://arxiv.org/abs/2310.08740)]            |
| Laser: Llm agent with state-space exploration for web navigation                                                      | Laser          | TD           | IT         | AE       | IO,NO     | 09/2023 | [[paper](https://arxiv.org/abs/2309.08172)]            |
| Synapse: Trajectory-as-Exemplar Prompting with Memory for Computer Control                                            | Synapse        | -            | -          | MA       | IO        | 06/2023 | [[paper](https://arxiv.org/abs/2306.07863)]            |
| Sheetcopilot: Bringing software productivity to the next level through large language models                          | SheetCopilot   | TD           | IT         | AE       | EO        | 05/2023 | [[paper](https://arxiv.org/abs/2305.19308)]            |
| Language Models can Solve Computer Tasks                                                                              | RCI            | -            | IT         | AE       | IO,NO     | 03/2023 | [[paper](https://arxiv.org/abs/2303.17491)]            |
| Enabling conversational interaction with mobile ui using large language models                                        | -              | TD           | -          | -        | IO        | 09/2022 | [[paper](https://arxiv.org/abs/2209.08655)]            |

**Table 3:** Recent benchmarks for OS Agents. We divided the Benchmarks into three sections based on the Platform and sorted them by release date. The following is an explanation of the abbreviations. BS: Benchmark Settings, M/P: Mobile, PC: Desktop, IT: Interactive, ST: Static, OET: Operation Environment Types, RW: Real-World, SM:Simulated, GG: GUI Grounding, IF: Information Processing, AT:Agentic, CG: Code Generation.

| Paper                                                                                                     | Benchmark         | Platform   | BS   | OET   | Task   | Date    | Link                                                      |
|:----------------------------------------------------------------------------------------------------------|:------------------|:-----------|:-----|:------|:-------|:--------|:----------------------------------------------------------|
| On the effects of data scale on computer control agents                                                   | AndroidControl    | M/P        | ST   | -     | AT     | 06/2024 | [[paper](https://arxiv.org/abs/2406.03679)]               |
| AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents                                    | AndroidWorld      | M/P        | IT   | RW    | AT     | 05/2024 | [[paper](https://arxiv.org/abs/2405.14573)]               |
| Latent state estimation helps ui agents to reason                                                         | Android-50 (A-50) | M/P        | IT   | RW    | AT     | 05/2024 | [[paper](https://arxiv.org/abs/2405.11120)]               |
| Benchmarking mobile device control agents across diverse configurations                                   | B-MoCA            | M/P        | IT   | RW    | AT     | 04/2024 | [[paper](https://arxiv.org/abs/2404.16660)]               |
| Llamatouch: A faithful and scalable testbed for mobile ui task automation                                 | LlamaTouch        | M/P        | IT   | RW    | AT     | 04/2024 | [[paper](https://arxiv.org/abs/2404.16054)]               |
| Understanding the weakness of large language model agents within a complex android environment            | AndroidArena      | M/P        | IT   | RW    | AT     | 02/2024 | [[paper](https://arxiv.org/abs/2402.06596)]               |
| Android in the wild: A large-scale dataset for android device control                                     | AITW              | M/P        | ST   | -     | AT     | 07/2023 | [[paper](https://arxiv.org/abs/2307.10088)]               |
| Ugif: Ui grounded instruction following                                                                   | UGIF-DataSet      | M/P        | ST   | -     | AT     | 11/2022 | [[paper](https://arxiv.org/abs/2211.07615)]               |
| A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility                     | MoTIF             | M/P        | ST   | -     | AT     | 02/2022 | [[paper](https://arxiv.org/abs/2202.02312)]               |
| Mapping natural language instructions to mobile UI action sequences                                       | PIXELHELP         | M/P        | IT   | RW    | GG     | 05/2020 | [[paper](https://arxiv.org/abs/2005.03776)]               |
| Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale                                            | WindowsAgentArena | PC         | IT   | RW    | AT     | 09/2024 | [[paper](https://arxiv.org/abs/2409.08264)]               |
| OfficeBench: Benchmarking Language Agents across Multiple Applications for Office Automation              | OfficeBench       | PC         | IT   | RW    | AT     | 07/2024 | [[paper](https://arxiv.org/abs/2407.19056)]               |
| OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments                | OSWorld           | PC         | IT   | RW    | AT     | 04/2024 | [[paper](https://arxiv.org/abs/2404.07972)]               |
| Omniact: A dataset and benchmark for enabling multimodal generalist autonomous agents for desktop and web | OmniACT           | PC         | ST   | -     | GG     | 02/2024 | [[paper](https://arxiv.org/abs/2402.17553)]               |
| ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation                                      | ASSISTGUI         | PC         | IT   | RW    | AT     | 12/2023 | [[paper](https://arxiv.org/abs/2312.13108)]               |
| WebCanvas: Benchmarking Web Agents in Online Environments                                                 | Mind2Web-Live     | Web        | IT   | RW    | IF,AT  | 06/2024 | [[paper](https://arxiv.org/abs/2406.12373)]               |
| MMInA: Benchmarking multihop multimodal internet agents                                                   | MMInA             | Web        | IT   | RW    | IF,AT  | 04/2024 | [[paper](https://arxiv.org/abs/2404.09992)]               |
| AgentStudio: A Toolkit for Building General Virtual Agents                                                | GroundUI          | Web        | ST   | -     | GG     | 03/2024 | [[paper](https://arxiv.org/abs/2403.17918)]               |
| Tur[k]ingBench: A Challenge Benchmark for Web Agents                                                      | TurkingBench      | Web        | IT   | RW    | AT     | 03/2024 | [[paper](https://arxiv.org/abs/2403.11905)]               |
| Workarena: How capable are web agents at solving common knowledge work tasks?                             | WorkArena         | Web        | IT   | RW    | IF,AT  | 03/2024 | [[paper](https://arxiv.org/abs/2403.07718)]               |
| WebLINX: Real-World website navigation with Multi-Turn dialogue                                           | WebLINX           | Web        | ST   | -     | IF,AT  | 02/2024 | [[paper](https://arxiv.org/abs/2402.05930)]               |
| Visualwebarena: Evaluating multimodal agents on realistic visual web tasks                                | Visualwebarena    | Web        | IT   | RW    | GG,AT  | 01/2024 | [[paper](https://arxiv.org/abs/2401.13649)]               |
| WebVLN: Vision-and-Language Navigation on Websites                                                        | WebVLN-v1         | Web        | IT   | RW    | IF,AT  | 12/2023 | [[paper](https://arxiv.org/abs/2312.15820)]               |
| Webarena: A realistic web environment for building autonomous agents                                      | WebArena          | Web        | IT   | RW    | AT     | 07/2023 | [[paper](https://arxiv.org/abs/2307.13854)]               |
| Mind2Web: Towards a Generalist Agent for the Web                                                          | Mind2Web          | Web        | ST   | -     | IF,AT  | 06/2023 | [[paper](https://arxiv.org/abs/2306.06070)]               |
| Webshop: Towards scalable real-world web interaction with grounded language agents                        | WebShop           | Web        | ST   | -     | AT     | 07/2022 | [[paper](https://arxiv.org/abs/2207.01206)]               |
| Mapping natural language commands to web elements                                                         | PhraseNode        | Web        | ST   | -     | GG     | 08/2018 | [[paper](https://arxiv.org/abs/1808.09132)]               |
| World of bits: An open-domain platform for web-based agents                                               | MiniWoB           | Web        | ST   | -     | AT     | 08/2017 | [[paper](https://dl.acm.org/doi/10.5555/3305890.3306005)] |
| World of bits: An open-domain platform for web-based agents                                               | FormWoB           | Web        | IT   | SM    | AT     | 08/2017 | [[paper](https://dl.acm.org/doi/10.5555/3305890.3306005)] |

## Full List

### Foundation Models

1. [2024/10/31] AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents. [[paper](https://arxiv.org/abs/2410.24024)]
2. [2024/10/30] OS-ATLAS: A Foundation Action Model for Generalist GUI Agents. [[paper](https://arxiv.org/abs/2410.23218)]
3. [2024/10/28] AutoGLM: Autonomous Foundation Agents for GUIs. [[paper](https://arxiv.org/abs/2411.00820)]
4. [2024/10/25] EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data. [[paper](https://arxiv.org/abs/2410.19461)]
5. [2024/10/24] Ferret-UI One: Mastering Universal User Interface Understanding Across Platforms. [[paper](https://arxiv.org/abs/2410.18967)]
6. [2024/10/22] ShowUI: One Vision-Language-Action Model for Generalist GUI Agent. [[paper](https://openreview.net/forum?id=UXdxYnkJtX)]
7. [2024/10/17] Harnessing Webpage UIs for Text-Rich Visual Understanding. [[paper](https://arxiv.org/abs/2410.13824)]
8. [2024/10/09] TinyClick: Single-Turn Agent for Empowering GUI Automation. [[paper](https://arxiv.org/abs/2410.11871)]
9. [2024/10/07] Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents. [[paper](https://arxiv.org/abs/2410.05243)]
10. [2024/10/03] NNetscape Navigator: Complex Demonstrations for Web Agents Without a Demonstrator. [[paper](https://arxiv.org/abs/2410.02907)]
11. [2024/09/30] MM1.5: Methods, Analysis & Insights from Multimodal LLM Fine-tuning. [[paper](https://arxiv.org/abs/2409.20566)]
12. [2024/09/24] Synatra: Turning indirect knowledge into direct demonstrations for digital agents at scale. [[paper](https://arxiv.org/abs/2409.15637)]
13. [2024/09/23] MobileVLM: A Vision-Language Model for Better Intra- and Inter-UI Understanding. [[paper](https://arxiv.org/abs/2409.14818)]
14. [2024/09/22] MobileViews: A Large-Scale Mobile GUI Dataset. [[paper](https://arxiv.org/abs/2409.14337)]
15. [2024/08/30] UI-Hawk: Unleashing the screen stream understanding for gui agents. [[paper](https://www.preprints.org/manuscript/202408.2137)]
16. [2024/07/19] GUI Action Narrator: Where and When Did That Action Take Place? [[paper](https://arxiv.org/abs/2406.13719)]
17. [2024/07/05] MobileFlow: A Multimodal LLM for Mobile GUI Agent. [[paper](https://arxiv.org/abs/2407.04346)]
18. [2024/06/20] VGA: Vision GUI Assistant - Minimizing Hallucinations through Image-Centric Fine-Tuning. [[paper](https://arxiv.org/abs/2406.14056)]
19. [2024/06/12] GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices. [[paper](https://arxiv.org/abs/2406.08451)]
20. [2024/06/12] Tell Me What's Next: Textual Foresight for Generic UI Representations. [[paper](https://arxiv.org/abs/2406.07822)]
21. [2024/05/08] Visual Grounding for User Interfaces. [[paper](https://aclanthology.org/2024.naacl-industry.9/)]
22. [2024/05/05] Visual grounding for desktop graphical user interfaces. [[paper](https://arxiv.org/abs/2407.01558)]
23. [2024/05/05] Android in the Zoo：Chain-of-Action-Thought for GUI Agents. [[paper](https://arxiv.org/abs/2403.02713)]
24. [2024/05/01] Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning. [[paper](https://arxiv.org/abs/2405.00516)]
25. [2024/04/16] Search Beyond Queries: Training Smaller Language Models for Web Interactions via Reinforcement Learning. [[paper](https://arxiv.org/abs/2404.10887)]
26. [2024/04/12] Training a Vision Language Model as Smartphone Assistant. [[paper](https://arxiv.org/abs/2404.08755)]
27. [2024/04/09] Autonomous Evaluation and Refinement of Web Agents. [[paper](https://arxiv.org/abs/2404.06474)]
28. [2024/04/08] Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs. [[paper](https://arxiv.org/abs/2404.05719)]
29. [2024/04/04] AutoWebGLM: A Large Language Model-based Web Navigating Agent. [[paper](https://arxiv.org/abs/2404.03648)]
30. [2024/04/02] Octopus v2: On-device language model for super agent. [[paper](https://arxiv.org/abs/2404.01744)]
31. [2024/03/30] Large Language Models Can Self-Improve At Web Agent Tasks. [[paper](https://arxiv.org/abs/2405.20309v2)]
32. [2024/02/08] WebLINX: Real-World website navigation with Multi-Turn dialogue. [[paper](https://arxiv.org/abs/2402.05930)]
33. [2024/02/07] ScreenAI: A Vision-Language Model for UI and Infographics Understanding. [[paper](https://arxiv.org/abs/2402.04615)]
34. [2024/02/06] Dual-View Visual Contextualization for Web Navigation. [[paper](https://arxiv.org/abs/2402.04476)]
35. [2024/01/20] E-ANT: A Large-Scale Dataset for Efficient Automatic GUI NavigaTion. [[paper](https://arxiv.org/abs/2406.14250)]
36. [2024/01/17] SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents. [[paper](https://arxiv.org/abs/2401.10935)]
37. [2024/01/17] GUICourse: From General Vision Language Models to Versatile GUI Agents. [[paper](https://arxiv.org/abs/2406.11317)]
38. [2023/12/25] WebVLN: Vision-and-Language Navigation on Websites. [[paper](https://arxiv.org/abs/2312.15820)]
39. [2023/12/25] UINav: A Practical Approach to Train On-Device Automation Agents. [[paper](https://aclanthology.org/2024.naacl-industry.4/)]
40. [2023/12/14] CogAgent: A Visual Language Model for GUI Agents. [[paper](https://arxiv.org/abs/2312.08914)]
41. [2023/12/04] Intelligent Virtual Assistants with LLM-based Process Automation. [[paper](https://arxiv.org/abs/2312.06677)]
42. [2023/11/30] Exposing Limitations of Language Model Agents in Sequential-Task Compositions on the Web. [[paper](https://arxiv.org/abs/2311.18751)]
43. [2023/10/27] Android in the wild: A large-scale dataset for android device control. [[paper](https://arxiv.org/abs/2307.10088)]
44. [2023/10/08] UReader: Universal OCR-free Visually-situated Language Understanding with Multimodal Large Language Model. [[paper](https://arxiv.org/abs/2310.05126)]
45. [2023/10/07] ILuvUI: Instruction-tuned Language-Vision modeling of UIs from Machine Conversations. [[paper](https://arxiv.org/abs/2310.04869)]
46. [2023/10/07] Reinforced UI Instruction Grounding: Towards a Generic UI Task Automation API. [[paper](https://arxiv.org/abs/2310.04716)]
47. [2023/07/24] A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis. [[paper](https://arxiv.org/abs/2307.12856)]
48. [2023/05/31] From pixels to UI actions: Learning to follow instructions via graphical user interfaces. [[paper](https://arxiv.org/abs/2306.00245)]
49. [2023/05/19] Multimodal Web Navigation with Instruction-Finetuned Foundation Models. [[paper](https://arxiv.org/abs/2305.11854)]
50. [2023/01/30] WebUI: A Dataset for Enhancing Visual UI Understanding with Web Semantics. [[paper](https://arxiv.org/abs/2301.13280)]
51. [2023/01/23] Lexi: Self-Supervised Learning of the UI Language. [[paper](https://arxiv.org/abs/2301.10165)]
52. [2022/10/06] Towards Better Semantic Understanding of Mobile Interfaces. [[paper](https://arxiv.org/abs/2210.02663)]
53. [2022/09/29] Spotlight: Mobile UI Understanding using Vision-Language Models with a Focus. [[paper](https://arxiv.org/abs/2209.14927)]
54. [2022/07/04] WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents. [[paper](https://arxiv.org/abs/2207.01206)]
55. [2022/05/23] Meta-gui: Towards multi-modal conversational agents on mobile gui. [[paper](https://arxiv.org/abs/2205.11029)]
56. [2022/02/16] A data-driven approach for learning to control computers. [[paper](https://arxiv.org/abs/2202.08137)]

### Agent Frameworks

1. [2024/11/10] Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents. [[paper](https://arxiv.org/abs/2411.06559)]
2. [2024/11/01] WebOlympus: An Open Platform for Web Agents on Live Websites. [[paper](https://aclanthology.org/2024.emnlp-demo.20/)]
3. [2024/10/29] Auto-Intent: Automated Intent Discovery and Self-Exploration for Large Language Model Web Agents. [[paper](https://arxiv.org/abs/2410.22552)]
4. [2024/10/25] OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization. [[paper](https://arxiv.org/abs/2410.19609)]
5. [2024/10/24] OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning. [[paper](https://arxiv.org/abs/2410.18963)]
6. [2024/10/24] AgentStore: Scalable Integration of Heterogeneous Agents As Specialized Generalist Computer Assistant. [[paper](https://arxiv.org/abs/2410.18603)]
7. [2024/10/24] Infogent: An Agent-Based Framework for Web Information Aggregation. [[paper](https://arxiv.org/abs/2410.19054)]
8. [2024/10/22] Large Language Models Empowered Personalized Web Agents. [[paper](https://arxiv.org/abs/2410.17236)]
9. [2024/10/21] Beyond Browsing: API-Based Web Agents. [[paper](https://arxiv.org/abs/2410.16464)]
10. [2024/10/17] AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents. [[paper](https://arxiv.org/abs/2410.13825)]
11. [2024/10/17] MobA: A Two-Level Agent System for Efficient Mobile Task Automation. [[paper](https://arxiv.org/abs/2410.13757)]
12. [2024/10/11] VisionTasker: Mobile Task Automation Using Vision Based UI Understanding and LLM Task Planning. [[paper](https://dl.acm.org/doi/abs/10.1145/3654777.3676386)]
13. [2024/10/10] Agent S: An Open Agentic Framework that Uses Computers Like a Human. [[paper](https://arxiv.org/abs/2410.08164)]
14. [2024/10/09] ClickAgent: Enhancing UI Location Capabilities of Autonomous Agents. [[paper](https://arxiv.org/abs/2410.11872)]
15. [2024/10/01] Dynamic Planning for LLM-based Graphical User Interface Automation. [[paper](https://arxiv.org/abs/2410.00467)]
16. [2024/10/01] Multimodal Auto Validation For Self-Refinement in Web Agents. [[paper](https://arxiv.org/abs/2410.00689)]
17. [2024/09/25] Turn Every Application into an Agent: Towards Efficient Human-Agent-Computer Interaction with API-First LLM-Based Agents. [[paper](https://arxiv.org/abs/2409.17140)]
18. [2024/09/23] From Commands to Prompts: LLM-based Semantic File System for AIOS. [[paper](https://arxiv.org/abs/2410.11843)]
19. [2024/09/23] Steward: Natural Language Web Automation. [[paper](https://arxiv.org/abs/2409.15441)]
20. [2024/09/16] NaviQAte: Functionality-Guided Web Application Navigation. [[paper](https://arxiv.org/abs/2409.10741)]
21. [2024/09/14] PeriGuru: A Peripheral Robotic Mobile App Operation Assistant based on GUI Image Understanding and Prompting with LLM. [[paper](https://arxiv.org/abs/2409.09354)]
22. [2024/09/12] Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale. [[paper](https://arxiv.org/abs/2409.08264)]
23. [2024/09/11] Agent Workflow Memory. [[paper](https://arxiv.org/abs/2409.07429)]
24. [2024/08/28] Webpilot: A versatile and autonomous multi-agent system for web task execution with strategic exploration. [[paper](https://arxiv.org/abs/2408.15978)]
25. [2024/08/24] AutoWebGLM: A Large Language Model-based Web Navigating Agent. [[paper](https://dl.acm.org/doi/abs/10.1145/3637528.3671620)]
26. [2024/08/24] Intelligent Agents with LLM-based Process Automation. [[paper](https://dl.acm.org/doi/abs/10.1145/3637528.3671646)]
27. [2024/08/01] OpenWebAgent: An Open Toolkit to Enable Web Agents on Large Language Models. [[paper](https://aclanthology.org/2024.acl-demos.8/)]
28. [2024/08/01] Omniparser for pure vision based gui agent. [[paper](https://arxiv.org/abs/2408.00203)]
29. [2024/07/21] Towards LLMCI: Multimodal AI for LLM-Vision UI Operation. [[paper](https://doi.org/10.21203/rs.3.rs-4653823/v1)]
30. [2024/07/17] Agent-e: From autonomous web navigation to foundational design principles in agentic systems. [[paper](https://arxiv.org/abs/2407.13032)]
31. [2024/07/04] MobileExperts: A Dynamic Tool-Enabled Agent Team in Mobile Devices. [[paper](https://arxiv.org/abs/2407.03913)]
32. [2024/07/01] Tree Search for Language Model Agents. [[paper](https://arxiv.org/abs/2407.01476)]
33. [2024/06/27] Read anywhere pointed: Layout-aware gui screen reading with tree-of-lens grounding. [[paper](https://arxiv.org/abs/2406.19263)]
34. [2024/06/11] CAAP: Context-Aware Action Planning Prompting to Solve Computer Tasks with Front-End UI Only. [[paper](https://arxiv.org/abs/2406.06947)]
35. [2024/06/03] Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration. [[paper](https://arxiv.org/abs/2406.01014)]
36. [2024/05/23] AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[paper](https://arxiv.org/abs/2405.14573)]
37. [2024/05/17] Latent State Estimation Helps UI Agents to Reason. [[paper](https://arxiv.org/abs/2405.11120)]
38. [2024/04/28] MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot. [[paper](https://arxiv.org/abs/2404.18074)]
39. [2024/04/09] Autonomous Evaluation and Refinement of Web Agents. [[paper](https://arxiv.org/abs/2404.06474)]
40. [2024/04/03] PromptRPA: Generating Robotic Process Automation on Smartphones from Textual Prompts. [[paper](https://arxiv.org/abs/2404.02475)]
41. [2024/03/25] AIOS: LLM Agent Operating System. [[paper](https://arxiv.org/abs/2403.16971v3)]
42. [2024/03/05] Android in the zoo: Chain-of-action-thought for gui agents. [[paper](https://arxiv.org/abs/2403.02713)]
43. [2024/03/05] Cradle: Empowering Foundation Agents Towards General Computer Control. [[paper](https://arxiv.org/abs/2403.03186v3)]
44. [2024/02/23] On the Multi-turn Instruction Following for Conversational Web Agents. [[paper](https://arxiv.org/abs/2402.15057)]
45. [2024/02/19] CoCo-Agent: A Comprehensive Cognitive MLLM Agent for Smartphone GUI Automation. [[paper](https://arxiv.org/abs/2402.11941)]
46. [2024/02/12] OS-Copilot: Towards Generalist Computer Agents with Self-Improvement. [[paper](https://arxiv.org/abs/2402.07456)]
47. [2024/02/09] ScreenAgent: A Vision Language Model-driven Computer Control Agent. [[paper](https://arxiv.org/abs/2402.07945)]
48. [2024/02/08] Ufo: A ui-focused agent for windows os interaction. [[paper](https://arxiv.org/abs/2402.07939)]
49. [2024/02/06] Dual-View Visual Contextualization for Web Navigation. [[paper](https://arxiv.org/abs/2402.04476)]
50. [2024/01/29] Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception. [[paper](https://arxiv.org/abs/2401.16158)]
51. [2024/01/25] WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models. [[paper](https://arxiv.org/abs/2401.13919)]
52. [2024/01/17] Seeclick: Harnessing gui grounding for advanced visual gui agents. [[paper](https://arxiv.org/abs/2401.10935)]
53. [2024/01/04] MobileAgent: enhancing mobile control via human-machine interaction and SOP integration. [[paper](https://arxiv.org/abs/2401.04124)]
54. [2024/01/03] GPT-4V(ision) is a Generalist Web Agent, if Grounded. [[paper](https://arxiv.org/abs/2401.01614)]
55. [2023/12/21] AppAgent: Multimodal Agents as Smartphone Users. [[paper](https://arxiv.org/abs/2312.13771)]
56. [2023/12/20] Assistgui: Task-oriented desktop graphical user interface automation. [[paper](https://arxiv.org/abs/2312.13108)]
57. [2023/12/04] MobileGPT: Augmenting LLM with Human-like App Memory for Mobile Task Automation. [[paper](https://arxiv.org/abs/2312.03003v3)]
58. [2023/12/04] Intelligent Virtual Assistants with LLM-based Process Automation. [[paper](https://arxiv.org/abs/2312.06677)]
59. [2023/11/13] GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation. [[paper](https://arxiv.org/abs/2311.07562)]
60. [2023/10/24] WebWISE: Web Interface Control and Sequential Exploration with Large Language Models. [[paper](https://arxiv.org/abs/2310.16042)]
61. [2023/10/12] A Zero-Shot Language Agent for Computer Control with Structured Reflection. [[paper](https://arxiv.org/abs/2310.08740)]
62. [2023/09/20] You only look at screens: Multimodal chain-of-action agents. [[paper](https://arxiv.org/abs/2309.11436)]
63. [2023/09/15] Laser: Llm agent with state-space exploration for web navigation. [[paper](https://arxiv.org/abs/2309.08172)]
64. [2023/08/29] AutoDroid: LLM-powered Task Automation in Android. [[paper](https://arxiv.org/abs/2308.15272)]
65. [2023/07/24] A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis. [[paper](https://arxiv.org/abs/2307.12856)]
66. [2023/06/14] Synapse: Trajectory-as-Exemplar Prompting with Memory for Computer Control. [[paper](https://arxiv.org/abs/2306.07863)]
67. [2023/06/09] Mind2Web: Towards a Generalist Agent for the Web. [[paper](https://arxiv.org/abs/2306.06070)]
68. [2023/05/30] Sheetcopilot: Bringing software productivity to the next level through large language models. [[paper](https://arxiv.org/abs/2305.19308)]
69. [2023/05/23] Hierarchical prompting assists large language model on web navigation. [[paper](https://arxiv.org/abs/2305.14257)]
70. [2023/05/09] InternGPT: Solving Vision-Centric Tasks by Interacting with ChatGPT Beyond Language. [[paper](https://arxiv.org/abs/2305.05662)]
71. [2023/03/30] Language Models can Solve Computer Tasks. [[paper](https://arxiv.org/abs/2303.17491)]
72. [2022/09/19] Enabling conversational interaction with mobile ui using large language models. [[paper](https://arxiv.org/abs/2209.08655)]
73. [2022/05/23] Meta-gui: Towards multi-modal conversational agents on mobile gui. [[paper](https://arxiv.org/abs/2205.11029)]
    

### Evaluation & Benchmark

1. [2024/10/31] AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents. [[paper](https://arxiv.org/abs/2410.24024)]
2. [2024/10/28] AssistEditor: Multi-Agent Collaboration for GUI Workflow Automation in Video Creation. [[paper](https://dl.acm.org/doi/abs/10.1145/3664647.3684998)]
3. [2024/10/28] Shopping MMLU: A Massive Multi-Task Online Shopping Benchmark for Large Language Models. [[paper](https://arxiv.org/abs/2410.20745)]
4. [2024/10/28] MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI. [[paper](https://arxiv.org/abs/2404.16006)]
5. [2024/10/24] VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks. [[paper](https://arxiv.org/abs/2410.19100)]
6. [2024/10/22] Large Language Models Empowered Personalized Web Agents. [[paper](https://arxiv.org/abs/2410.17236)]
7. [2024/10/19] SPA-Bench: A Comprehensive Benchmark for SmartPhone Agent Evaluation. [[paper](https://arxiv.org/abs/2410.15164)]
8. [2024/10/17] MobA: A Two-Level Agent System for Efficient Mobile Task Automation. [[paper](https://arxiv.org/abs/2410.13757)]
9. [2024/10/07] Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents. [[paper](https://arxiv.org/abs/2410.05243)]
10. [2024/09/22] MobileViews: A Large-Scale Mobile GUI Dataset. [[paper](https://arxiv.org/abs/2409.14337)]
11. [2024/09/12] Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale. [[paper](https://arxiv.org/abs/2409.08264)]
12. [2024/09/06] WebQuest: A Benchmark for Multimodal QA on Web Page Sequences. [[paper](https://arxiv.org/abs/2409.13711)]
13. [2024/08/01] Omniparser for pure vision based gui agent. [[paper](https://arxiv.org/abs/2408.00203)]
14. [2024/07/26] OfficeBench: Benchmarking Language Agents across Multiple Applications for Office Automation. [[paper](https://arxiv.org/abs/2407.19056)]
15. [2024/07/22] AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks? [[paper](https://arxiv.org/abs/2407.15711)]
16. [2024/07/15] Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows? [[paper](https://arxiv.org/abs/2407.10956)]
17. [2024/07/13] RealWeb: A Benchmark for Universal Instruction Following in Realistic Web Services Navigation. [[paper](https://ieeexplore.ieee.org/abstract/document/10707522)]
18. [2024/07/11] UICrit: Enhancing Automated Design Evaluation with a UI Critique Dataset. [[paper](https://arxiv.org/abs/2407.08850)]
19. [2024/07/07] WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks. [[paper](https://arxiv.org/abs/2407.05291)]
20. [2024/07/04] MobileExperts: A Dynamic Tool-Enabled Agent Team in Mobile Devices. [[paper](https://arxiv.org/abs/2407.03913)]
21. [2024/07/03] Amex: Android multi-annotation expo dataset for mobile gui agents. [[paper](https://arxiv.org/abs/2407.17490)]
22. [2024/07/01] CRAB: Cross-environment Agent Benchmark for Multimodal Language Model Agents. [[paper](https://arxiv.org/abs/2407.01511)]
23. [2024/07/01] Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents. [[paper](https://arxiv.org/abs/2407.00993)]
24. [2024/06/27] Read Anywhere Pointed: Layout-aware GUI Screen Reading with Tree-of-Lens Grounding. [[paper](https://arxiv.org/abs/2406.19263)]
25. [2024/06/20] E-ANT: A Large-Scale Dataset for Efficient Automatic GUI NavigaTion. [[paper](https://arxiv.org/abs/2406.14250)]
26. [2024/06/20] Identifying User Goals from UI Trajectories. [[paper](https://arxiv.org/abs/2406.14314)]
27. [2024/06/19] GUI Action Narrator: Where and When Did That Action Take Place? [[paper](https://arxiv.org/abs/2406.13719)]
28. [2024/06/18] WebCanvas: Benchmarking Web Agents in Online Environments. [[paper](https://arxiv.org/abs/2406.12373)]
29. [2024/06/17] GUICourse: From General Vision Language Models to Versatile GUI Agents. [[paper](https://arxiv.org/abs/2406.11317)]
30. [2024/06/14] VideoGUI: A Benchmark f om Instructional Videos. [[paper](https://arxiv.org/abs/2406.10227)]
31. [2024/06/12] GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices. [[paper](https://arxiv.org/abs/2406.08451)]
32. [2024/06/12] GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents. [[paper](https://arxiv.org/abs/2406.10819)]
33. [2024/06/12] MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents. [[paper](https://arxiv.org/abs/2406.08184)]
34. [2024/06/06] On the Effects of Data Scale on UI Control Agents. [[paper](https://arxiv.org/abs/2406.03679)]
35. [2024/06/05] WebOlympus: An Open Platform for Web Agents on Live Websites. [[paper](https://aclanthology.org/2024.emnlp-demo.20/)]
36. [2024/06/05] UGIF-DataSet: A New Dataset for Cross-lingual, Cross-modal Sequential actions on the UI. [[paper](https://aclanthology.org/2024.findings-naacl.89/)]
37. [2024/06/01] WebSuite: Systematically Evaluating Why Web Agents Fail. [[paper](https://arxiv.org/abs/2406.01623)]
38. [2024/05/23] AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[paper](https://arxiv.org/abs/2405.14573)]
39. [2024/05/23] AGILE: A Novel Reinforcement Learning Framework of LLM Agents. [[paper](https://arxiv.org/abs/2405.14751)]
40. [2024/05/17] Latent state estimation helps ui agents to reason. [[paper](https://arxiv.org/abs/2405.11120)]
41. [2024/05/07] Mapping natural language instructions to mobile UI action sequences. [[paper](https://arxiv.org/abs/2005.03776)]
42. [2024/05/05] Visual grounding for desktop graphical user interfaces. [[paper](https://arxiv.org/abs/2407.01558)]
43. [2024/04/28] MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot. [[paper](https://arxiv.org/abs/2404.18074)]
44. [2024/04/25] Benchmarking mobile device control agents across diverse configurations. [[paper](https://arxiv.org/abs/2404.16660)]
45. [2024/04/15] MMInA: Benchmarking multihop multimodal internet agents. [[paper](https://arxiv.org/abs/2404.09992)]
46. [2024/04/12] Llamatouch: A faithful and scalable testbed for mobile ui task automation. [[paper](https://arxiv.org/abs/2404.16054)]
47. [2024/04/11] OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[paper](https://arxiv.org/abs/2404.07972)]
48. [2024/04/09] VisualWebBench: How Far Have Multimodal LLMs Evolved in Web Page Understanding and Grounding? [[paper](https://arxiv.org/abs/2404.05955)]
49. [2024/04/09] GUIDE: Graphical User Interface Data for Execution. [[paper](https://arxiv.org/abs/2404.16048)]
50. [2024/04/08] Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs. [[paper](https://arxiv.org/abs/2404.05719)]
51. [2024/04/04] Autowebglm: Bootstrap and reinforce a large language model-based web navigating agent. [[paper](https://arxiv.org/abs/2404.03648)]
52. [2024/03/29] Evaluating language model agents on realistic autonomous tasks. [[paper](https://arxiv.org/abs/2312.11671)]
53. [2024/03/29] Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want. [[paper](https://arxiv.org/abs/2403.20271)]
54. [2024/03/26] AgentStudio: A Toolkit for Building General Virtual Agents. [[paper](https://arxiv.org/abs/2403.17918)]
55. [2024/03/18] Tur[k]ingBench: A Challenge Benchmark for Web Agents. [[paper](https://arxiv.org/abs/2403.11905)]
56. [2024/03/15] Computer User Interface Understanding. A New Dataset and a Learning Framework. [[paper](https://arxiv.org/abs/2403.10170)]
57. [2024/03/12] Workarena: How capable are web agents at solving common knowledge work tasks? [[paper](https://arxiv.org/abs/2403.07718)]
58. [2024/03/06] PPTC-R benchmark: Towards Evaluating the Robustness of Large Language Models for PowerPoint Task Completion. [[paper](https://arxiv.org/abs/2403.03788)]
59. [2024/03/05] Android in the Zoo:Chain-of-Action-Thought for GUI Agents. [[paper](https://arxiv.org/abs/2403.02713)]
60. [2024/02/27] Omniact: A dataset and benchmark for enabling multimodal generalist autonomous agents for desktop and web. [[paper](https://arxiv.org/abs/2402.17553)]
61. [2024/02/23] On the Multi-turn Instruction Following for Conversational Web Agents. [[paper](https://arxiv.org/abs/2402.15057)]
62. [2024/02/09] Understanding the weakness of large language model agents within a complex android environment. [[paper](https://arxiv.org/abs/2402.06596)]
63. [2024/02/08] WebLINX: Real-World website navigation with Multi-Turn dialogue. [[paper](https://arxiv.org/abs/2402.05930)]
64. [2024/01/29] Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception. [[paper](https://arxiv.org/abs/2401.16158)]
65. [2024/01/25] Webvoyager: Building an end-to-end web agent with large multimodal models. [[paper](https://arxiv.org/abs/2401.13919)]
66. [2024/01/25] GPTVoiceTasker: Advancing Multi-step Mobile Task Efficiency Through Dynamic Interface Exploration and Learning. [[paper](https://arxiv.org/abs/2401.14268)]
67. [2024/01/24] Visualwebarena: Evaluating multimodal agents on realistic visual web tasks. [[paper](https://arxiv.org/abs/2401.13649)]
68. [2024/01/24] Agentboard: An analytical evaluation board of multiturn LLM agents. [[paper](https://arxiv.org/abs/2401.13178)]
69. [2024/01/17] Seeclick: Harnessing gui grounding for advanced visual gui agents. [[paper](https://arxiv.org/abs/2401.10935)]
70. [2023/12/26] AutoTask: Executing Arbitrary Voice Commands by Exploring and Learning from Mobile GUI. [[paper](https://arxiv.org/abs/2312.16062)]
71. [2023/12/25] WebVLN: Vision-and-Language Navigation on Websites. [[paper](https://arxiv.org/abs/2312.15820)]
72. [2023/12/20] ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation. [[paper](https://arxiv.org/abs/2312.13108)]
73. [2023/11/30] Exposing Limitations of Language Model Agents in Sequential-Task Compositions on the Web. [[paper](https://arxiv.org/abs/2311.18751)]
74. [2023/11/21] GAIA: a benchmark for general AI assistants. [[paper](https://arxiv.org/abs/2311.12983)]
75. [2023/11/13] GPT-4V in wonderland: Large multimodal models for Zero-Shot smartphone GUI navigation. [[paper](https://arxiv.org/abs/2311.07562)]
76. [2023/11/03] Pptc benchmark: Evaluating large language models for powerpoint task completion. [[paper](https://arxiv.org/abs/2311.01767)]
77. [2023/10/16] OpenAgents: An Open Platform for Language Agents in the Wild. [[paper](https://arxiv.org/abs/2310.10634)]
78. [2023/09/20] You Only Look at Screens:Multimodal Chain-of-Action Agents. [[paper](https://arxiv.org/abs/2309.11436)]
79. [2023/08/29] AutoDroid: LLM-powered Task Automation in Android. [[paper](https://arxiv.org/abs/2308.15272)]
80. [2023/08/07] Agentbench: Evaluating llms as agents. [[paper](https://arxiv.org/abs/2308.03688)]
81. [2023/07/25] Webarena: A realistic web environment for building autonomous agents. [[paper](https://arxiv.org/abs/2307.13854)]
82. [2023/07/19] Android in the wild: A large-scale dataset for android device control. [[paper](https://arxiv.org/abs/2307.10088)]
83. [2023/06/09] Mind2Web: Towards a Generalist Agent for the Web. [[paper](https://arxiv.org/abs/2306.06070)]
84. [2023/05/30] Sheetcopilot: Bringing software productivity to the next level through large language models. [[paper](https://arxiv.org/abs/2305.19308)]
85. [2023/05/25] On the tool manipulation capability of open-source large language models. [[paper](https://arxiv.org/abs/2305.16504)]
86. [2023/05/14] Mobile-env: A universal platform for training and evaluation of mobile interaction. [[paper](https://arxiv.org/abs/2305.08144v1)]
87. [2023/05/14] Mobile-env: Building qualified evaluation benchmarks for llm-gui interaction. [[paper](https://arxiv.org/abs/2305.08144)]
88. [2023/04/14] Droidbot-gpt: Gpt-powered ui automation for android. [[paper](https://arxiv.org/abs/2304.07061)]
89. [2023/04/10] OpenAGI: When LLM Meets Domain Experts. [[paper](https://arxiv.org/abs/2304.04370)]
90. [2023/03/13] Vision-Language models as success detectors. [[paper](https://arxiv.org/abs/2303.07280)]
91. [2022/11/14] Ugif: Ui grounded instruction following. [[paper](https://arxiv.org/abs/2211.07615)]
92. [2022/10/08] Understanding html with large language models. [[paper](https://arxiv.org/abs/2210.03945)]
93. [2022/09/29] MUG: Interactive Multimodal Grounding on User Interfaces. [[paper](https://arxiv.org/abs/2209.15099)]
94. [2022/09/16] ScreenQA: Large-Scale Question-Answer Pairs over Mobile App Screenshots. [[paper](https://arxiv.org/abs/2209.08199)]
95. [2022/07/04] Webshop: Towards scalable real-world web interaction with grounded language agents. [[paper](https://arxiv.org/abs/2207.01206)]
96. [2022/05/23] Meta-gui: Towards multi-modal conversational agents on mobile gui. [[paper](https://arxiv.org/abs/2205.11029)]
97. [2022/02/04] A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility. [[paper](https://arxiv.org/abs/2202.02312)]
98. [2021/04/17] Mobile app tasks with iterative feedback (motif): Addressing task feasibility in interactive visual environments. [[paper](https://arxiv.org/abs/2104.08560)]
99. [2021/01/23] Websrc: A dataset for web-based structural reading comprehension. [[paper](https://arxiv.org/abs/2101.09465)]
100. [2018/08/28] Mapping natural language commands to web elements. [[paper](https://arxiv.org/abs/1808.09132)]
101. [2017/11/06] Building natural language interfaces to web apis. [[paper](https://dl.acm.org/doi/10.1145/3132847.3133009)]
102. [2017/08/06] World of bits: An open-domain platform for web-based agents. [[paper](https://dl.acm.org/doi/10.5555/3305890.3306005)]


### Safety & Privacy

1. [2024/11/04] Attacking Vision-Language Computer Agents via Pop-ups. [[paper](https://arxiv.org/abs/2411.02391)]
2. [2024/10/23] MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control. [[paper](https://arxiv.org/abs/2410.17520)]
3. [2024/10/22] Advweb: Controllable black-box attacks on vlm-powered web agents. [[paper](https://arxiv.org/abs/2410.17401)]
4. [2024/10/11] Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents. [[paper](https://arxiv.org/abs/2410.13886)]
5. [2024/10/09] ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents. [[paper](https://arxiv.org/abs/2410.06703)]
6. [2024/09/17] Eia: Environmental injection attack on generalist web agents for privacy leakage. [[paper](https://arxiv.org/abs/2409.11295)]
7. [2024/08/05] Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions. [[paper](https://arxiv.org/abs/2408.02544)]
8. [2024/07/12] Security Matrix for Multimodal Agents on Mobile Devices: A Systematic and Proof of Concept Study. [[paper](https://arxiv.org/abs/2407.09295)]
9. [2024/06/18] Adversarial Attacks on Multimodal Agents. [[paper](https://arxiv.org/abs/2406.12814)]
10. [2024/02/26] WIPI: A New Web Threat for LLM-Driven Web Agents. [[paper](https://arxiv.org/abs/2402.16965)]
11. [2023/08/03] From Prompt Injections to SQL Injection Attacks: How Protected is Your LLM-Integrated Web Application? [[paper](https://arxiv.org/abs/2308.01990)]


## Useful Links
1. aialt/awesome-mobile-agents: https://github.com/aialt/awesome-mobile-agents <br>
2. OSU-NLP-Group/GUI-Agents-Paper-List: https://github.com/OSU-NLP-Group/GUI-Agents-Paper-List <br>
3. vyokky/LLM-Brained-GUI-Agents-Survey: https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey <br>


## Contact
The repo is still being updated rapidly🚀. Please let us know if you notice any mistakes or would like any work related to OS Agents to be included in our list by e-mail: huxueyu.zju@gmail.com.
<!--
Please let us know if you find out a mistake or are interested in contributing by e-mail: huxueyu.zju@gmail.com.
-->


## Citation
If you find our repository helpful, we would appreciate it if you could cite:
```
@misc{hu2024osagents,  
  title        = {OS Agents: A Survey on MLLM-based Agents for General Computing Devices Use},  
  author       = {Xueyu Hu and Tao Xiong and Biao Yi and Zishu Wei and Ruixuan Xiao and Yurun Chen and Jiasheng Ye and Meiling Tao and Xiangxin Zhou and Ziyu Zhao and Yuhuai Li and Shengze Xu and Shawn Wang and Xinchen Xu and Shuofei Qiao and Kun Kuang and Tieyong Zeng and Liang Wang and Jiwei Li and Yuchen Eleanor Jiang and Wangchunshu Zhou and Guoyin Wang and Keting Yin and Zhou Zhao and Hongxia Yang and Fan Wu and Shengyu Zhang and Fei Wu},  
  year         = {2024},  
  howpublished = {\url{https://github.com/OS-Agent-Survey/OS-Agent-Survey/}},  
}  
```
