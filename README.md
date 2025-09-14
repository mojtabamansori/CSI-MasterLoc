# CSI-MasterLoc 🚀
Indoor Localization using WiFi CSI Data  
A project by **Masterminds Team**

---

## 📌 Project Overview
**CSI-MasterLoc** is an open-source project focused on **indoor localization** using **WiFi Channel State Information (CSI)** data.  
Our goal is to leverage CSI signals to estimate the position of devices inside buildings with high accuracy.

---

## 📊 Dataset
This repository contains our custom **CSI dataset** collected specifically for indoor positioning experiments.  
- Format: `.csv` / `.mat` (adjust based on your actual files)
- Includes raw CSI readings + ground truth location labels.

> 📁 Dataset is stored inside the [`/data`](data) folder.

---

## 💻 Code Structure
The project will include:
- `data/` → CSI dataset files  
- `src/` → Data preprocessing & feature extraction code  
- `models/` → Machine learning / deep learning models for localization  
- `notebooks/` → Jupyter notebooks for analysis & experiments  

---

## ⚡ Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Masterminds-Team/CSI-MasterLoc.git
   cd CSI-MasterLoc
