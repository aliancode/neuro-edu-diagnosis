

# 🎓 EduStack: Reliable Student Dropout Prediction with Explainable AI

[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)]()
[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)]()

---

## 📌 Overview

EduStack is a **research-grade machine learning pipeline** designed to address the challenge of **student dropout prediction** in higher education. Unlike many existing studies, EduStack focuses on **reliability, fairness, and interpretability**:

✅ **Nested Cross-Validation** → prevents data leakage & over-optimistic results.
✅ **Probability Calibration** → makes dropout risk predictions trustworthy.
✅ **Explainability with SHAP** → shows which features (e.g., attendance, engagement) most influence predictions.
✅ **Reproducibility** → generates manifest.json, requirements.txt, and fixed random seeds for consistent results.

---

## 🚀 Installation

```bash
git clone https://github.com/username/EduStack.git
cd EduStack
pip install -r requirements.txt
```

---

## ⚡ Usage

Run training & evaluation with nested cross-validation:

```bash
python main.py --config config.yaml
```

Interpret the model with SHAP:

```bash
python explain.py --model saved_model.pkl
```

---


---

## 📜 Citation

If you use **EduStack** in your research, please cite:

```bibtex
@article{edustack2025,
  title={EduStack: Reliable and Explainable Machine Learning for Student Dropout Prediction},
  author={REBBAH SIHAM},
  year={2025}
}
```

---

## 🤝 Contributing

Pull requests are welcome! Please check [issues](https://github.com/username/EduStack/issues).

---

## 📧 Contact

For questions or collaborations, reach out at: **[rebbahsiham0@gmail.com]**

---
