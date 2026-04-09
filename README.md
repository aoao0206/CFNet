# CFNet: Cross-Modal Data Augmentation Empowered Fuzzy Neural Network for Spectral Fluctuation

This repository provides the implementation and dataset for our work on improving spectral repeatability using cross-modal data augmentation and fuzzy neural networks.

---

## 📌 Overview

Spectral fluctuation significantly affects the repeatability of spectroscopic techniques such as LIBS (Laser-Induced Breakdown Spectroscopy).  

To address this issue, we propose **CFNet**, a framework that integrates:

- Cross-modal data augmentation (image–spectrum dual modality)
- Fuzzy neural networks (FNN) for uncertainty modeling
- Deep learning for feature extraction and fusion

This approach effectively improves robustness against spectral variability and achieves over **91% accuracy across multiple independent experiments** :contentReference[oaicite:0]{index=0}.

---

## 📂 Dataset (Augmented Data)

The cross-modal augmented dataset used in this work is available at:

- Link: https://pan.baidu.com/s/1MRAE5BGYMiBpDU97z1YWKw  
- Password: `hust`

The dataset includes:
- Element hyperspectral images (image modality)
- Point spectra (spectral modality)

---

## 📄 Paper

- Journal: *Knowledge-Based Systems (2024)*  
- Link: https://www.sciencedirect.com/science/article/pii/S0950705124010840  

---

## 📖 Paper Interpretation (Chinese)

- Link: https://mp.weixin.qq.com/s/bwSoO7UCDEqkP7igxgLFpQ  

---

## 🚀 Key Contributions

- Propose a **cross-modal data augmentation method** to model spectral fluctuation  
- Expand single spectrum modality into **image-spectrum dual modality**  
- Introduce **CFNet**, combining fuzzy logic and neural networks  
- Allow spectra to belong to **multiple categories with different membership degrees**  
- Validate performance via **multi-day blind experiments**

---

## 🧠 Method Highlights

- Transform spectral data:
  - From single spectrum → dual modality (image + spectrum)
- Extract features:
  - Spatial distribution (image)
  - Spectral waveform (spectrum)
- Apply:
  - Fuzzy logic for uncertainty modeling
  - Deep learning for feature extraction
- Fuse:
  - Image features + spectrum features → final prediction

---

## 📊 Applications

- LIBS repeatability enhancement  
- Spectral classification under fluctuation  
- Potential extensions:
  - Raman spectroscopy  
  - Infrared spectroscopy  
  - Chemical and biomedical analysis  

---

## 📌 Citation

If you use this code or dataset, please cite the following papers:

### 🔹 OPGM (this work)
```bibtex
@article{opgm_libs,
  title={Optical Property-Guided Spectral Line Screening Method for LIBS Analysis},
  author={Gong, Aojun and Huang, Liming and Wang, Haozhe and Zhang, Deng and Hu, Zhenlin and Yu, Yuan and Guo, Lianbo},
  journal={Talanta},
  year={2025}
}
