# Awesome Activation Steering

> A curated collection of papers on **activation steering** and **representation engineering** in large language models.

## What is Activation Steering?
- A technique for guiding model behavior by directly modifying internal activation values at inference time—typically by intervening in the residual stream.
- The term "Activation Engineering" was coined in the paper *Steering Language Models With Activation Engineering* (arXiv, August 2023).
- The central challenge is finding a meaningful steering direction within the LLM's high-dimensional latent space that reliably produces the desired behavioral change.

---

## 📑 Table of Contents

- [Benchmarks](#benchmarks)
- [Activation Steering](#-activation-steering)
- [Representation Engineering](#-representation-engineering)
- [Persona & Role-Play in LLMs](#-persona--role-play-in-language-models)
- [Linear Representations in LLMs](#-linear-representations-in-language-models)
- [Personality Modelling in LLMs](#-personality-modelling-in-llms)

---

## 🏆 Benchmarks
- **[AxBench](https://arxiv.org/abs/2501.17148)**: Steering LLMs? Even Simple Baselines Outperform Sparse Autoencoders `ICML 2025 Spotlight`
- [Steer-Bench: A Benchmark for Evaluating the Steerability of LLMs](https://arxiv.org/html/2505.20645v2) `2025-01` `arXiv`
- [AISteer360](https://ibm.github.io/AISteer360/) `2025-01`

## 🎯 Activation Steering

- **[ActAdd](https://arxiv.org/abs/2308.10248)**: Steering language models with activation engineering `2023-08` `arXiv`
- **[ITI](https://arxiv.org/abs/2306.03341)**: Inference-Time Intervention: Eliciting Truthful Answers from a Language Model `NIPS 2023 Spotlight`
- **[CAA](https://arxiv.org/abs/2312.06681)**: Steering Llama 2 via Contrastive Activation Addition `ACL 2024` `🏆 Outstanding Paper`
- [Analyzing the Generalization and Reliability of Steering Vectors](https://arxiv.org/abs/2407.12404) `2024-07` `arXiv`
- [Reliability Challenges in Steering Language Models](https://arxiv.org/abs/2504.04635) `2025-04` `arXiv`
- [SAEs Are Good for Steering — If You Select the Right Features](https://arxiv.org/abs/2505.20063) `EMNLP 2025`
- [Improved Representation Steering for Language Models](https://arxiv.org/abs/2505.20809) `NIPS 2025`
- [HyperSteer: Activation Steering at Scale with Hypernetworks](https://arxiv.org/abs/2506.03292) `2025-06` `arXiv`
- [Steerable Chatbots: Personalizing LLMs with Preference-Based Activation Steering](https://arxiv.org/abs/2505.04260) `2025-05` `arXiv`
- [BILLY: Steering LLMs via Merging Persona Vectors for Creative Generation](https://arxiv.org/abs/2510.10157) `2025-10` `arXiv`
- [CogSteer: Cognition-Inspired Selective Layer Intervention for Efficiently Steering LLMs](https://arxiv.org/abs/2410.17714) `ACL 2025 Findings`
- [Toward universal steering and monitoring of AI models](https://www.science.org/doi/10.1126/science.aea6792) `2026` `Science`

### AI Safety
- [Refusal in language models is mediated by a single direction](https://arxiv.org/abs/2406.11717) `2024-06` `arXiv`
- [Programming Refusal with Conditional Activation Steering](https://arxiv.org/abs/2409.05907) `ICLR 2025 Spotlight`

### Personality Steering
- [Identifying and Manipulating Personality Traits in LLMs Through Activation Engineering](https://arxiv.org/abs/2412.10427) `2024-12` `arXiv`
- **[Activation-Space Personality Steering](https://arxiv.org/abs/2511.03738)**: Hybrid Layer Selection for Stable Trait Control in LLMs `2025-10` `arXiv`
- [PERSONA: Dynamic and Compositional Inference-Time Personality Control via Activation Vector Algebra](https://arxiv.org/abs/2602.15669) `2026` `ICLR`

### Dynamic Activation Steering
- [Programming Refusal with Conditional Activation Steering](https://arxiv.org/abs/2409.05907) `ICLR 2025 Spotlight`
- [ODESteer: A Unified ODE-Based Steering Framework for LLM Alignment](https://arxiv.org/abs/2602.17560) `ICLR 2026`

### Reasoning
- [Improving Reasoning in LLMs via Representation Engineering](https://arxiv.org/abs/2504.19483) `2025-04` `arXiv`
- [Steering LLMs' Reasoning with activation state machines](https://openreview.net/forum?id=p17En1bhCY) `2025-09` `OpenReview`

---

## 🔬 Representation Engineering

- **[RepE](https://arxiv.org/abs/2310.01405)**: Representation Engineering: A Top-Down Approach to AI Transparency `2023-10` `arXiv`
- [Looking inward: Language models can learn about themselves by introspection](https://arxiv.org/abs/2410.13787) `2024-10` `arXiv`
- [LLM evaluators recognize and factor their own generations](https://arxiv.org/html/2404.13076v1) `2024-04` `arXiv`
- [Inspection and control of self-generated-text recognition ability in Llama3-8B-Instruct](https://arxiv.org/abs/2410.02064) `ICLR 2025`
- [Tell me about yourself: LLMs are aware of their learned behaviors](https://arxiv.org/abs/2501.11120) `ICLR 2025`
- [Simple mechanistic explanations for out-of-context reasoning](https://arxiv.org/abs/2507.08218) `ICML 2025 Workshop`
- [Emergent introspective awareness in large language models](https://arxiv.org/abs/2601.01828) `2026-01` `arXiv`

---

## 🎭 Persona & Role-Play in Language Models

### Anthropic

- **[Persona Vectors](https://arxiv.org/abs/2507.21509)**: Monitoring and Controlling Character Traits in Language Models `2025-07` `arXiv`
- **[The Assistant Axis](https://arxiv.org/abs/2601.10387)**: Situating and Stabilizing the Default Persona of Language Models `2026-01` `arXiv`

### Role-Play

- [Role Play with large language models](https://arxiv.org/abs/2305.16367) `Nature 2023-11`
- [RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities](https://arxiv.org/abs/2310.00746) `2023-10` `arXiv`
- [Character-LLM: A Trainable Agent for Role-Playing](https://arxiv.org/abs/2310.10158) `EMNLP 2023`
- Measuring and Controlling Instruction (In)Stability in Language Model Dialogs `COLM 2024`
- [From Persona to Personalization: A Survey on Role-Playing Language Agents](https://arxiv.org/abs/2404.18231) `TMLR 2024`

---

## 📐 Linear Representations in Language Models

### Anthropic Blog Posts

- [Towards Monosemanticity: Decomposing Language Models with Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html) `2023-10`
- [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html) `2024-05`
- [Circuit Tracing: Revealing Computational Graphs in Language Models](https://transformer-circuits.pub/2025/attribution-graphs/index.html) `2025-03`
- [On the Biology of a LLM](https://transformer-circuits.pub/2025/biology-of-a-llm/index.html) `2025-03`
- [Emotion Concepts and their Function in a Large Language Model](https://transformer-circuits.pub/2026/emotions/index.html) `2026-04`

### SAEs

- [Sparse Autoencoders Find Highly Interpretable Features in LMs](https://arxiv.org/abs/2309.08600) `2023-09` `arXiv`
- [Transcoders Find Interpretable LLM Feature Circuits](https://arxiv.org/abs/2406.11944) `NIPS 2024`
- [Auditing Language Models for Hidden Objectives](https://arxiv.org/abs/2503.10965) `2025-03` `arXiv`

---

## 🧠 Personality Modelling in LLMs

- [PersonaLLM: Investigating the ability of LLMs to express personality traits](https://arxiv.org/abs/2305.02547) `NAACL 2024 Findings`
- [Personality Traits in LLMs](https://arxiv.org/abs/2307.00184) `2025-07` `arXiv`
- [Big5-Chat: Shaping LLM personalities through training on human-grounded data](https://arxiv.org/abs/2410.16491) `2024-10` `arXiv`
- [Personality Vector: Modulating Personality of LLMs by Model Merging](https://arxiv.org/abs/2509.19727) `EMNLP 2025`

### Benchmarks
- [LaMP: When Large Language Models Meet Personalization](https://aclanthology.org/2024.acl-long.399/) `ACL 2024`
- [LongLaMP: A Benchmark for Personalized Long-form Text Generation](https://arxiv.org/abs/2407.11016) `2025-06` `arXiv`
