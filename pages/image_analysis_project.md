---
layout: single
title: "Image Analysis Project"
permalink: /image_analysis_project/
author_profile: true

feature_row3:
  - image_path: assets/images/image_analysis.jpg
    alt: "Image Analysis Project"
    excerpt: "Brain cell counting using CellProfiler."
    url: "/image_analysis_project/"
    btn_class: "btn--inverse"
    btn_label: "View Project"
---

# 🧠 Image Analysis Project: Brain Cell Counting  

{% include feature_row id="feature_row3" type="left" %}

---

In this project, we used **CellProfiler** to quantify brain cells from microscopy images. This approach allowed high-throughput, automated, and reproducible cell counting.

### ✅ **Key Analysis Steps in CellProfiler:**
- Image Preprocessing using **ColorToGray** module.
- Applied filters:  
  - **EnhanceEdges**  
  - **GaussianFilter**  
  - **ErodeImage**  
  - **Closing**
- Identified primary objects (brain cells) for quantification.
- Exported data for statistical analysis.

---

### 📊 **Example Results:**
- Total cells detected: **1,245 cells per image** (average).
- Increased cell density observed in specific brain regions under experimental conditions.

---

You can learn more about [CellProfiler here](https://cellprofiler.org/).

