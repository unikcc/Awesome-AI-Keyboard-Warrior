# Awesome AI Keyboard Warrior

This repository contains research on using AI to control computers solely through the mouse and keyboard.

<p align="center">
  <a href="#1">Papers</a> •
  <a href="#2">Simulation Environments & Benchmarks</a> •
  <a href="#3">Auxiliary Tools</a>
</p>

<a href="https://github.com/unikcc/Awesome-AI-Keyboard-Warrior">
  <img src="https://img.shields.io/badge/AIKeyboardWarrirr-0.1-blue" alt="Awesome-AI-Keyboard-Warrior">
</a>
<a href="https://huggingface.co/docs/transformers/index" rel="nofollow">
  <img src="https://img.shields.io/github/last-commit/unikcc/Awesome-AI-Keyboard-Warrior?color=orange" alt="Awesome-AI-Keyboard-Warrior">
</a>
<a href="https://github.com/unikcc/Awesome-AI-Keyboard-Warrior" rel="nofollow">
  <img src="https://img.shields.io/badge/PRs-Welcome-green" alt="Welcome">
</a>
<a href="https://github.com/unikcc/Awesome-AI-Keyboard-Warrior/blob/master/LICENSE" rel="nofollow">
  <img src="https://img.shields.io/badge/LICENSE-MIT-cyan" alt="LICENSE">
</a>


## 🔔 News
- **2023-02-15** We created a new repository dedicated to exploring the topic of "Human-like AI Control: Operating Computers with Mouse and Keyboard," aptly named "AI Keyboard Warrior" (AI键盘侠).

---

<h2 id="1">📜 Papers </h2>
<ol>

<li> A data-driven approach for learning to control computers Peter C Humphreys, 
<!-- <strong>  -->
David Raposo, Tobias Pohlen, Gregory Thornton, Rachita Chhaparia, Alistair Muldal, Josh Abramson, Petko Georgiev, Adam Santoro, Timothy Lillicrap, ICML, 2022, [<a href="https://proceedings.mlr.press/v162/humphreys22a.html">Paper</a>]</li>

<li>Video PreTraining (VPT): Learning to Act by Watching Unlabeled Online Videos 
<!-- <strong> -->
Bowen Baker, Ilge Akkaya, Peter Zhokhov, Joost Huizinga, Jie Tang, Adrien Ecoffet, Brandon Houghton, Raul Sampedro, Jeff Clune, NeurIPS, 2022, [<a href="https://openreview.net/forum?id=AXDNM76T1nc">Paper</a>], [<a href="https://github.com/openai/Video-Pre-Training">Code</a>]</li>
<!-- </strong> -->

<li>MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge 
<!-- <strong> -->
Linxi Fan, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, Anima Anandkumar
<!-- </strong> -->
, NeurIPS, Outstanding paper, 2022, [<a href="https://openreview.net/forum?id=rc8o_j8I8PX">Paper</a>], [<a href="https://github.com/MineDojo/MineDojo">Code</a>], [<a href="https://minedojo.org/">Demo</a>]</li>

<li> Do As I Can, Not As I Say:
Grounding Language in Robotic Affordances  
<!-- <strong> -->
Michael Ahn, Anthony Brohan, Noah Brown, Yevgen Chebotar, Omar Cortes
<!-- </strong> -->
Arxiv, 2022, 
[<a href="https://arxiv.org/pdf/2204.01691.pdf">Paper</a>], [<a href="https://say-can.github.io/">Demo</a>]</li>

<li>WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents 
<!-- <strong> -->
Shunyu Yao, Howard Chen, John Yang, Karthik Narasimhan
<!-- </strong> -->
, NeurIPS, 2022 [<a href="https://openreview.net/forum?id=R9KnuFlvnU">Paper</a>], [<a href="https://github.com/princeton-nlp/WebShop">Code</a>], [<a href="https://webshop-pnlp.github.io/">Demo</a>]</li>

<li>Do BERTs Learn to Use Browser User Interface? Exploring Multi-Step Tasks with Unified Vision-and-Language BERTs 
<!-- <strong> -->
Taichi Ik, Akiko Aizawa
<!-- </strong> -->
, Arxiv, [<a href="https://arxiv.org/abs/2203.07828">Paper</a>]</li>

