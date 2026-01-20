# Common Test I – Multi-Class Classification (DeepLense)

## Task
Multi-class classification of strong gravitational lensing images into:
- **no** – no substructure  
- **sphere** – subhalo (CDM-like) substructure  
- **vort** – vortex-like substructure  

## Dataset
Provided by **ML4Sci (DeepLense)**.  
Images are stored as `.npy` arrays and normalized using min–max normalization.

## Approach
- ResNet-18 with transfer learning
- Data augmentation to avoid memorization
- Mixed precision training (AMP)
- Learning rate scheduling
- Early stopping
- ROC–AUC evaluation (One-vs-Rest)
- Grad-CAM explainability

## Results
- **Validation Accuracy:** ~97%  
- **ROC–AUC:** ~0.99 per class  

## Files
- `Common_Test_I_Classification.ipynb` – Full training & evaluation pipeline  
- `best_model.pth` – Trained model weights  

## Trained Model Weights (Backup)
If the model file is not accessible directly from GitHub, it can also be downloaded from:

🔗 **Google Drive:**  
👉 https://drive.google.com/file/d/107mx_Vv5q484pdFvvZj8alSuSAyqR4lc/view?usp=sharing


pip install -r requirements.txt
jupyter notebook

Author

Salman A — GSoC 2025 Applicant




## 📗 **Main Repository README.md (UPDATED)**


# DeepLense – GSoC 2025 Evaluation

This repository contains my solutions for the **ML4Sci DeepLense GSoC 2025 evaluation tests**.

## Repository Structure


DeepLense-GSoC-2025/
│
├── Common_Test_I/
│ ├── Common_Test_I_Classification.ipynb
│ ├── best_model.pth
│ ├── requirements.txt
│ └── README.md
│
├── Specific_Test_II/
│
└── README.md


## Completed
✅ **Common Test I – Multi-Class Classification**

- Multi-class classification of strong lensing images  
- ROC–AUC, Grad-CAM, learning curves, and confusion matrix included  
- Validation accuracy ≈ **97%**

📦 **Model weights (backup link):**  
👉https://drive.google.com/file/d/107mx_Vv5q484pdFvvZj8alSuSAyqR4lc/view?usp=sharing

## In Progress
🔄 **Specific Test II – Lens Finding**

## Author
**Salman A**  
GSoC 2025 Applicant – ML4Sci (DeepLense)
