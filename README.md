# Classification of Arabic /r/ Sound Pronunciation Disorders

## Project Description  
This project aims to build a system capable of classifying pronunciation disorders of the Arabic /r/ sound (IPA: [r]) when it appears at the beginning of words. The disorders are categorized into four classes:  
1. **Distortion**  
2. **Deletion**  
3. **Substitution with /gh/**  
4. **Substitution with /l/**  
5. **Normal (correct) pronunciation**  

The project leverages speech signal processing and machine learning techniques to achieve this goal.  

## Team Members  
- [ Leyan Buirat ] (1211439)
- [ Noor Shamali ] (1200016)  
- [Dana Ghnimat ] (1200031)  
- ## 🎥 Demo
<div align="center">
  <img src="C:\Users\hp\Desktop\فصل ثني سنه رابعه\spoken project\View Result.gif" width="1000" alt="System Demo">
</div>

## Requirements  
- Python 3.x  
- Required libraries:  
  - `librosa`  
  - `scikit-learn`  
  - `numpy`  
  - `matplotlib`  
  - `pandas`  

## Implementation Steps  
1. **Download the Dataset**:  
   The audio dataset is available via [Google Drive](https://drive.google.com/drive/folders/13PPVmCAlbzGkzOvQxaB3NTcfUkG6GB?usp=sharing).  

2. **Feature Extraction**:  
   Mel-Frequency Cepstral Coefficients (MFCCs) along with delta and delta-delta coefficients are extracted using `librosa` to capture spectral and temporal features.  

3. **Model Training**:  
   - **Gaussian Mixture Models (GMMs)** and **Support Vector Machines (SVMs)** are trained for classification.  
   - Hyperparameters are tuned for optimal performance.  

4. **Evaluation**:  
   Performance metrics include:  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix  

## Results  
- The best-performing model achieved **72.4% accuracy** using an SVM with an RBF kernel.  
- Detailed results are available in the project report.  

## How to Run  
1. Clone the repository:  
   ```bash  
   git clone [repository-link]  
