<div align="center">

![logo](./images/logo.png)

</div>

<div align="center">

![visitors](https://visitor-badge.laobi.icu/badge?page_id=jingyaogong/minimind)
[![GitHub Repo stars](https://img.shields.io/github/stars/jingyaogong/minimind?style=social)](https://github.com/jingyaogong/minimind/stargazers)
[![GitHub Code License](https://img.shields.io/github/license/jingyaogong/minimind)](LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/jingyaogong/minimind)](https://github.com/jingyaogong/minimind/commits/master)
[![GitHub pull request](https://img.shields.io/badge/PRs-welcome-blue)](https://github.com/jingyaogong/minimind/pulls)
[![Collection](https://img.shields.io/badge/🤗-MiniMind%20%20Collection-blue)](https://huggingface.co/collections/jingyaogong/minimind-66caf8d999f5c7fa64f399e5)

</div>

<div align="center">

![GitHub Trend](https://trendshift.io/api/badge/repositories/12586)

</div>

<div align="center">
  <h3>"The Great Way is Simple"</h3>
</div>

<div align="center">

[中文](./README.md) | English

</div>

> **Personal fork note:** I'm using this repo to study LLM training from scratch. My focus is on the SFT and DPO stages. If you're here by accident, check out the [original repo](https://github.com/jingyaogong/minimind) instead!

* This open-source project aims to train MiniMind, an ultra-small language model with about 64M parameters, entirely from scratch with only about RMB 3 in cost and 2 hours of training time.
* The MiniMind series is intentionally lightweight. The smallest model on the main branch is about $\frac{1}{2700}$ the size of GPT-3, making full training and reproduction feasible even on ordinary personal GPUs.
* The project provides a minimalist model architecture and an end-to-end LLM training pipeline, covering MoE, data cleaning, pretraining, Supervised Fine-Tuning (SFT), LoRA, RLHF (DPO), RLAIF (PPO / GRPO / CISPO), Tool Use, Agentic RL, Adaptive Thinking, and Model Distillation.
* MiniMind has also been extended to a vision model [MiniMind-V](https://github.com/jingyaogong/minimind-v), a multimodal Omni model [MiniMind-O](https://github.com/jingyaogong/minimind-o), a diffusion language model (MiniMind-dLM), and a linear attention model (MiniMind-Linear). See [Discussion](https://github.com/jingyaogong/minimind/discussions) for details.
* All core algorithms are implemented directly in native PyTorch, without relying on high-level abstractions from third-party libraries.
* MiniMind is both an end-to-end open-source reproduction of the LLM training pipeline and a hands-on tutorial for learning how LLMs are built.
* We hope this project can provide a reproducible, understandable, and extensible starting point for more people, share the joy of creation, and help move the broader AI community forward.

> Note: This project is released under the Apache 2.0 license and is completely free. "2 hours" refers to the measured time for running `1 epoch` of the SFT stage on a single NVIDIA 3090, while "RMB 3" refers to the corresponding GPU rental cost.

---

<div align="center">

![minimind-3](./images/minimind-3.gif)

[🔗 Online Demo](https://www.modelscope.cn/studios/gongjy/MiniMind) | [🔗 Video Introduction](https://www.bilibil