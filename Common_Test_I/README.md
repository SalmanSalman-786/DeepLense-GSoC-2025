# Common Test I – Multi-Class Classification (DeepLense)

## Task
Multi-class classification of strong gravitational lensing images into:
- no substructure
- subhalo (sphere)
- vortex substructure

## Dataset
Provided by ML4Sci (DeepLense).  
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
- Validation Accuracy: **~97%**
- ROC–AUC: **~0.99 per class**

## Files
- `Common_Test_I_Classification.ipynb` – Full training & evaluation pipeline
- `best_model.pth` – Trained model weights

## How to Run

pip install -r requirements.txt
jupyter notebook
Author
Salman — GSoC 2025 Applicant



# 📌 Step 7: Main Repository README

Create:
README.md


# DeepLense – GSoC 2025 Evaluation

This repository contains my solutions for the **ML4Sci DeepLense GSoC 2025 evaluation tests**.

## Completed
- ✅ Common Test I – Multi-Class Classification

## In Progress
- 🔄 Specific Test II – Lens Finding

## Author
Salman  
Email submission sent to **ml4-sci@cern.ch**