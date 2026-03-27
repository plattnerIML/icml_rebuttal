# Anonymous Submission: Make-a-Shape Meltdown Mitigation

This repository contains the source code and qualitative results for our proposed mitigation of topological meltdown in point-cloud-to-mesh diffusion.

> **Note to Reviewers:** For a comprehensive interactive gallery of hundreds of shapes, please refer to the `gallery.html` file included in our **Supplementary ZIP** on the conference submission portal.

---

## 🚀 Qualitative Overview

Below is a representative comparison showing the baseline model's failure (meltdown) vs. our recovery method (PowerRemap) on a complex geometry.

![Method Comparison](assets/psnr_curve_hash_grid__silu__sgd.png)

*Figure 1: (Left) Ground Truth mesh. (Middle) Baseline output showing disconnected components (α=ε). (Right) Our PowerRemap recovery (γ=1.05) restoring a single manifold component.*

---

## 🛠️ Quick Start

### Installation
```bash
pip install -r requirements.txt
