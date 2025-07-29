---
license: mit
language:
- en
base_model:
- Salesforce/blip-image-captioning-base
pipeline_tag: image-to-text
---
# 🏙️ BLIP Image Captioning for Municipality Use (Graduation Project)

This is a fine-tuned version of [Salesforce's BLIP base model](https://huggingface.co/Salesforce/blip-image-captioning-base), customized for generating captions on images related to street infrastructure and urban environments.  
The model was developed as part of a **Graduation Project** at the College of Information Systems.

---

## 🎓 Graduation Project Information

- **Project Title:** Smart Captioning for Urban Monitoring Using AI  
- **Student Name:** Saja  
- **University Major:** Information Systems  
- **Semester:** Final Year – Graduation Project 1  
- **Purpose:** This model aims to assist municipalities in automatically generating descriptive captions for street and infrastructure images using AI.

---

## 🧠 Model Overview

- **Base Model:** [Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)
- **Architecture:** BLIP (Bootstrapped Language Image Pretraining)
- **Task:** Image Captioning (with a focus on municipality-related data)

---

## 🏙️ Dataset

This model was fine-tuned on a **custom dataset** consisting of images captured in urban environments (e.g., roads, signs, sidewalks) for the purpose of city infrastructure monitoring.

> ⚠️ The dataset is not publicly released due to privacy and data ownership considerations.

---

## ✅ Intended Use

This model is designed for:

- Generating captions for street-level and city infrastructure images.
- Assisting municipalities in monitoring, analyzing, and documenting visual data.

---

## ❌ Limitations

- May not generalize well to domains outside of urban/street imagery.
- Captions might be biased by the dataset or lack context in unfamiliar scenes.
- Does not include object detection – focuses on captioning only.

---

## 📜 License

- This model is released under the **MIT License**.
- It is based on the [Salesforce BLIP model](https://huggingface.co/Salesforce/blip-image-captioning-base), which is licensed under the **BSD-3-Clause License**.
- Please ensure appropriate credit is given to the original authors when using or redistributing this model.

---

## 🤝 Acknowledgements

- Special thanks to **Salesforce Research** for the original BLIP model.
- Developed as part of a university graduation project with guidance from faculty members.

---