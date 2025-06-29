# 🎙️ Classification of Arabic /r/ Sound Pronunciation Disorders

<div align="center">
  <img src="assets/system_architecture.png" width="600" alt="System Architecture">
  <br>
  <img src="View%20Result.gif" width="800" alt="Demo Animation">
</div>

## 📝 Table of Contents
- [Project Overview](#-project-overview)
- [Demo](#-demo)
- [Team Members](#-team-members)
- [Methodology](#-methodology)
- [Results](#-results)
- [Installation](#-installation)
- [How to Run](#-how-to-run)
- [Dataset](#-dataset)

## 🌟 Project Overview
نظام ذكاء اصطناعي لتصنيف اضطرابات نطق حرف الراء العربي (/r/) في بداية الكلمات إلى 5 فئات:

1. **Distortion** (تشويه)
2. **Deletion** (حذف)
3. **Substitution with /gh/** (استبدال بالغين)
4. **Substitution with /l/** (استبدال باللام)
5. **Normal** (النطق الصحيح)

## 🎥 Demo
<div align="center">
  <img src="View%20Result.gif" width="800" alt="System Demo">
</div>

## 👥 Team Members
- [ Leyan Buirat ] (https://github.com/layanbuirat)(1211439)
- [ Noor Shamali ] (1200016)  
- [Dana Ghnimat ] (1200031)  
## 🔬 Methodology
### 📊 Feature Extraction
- معاملات ميل-التردد (MFCCs)
- معاملات دلتا ودلتا-دلتا
- معالجة الإشارة الصوتية باستخدام `librosa`

### 🤖 Models
- Gaussian Mixture Models (GMM)
- Support Vector Machines (SVM)
- Random Forest

## 📈 Results
| Model | Accuracy | Precision | Recall |
|-------|----------|-----------|--------|
| SVM (RBF) | 72.4% | 0.71 | 0.72 |
| GMM | 68.2% | 0.67 | 0.68 |

## 💻 Installation
```bash
git clone https://github.com/layanbuirat/Classification-of-Arabic-r-Sound-Pronunciation-Disorders.git
cd Classification-of-Arabic-r-Sound-Pronunciation-Disorders
pip install -r requirements.txt

🚀 How to Run
jupyter notebook Spoken_Course_project.ipynb

📁 Dataset
Download Dataset

📚 Documentation
Full Report

Presentation Slides

<p align="center"> <img src="https://img.shields.io/badge/Made%20with-Python-blue?logo=python"> <img src="https://img.shields.io/badge/License-MIT-green"> </p> ```
