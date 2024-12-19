# Baseline Matrix

## Overview
This baseline matrix is created to evaluate and compare the performance of the following models:

1. **Scratch Model**:
   - A YOLOv8 model trained from scratch using the annotated dataset with 1044 frames and 4 key custom object classes:
     - **Face**
     - **Logo**
     - **News-Ticker**
     - **Text**

2. **Pre-Trained Backbone**:
   - A YOLOv8 model with a frozen backbone (pre-trained on COCO) using the annotated dataset with 1044 frames and 4 key custom object classes:
     - **Face**
     - **Logo**
     - **News-Ticker**
     - **Text**

3. **Fine-Tuned Model**:
   - A YOLOv8 model trained using the annotated dataset with 1044 frames and 4 key custom object classes:
     - **Face**
     - **Logo**
     - **News-Ticker**
     - **Text**

---

## Why the Default YOLOv8n Baseline Is Not Usable
- The default YOLOv8n model pre-trained on COCO does **not include the classes of interest** (face, logo, news-ticker, text).
- However, it can still serve as a **reference for comparison**, helping to measure the custom models' performance.

---

## Dataset Details
- **Source**: Dataset created using Roboflow.
- **Frames Annotated**: 1044.
- **Classes**: 
  - **Face**
  - **Logo**
  - **News-Ticker**
  - **Text**

---
