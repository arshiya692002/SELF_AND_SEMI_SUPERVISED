# SELF_AND_SEMI_SUPERVISED

Systematic benchmarking of Self-Supervised (DINO, SwAV) and Semi-Supervised (SimMatchV2) methods for medical image classification.

This project is a part of our **major B.Tech project** at the **Indian Institute of Information Technology, Allahabad**, under the supervision of **Dr. Sonali Agarwal**. It presents an empirical comparison of advanced learning strategies for scenarios with limited labeled medical data, using TissueMNIST and PathMNIST datasets.

---

##  Project Objectives

- Evaluate self-supervised vs. semi-supervised learning approaches on medical imaging datasets.
- Improve classification accuracy under limited-label settings.
- Optimize model configurations for practical healthcare scenarios.

---

##  Models Implemented

### Self-Supervised Learning

- **DINO**: Uses a student-teacher architecture with exponential moving average updates.
- **SwAV**: Learns representations by clustering and swapping assignments between augmented views.

### Semi-Supervised Learning

- **SimMatchV2**: Combines classification, consistency regularization, and similarity-based alignment.

---

##  Datasets Used

- **TissueMNIST**: Histological colorectal cancer tissue images.
- **PathMNIST**: Pathology images from colorectal cancer studies.

>  These datasets are not included in the repository due to GitHub's 100 MB size limit.

---

## Dataset Download Instructions

Due to GitHub’s file size limits, datasets are not included in this repository.

Please download the following files and place them inside a `dataset/` folder at the root of this project:

- [Download TissueMNIST (tissuemnist.npz)](https://zenodo.org/record/6496656/files/tissuemnist.npz?download=1)
- [Download PathMNIST (pathmnist.npz)](https://zenodo.org/record/6496656/files/pathmnist.npz?download=1)
---

## Performance Comparison

| Dataset      | Model Type        | Model        | Base Accuracy (%) | Improved Accuracy (%) | Gain   |
|--------------|-------------------|--------------|--------------------|------------------------|--------|
| TissueMNIST  | Semi-Supervised   | SimMatchV2   | 80.00              | 81.50                  | +1.50  |
| TissueMNIST  | Self-Supervised   | DINO         | 82.52              | 87.00                  | +4.48  |
| TissueMNIST  | Self-Supervised   | SwAV         | 77.90              | 79.90                  | +2.00  |
| PathMNIST    | Semi-Supervised   | SimMatchV2   | 79.11              | 80.94                  | +1.83  |
| PathMNIST    | Self-Supervised   | DINO         | 82.52              | 88.00                  | +5.48  |
| PathMNIST    | Self-Supervised   | SwAV         | 77.90              | 78.74                  | +0.84  |

---

##  Skills Demonstrated

- Deep Learning: Self-Supervised and Semi-Supervised Techniques
- PyTorch-based model development
- Image preprocessing and augmentation
- Visualization and benchmarking
- Research implementation and evaluation

---
---

## Documentation

- [docs/thesis_report.pdf](docs/thesis_report.pdf) — Final project report  
- [docs/ppt.pptx](docs/ppt.pptx) — Project presentation slides

---

## Team Members (Major Project)

- **Arshiya Chutke**  
- **Preeti**  
- **Girisha Vashisht**

---

## Supervisor

- **Dr. Sonali Agarwal**, IIIT Allahabad

---

## License

This project is released under the **MIT License**.
