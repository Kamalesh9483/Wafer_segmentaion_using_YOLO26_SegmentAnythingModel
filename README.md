# Silicon Wafer Detection & Segmentation  
## YOLO26 + SAM (Segment Anything Model)

## Overview

This project presents an end-to-end computer vision pipeline for **silicon wafer image analysis**, combining deep learning–based detection and segmentation.

The system integrates:

- A custom-trained YOLO26 segmentation model
- Automatic segmentation using Meta AI’s Segment Anything Model (SAM)
- Clear side-by-side visualization of segmentation outputs

The workflow starts from dataset preparation and YOLO training, and progresses to comparative segmentation using YOLO and SAM.

---

## Project Versions

### Version 1 — Integrated YOLO + SAM Pipeline  
📄 **Notebook:** `YOLO_26_SAM_Segmentation.ipynb`

Version 1 implements an integrated pipeline where:

- YOLO segmentation detects wafer regions
- SAM is used to refine or augment segmentation
- Combined outputs are visualized in a unified workflow

This version focuses on exploring collaborative segmentation between YOLO and SAM.

---

### Version 2 — Independent YOLO & SAM Predictions  
📄 **Notebook:** `YOLO_26_SAM_Segmentation_V2.ipynb`

Version 2 separates the two models and evaluates them independently and use both overlapping region for inference.

## Dataset

**Source:** Roboflow Universe  
Silicon Wafer Dataset:  
https://universe.roboflow.com/test-c3vhv/silicon-wafer-icwiy

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/072fccfc-187d-43a6-92e1-7823916c3dbd" />

Results Version 1:
<img width="1582" height="812" alt="Image_segmentation_3" src="https://github.com/user-attachments/assets/7ccffe0e-0fcd-4bd2-ae8d-1d9d3229ddc0" />
<img width="1582" height="812" alt="Image_segmentation_1" src="https://github.com/user-attachments/assets/4435af6a-fcf3-43fe-989f-ca97613f32eb" />
<img width="1440" height="790" alt="Image_segmentation_2" src="https://github.com/user-attachments/assets/a908a81b-4200-4b27-a61a-2204dd313904" />

Results Version 2:
<img width="1440" height="418" alt="image" src="https://github.com/user-attachments/assets/455527b2-8311-41a7-9ac4-3d1ff321d6ca" />
<img width="1440" height="418" alt="image" src="https://github.com/user-attachments/assets/de97ab0d-2c95-4202-a290-c94eeec323d1" />



