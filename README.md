# TensorFlow Image Classification Project

**Course:** IBM AI Engineering Professional Certificate - Deep Learning with TensorFlow  
**Author:** Son Nguyen  
**Date:** November 2, 2025

---

## 📋 Project Overview

This project implements **image classification using TensorFlow and Keras** with transfer learning. The assignment covers:

1. Feature extraction using pre-trained models
2. Fine-tuning deep learning models
3. Model evaluation and visualization
4. Image prediction and classification

---

## 📁 Project Structure

```
tensorflow-image-classification/
│
├── notebooks/
│   └── Image_Classification_Project.ipynb    # Main notebook with all tasks
│
├── screenshots/                                # Auto-generated screenshots
│   ├── tensorflow_version.png                 # Task 1: TensorFlow version
│   ├── test_generator.png                     # Task 2: Test generator
│   ├── train_generator_len.png                # Task 3: Train generator length
│   ├── model_summary.png                      # Task 4: Model summary
│   ├── model_compile.png                      # Task 5: Model compile code
│   ├── plot_accuracy_curve.png                # Task 6: Accuracy curves
│   ├── plot_loss_curve.png                    # Task 7: Loss curves
│   ├── plot_finetune_model.png                # Task 8: Fine-tune accuracy
│   ├── extract_features_model.png             # Task 9: Extract features prediction
│   └── finetuned_model.png                    # Task 10: Fine-tuned prediction
│
├── data/                                       # Dataset (auto-downloaded)
│   ├── train/
│   ├── validation/
│   └── test/
│
├── requirements.txt                            # Python dependencies
└── README.md                                   # This file
```

---

## 🛠️ Setup Instructions

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Run Notebook

```bash
jupyter notebook notebooks/Image_Classification_Project.ipynb
```

### 3. Execute All Cells

Run all cells in order - screenshots will be automatically saved to `screenshots/` folder.

---

## 📊 Assignment Tasks

| Task | Description | Points | Screenshot File |
|------|-------------|--------|-----------------|
| 1 | Print TensorFlow version | 2 | `tensorflow_version.png` |
| 2 | Create test_generator | 2 | `test_generator.png` |
| 3 | Print train_generator length | 2 | `train_generator_len.png` |
| 4 | Print model summary | 2 | `model_summary.png` |
| 5 | Compile model | 2 | `model_compile.png` |
| 6 | Plot accuracy curves (extract) | 2 | `plot_accuracy_curve.png` |
| 7 | Plot loss curves (fine-tune) | 2 | `plot_loss_curve.png` |
| 8 | Plot accuracy curves (fine-tune) | 2 | `plot_finetune_model.png` |
| 9 | Plot test image (extract model) | 2 | `extract_features_model.png` |
| 10 | Plot test image (fine-tuned) | 4 | `finetuned_model.png` |
| **Total** | | **22** | **10 screenshots** |

**Passing Score:** 70% (15.4/22 points)

---

## ✅ Submission Checklist

- [ ] All 10 screenshots generated in `screenshots/` folder
- [ ] All screenshots named exactly as required
- [ ] All tasks completed with correct output
- [ ] Code executes without errors
- [ ] Screenshots show both code AND output
- [ ] Image predictions show correct class labels

---

## 🎯 Expected Results

- **Extract Features Model Accuracy:** ~85-90%
- **Fine-Tuned Model Accuracy:** ~92-95%
- **Training Time:** 10-15 minutes per model
- **Dataset:** Cats vs Dogs or similar binary classification

---

## 📝 Notes

- All screenshots are automatically generated when running the notebook
- Screenshots include both code cells and output for grading
- Models use transfer learning with MobileNetV2 or ResNet50
- Data augmentation applied to training set

---

## 👤 Author

**Son Nguyen**  
IBM AI Engineering Professional Certificate  
Coursera - November 2025

---

## 📄 Honor Code

I, Son Nguyen, understand that submitting work that isn't my own may result in permanent failure of this course or deactivation of my Coursera account.
