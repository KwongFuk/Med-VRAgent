
# Med-VRAgent: Medical Visual Reasoning-Enhanced Agent  (EMNLP 2025)

This repository contains the implementation of **Med-VRAgent**, a novel framework for enhancing **medical visual reasoning** with multimodal large models.  
Med-VRAgent integrates **Visual Guidance**, **Retrieval-Augmented Reflection (RAR)**, and **Monte Carlo Tree Search (MCTS)** into a teacher–student–assessor architecture, significantly improving diagnostic reasoning, localization, and report generation.

---

## 🚀 Features
- **Teacher–Student–Assessor framework** for structured reasoning.
- **Visual Token Edit (VTE)** for fine-grained regional perception.
- **Retrieval-Augmented Reflection (RAR)** for knowledge-grounded refinement.
- **Monte Carlo Tree Search (MCTS)** for optimized reasoning paths.
- Supports **medical VQA** and **report generation** tasks.

---

## 📦 Requirements

- Python 3.9+
- PyTorch 2.0+
- HuggingFace Transformers
- PEFT + TRL (for PPO fine-tuning)
- FAISS (for retrieval)
- Grounding DINO (for ROI extraction)

Install dependencies:

```bash
pip install -r requirements.txt
