# GMAI-VL-R1

> 🔬 Official codebase for the paper:  
> **[GMAI-VL-R1: Harnessing Reinforcement Learning for Multimodal Medical Reasoning](https://arxiv.org/pdf/2504.01886)**  
> **arXiv: 2504.01886** · Yanzhou Su, Tianbin Li, Jiyao Liu, Chenglong Ma, Junzhi Ning, Cheng Tang, Sibo Ju, Jin Ye, Pengcheng Chen, Ming Hu, et al.

---

## 📘 Introduction

This repository contains the implementation of **GMAI-VL-R1**, a framework for **multimodal medical reasoning** powered by **reinforcement learning**.

We aim to explore how large vision-language models (VLMs) can improve **medical visual understanding and reasoning** with **rule-based reward design** and **high-quality medical datasets**.

Our method incorporates recent advancements in reinforcement learning for vision-language models and adapts them to the challenging domain of **medical imaging**.

---

## 🧠 Built Upon

Our work builds upon and integrates ideas from several open-source projects:

- [MM-Eureka-V0 (FanqingM/MM-Eureka-V0)](https://github.com/FanqingM/MM-Eureka-V0)
- [open-r1-multimodal (EvolvingLMMs-Lab/open-r1-multimodal)](https://github.com/EvolvingLMMs-Lab/open-r1-multimodal)
- [MM-EUREKA (ModalMinds/MM-EUREKA)](https://github.com/ModalMinds/MM-EUREKA)  
- [VLM-R1 (om-ai-lab/VLM-R1)](https://github.com/om-ai-lab/VLM-R1)

We thank the authors of these projects for their valuable contributions to the community.

---

## 📊 Dataset

We use a high-quality medical reasoning dataset:

**📁 Dataset Name:** [GMAI-Reasoning10K](https://huggingface.co/datasets/General-Medical-AI/GMAI-Reasoning10K)  
**📄 Format:** JSONL  
**📷 Modalities:** X-ray, CT, MRI, OCT, Ultrasound, etc.  
**🔢 Samples:** 10,000 high-quality multiple-choice questions designed for reinforcement learning training     
**📚 Source:** Aggregated from 95 public medical datasets (e.g., Kaggle, GrandChallenge)

---


## 📜 Citation

If you find our work helpful, please consider citing our paper:

```bibtex
@article{su2025gmai,
  title={Gmai-vl-r1: Harnessing reinforcement learning for multimodal medical reasoning},
  author={Su, Yanzhou and Li, Tianbin and Liu, Jiyao and Ma, Chenglong and Ning, Junzhi and Tang, Cheng and Ju, Sibo and Ye, Jin and Chen, Pengcheng and Hu, Ming and others},
  journal={arXiv preprint arXiv:2504.01886},
  year={2025}
}
