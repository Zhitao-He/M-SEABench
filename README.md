<div align="center">

# Multimodal-SEA: Benchmarking AI Agent Security under Multimodal Social Engineering Attacks

</div>

<div align="center">
<b><a href="https://scholar.google.com/citations?user=ULvoYXgAAAAJ&hl=zh-CN" target="_blank">Zhitao He</a><sup>1</sup> <a href="mailto:chzheng@connect.ust.hk">Chi Him Zheng</a><sup>1</sup> <a href="mailto:chanag@connect.ust.hk">Chengru Han</a><sup>1</sup> <a href="https://mayrfung.github.io/" target="_blank">Yi R. (May) Fung</a><sup>1</sup></b>

<sup>1</sup>MMSense Lab, Hong Kong University of Science and Technology

<p align="center">
  <img src="https://img.shields.io/badge/arXiv-Coming%20Soon-B31B1B.svg?logo=arxiv&amp;logoColor=white" alt="arXiv (coming soon)">
  <a href="Multimodel_SEA_paper.pdf"><img src="https://img.shields.io/badge/Paper-PDF-B31B1B.svg?style=flat" alt="Paper (PDF)" height="20"></a>
</p>
</div>

## Introduction

Personal AI agents face social engineering attacks supported by **forged multimodal content**, but existing evaluations mainly focus on text-based dialogue, leaving their intrinsic security under such attacks insufficiently studied. We introduce **Multimodal-SEA**, an interactive benchmark comprising **608 expert-designed tasks** grounded in real-world fraud cases, covering **14 domains** and **152 attack scenarios** with prepared multimodal content. The tasks span **four difficulty levels** and reflect the distinct social and cultural contexts of **Chinese and English** environments. Agents inspect content, verify requests, and execute actions in simulated applications, with attack outcomes grounded in **verifiable tool execution logs**.

Evaluating **seven widely used multimodal models** across **six dimensions** reveals that all are vulnerable, with attack success rates of **7.1% to 34.5%**. **Adding multimodal content increases attack success from 19.9% to 29.2%**, despite increased proactive verification coverage. Stronger safety instructions reduce attack success without improving the recognition of deceptive multimodal content.

Our main contributions include:

- **Multimodal-SEA Benchmark.** An interactive benchmark for evaluating the intrinsic security of personal AI agents under multimodal social engineering attacks. Grounded in real-world fraud cases, it covers 14 domains, four difficulty levels, and Chinese and English tasks reflecting distinct social and cultural contexts.
- **Systematic Evaluation and Analysis.** Seven widely used multimodal models evaluated across six dimensions covering both attack outcomes and agent verification behavior. Content ablation, prompt-based defense, and benign task evaluation reveal how multimodal content strengthens deception and where the intrinsic security of agents remains limited.

## Task Layout

```text
data/
└── tasks/
    ├── agent_expense/
    ├── charity/
    ├── digital_assets/
    ├── education/
    ├── gov/
    ├── medical/
    ├── payment/
    ├── property/
    ├── shopping/
    ├── smart_device/
    ├── social/
    ├── telecom/
    ├── travel/
    └── work/
```

## Citation

Citation information will be added when the paper is released.