<li>Reinforcement Learning on Web Interfaces using Workflow-Guided Exploration 
<!-- <strong> -->
Evan Zheran Liu, Kelvin Guu, Panupong Pasupat, Tianlin Shi, Percy Liang
<!-- </strong> -->
, ICLR, 2018, [<a href="https://openreview.net/forum?id=ryTp3f-0-">Paper</a>]</li>

<li>World of Bits: An Open-Domain Platform for Web-Based Agents 
<!-- <strong> -->
Tianlin Shi, Andrej Karpathy, Linxi Fan, Jonathan Hernandez, Percy Liang
<!-- </strong> -->
, ICML, 2017, [<a href="https://proceedings.mlr.press/v70/shi17a.html">Paper</a>]</li>

<li>
Language Models can Solve Computer Tasks 
Geunwoo Kim, Pierre Baldi, Stephen McAleer,
, Arxiv, 2023, 
[<a href="https://arxiv.org/abs/2303.17491">Paper</a>],
[<a href="https://posgnu.github.io/rci-web/">Project</a>]
</li>


<li>
From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces
<strong>
Peter Shaw, Mandar Joshi, James Cohan, Jonathan Berant, Panupong Pasupat, Hexiang Hu, Urvashi Khandelwal, Kenton Lee, Kristina Toutanova
</strong>, NIPS, 2023, 
[<a href="https://openreview.net/forum?id=3PjCt4kmRx">Paper</a>],
</li>


<li>
Android in the Wild: A Large-Scale Dataset for Android Device Control
<strong>
Christopher Rawles, Alice Li, Daniel Rodriguez, Oriana Riva, Timothy Lillicrap
</strong>, NIPS (Dataset Trasck), 2024, 
[<a href="https://arxiv.org/abs/2307.10088">Paper</a>],
[<a href="https://github.com/google-research/google-research/tree/master/android_in_the_wild">Code</a>],
</li>

<li>
Synapse: Leveraging Few-Shot Exemplars for Human-Level Computer Control
<strong>
Longtao Zheng, Rundong Wang, Bo An
</strong>, ICLR, 2024, 
[<a href="https://arxiv.org/abs/2306.07863">Paper</a>],
[<a href="https://ltzheng.github.io/Synapse/">Project</a>],
</li>

<li>
A Zero-Shot Language Agent for Computer Control with Structured Reflection
<strong>
Tao Li, Gang Li, Zhiwei Deng, Bryan Wang, Yang Li
</strong>, EMNLP(Findings), 2023, 
[<a href="https://arxiv.org/abs/2310.08740">Paper</a>],
[<a href="https://github.com/google-research/google-research/tree/master/zero_shot_structured_reflection">Code</a>],
</li>

<li>
SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents
<strong>
Kanzhi Cheng, Qiushi Sun, Yougang Chu, Fangzhi Xu, Yantao Li, Jianbing Zhang, Zhiyong Wu
</strong>, arxiv, 2023, 
[<a href="https://arxiv.org/abs/2401.10935">Paper</a>],
[<a href="https://github.com/njucckevin/SeeClick">Code & Data</a>],
</li>

</ol>

<h2 id="2">🎮 Simulation Environment && Benchmark</h2>

1. MiniWoB++: A web interaction benchmark for reinforcement learning [[Site](https://github.com/Farama-Foundation/miniwob-plusplus)]


2. MineRL Dataset:  Towards AI in Minecraft, [[Site](https://minerl.io/dataset/)]

3. WebShop: Towards real-world web interaction with grounded language agents [[Site](https://webshop-pnlp.github.io/)]

4. MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge [[Site](https://minedojo.org/)]


<h2 id="3">🚀 Auxiliary Tool </h2>

1. Sandbox2: Generates sandboxes for C/C++ libraries automatically [[Project Site](https://github.com/google/sandboxed-api/tree/main/sandboxed_api/sandbox2)]

2. Chrome Webdriver Security Considerations [[Project Site](https://chromedriver.chromium.org/security-considerations)]

3. MCP-Reborn: an MCP (Mod Coder Pack) for Minecraft for making modded clients and researching its code. (1.13-1.19.2) [[Project Site](https://github.com/Hexeption/MCP-Reborn)]


## 💖Acknowledgments

This project uses some code adapted from the following repositories:

- [awesome-embodied-vision](https://github.com/ChanganVR/awesome-embodied-vision)
- [Chain-of-ThoughtsPapers](https://github.com/zjunlp/Prompt4ReasoningPapers)


