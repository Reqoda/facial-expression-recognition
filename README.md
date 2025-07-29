# Facial Expression Recognition using PCA & LDA

This project was developed as part of the "Introduction to Machine Learning" course.  
It focuses on classifying facial expressions from grayscale images using dimensionality reduction and classical machine learning algorithms.

## 📊 Dataset
- **Name:** FER2013 (Facial Expression Recognition)
- **Format:** 48x48 grayscale images
- **Classes:** Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- Dataset source: [Kaggle - FER2013](https://www.kaggle.com/datasets/msambare/fer2013)

## 🧪 Techniques Used
- **PCA** (Principal Component Analysis) – manual implementation
- **LDA** (Linear Discriminant Analysis) – manual implementation
- **Classifiers:**
  - Logistic Regression
  - k-Nearest Neighbors (k=1, 3, 5...)
  - Random Forest

## 🚀 Results
| Model              | PCA Accuracy | LDA Accuracy |
|-------------------|--------------|--------------|
| Logistic Regression | 37.8%       | 34.5%        |
| 3-NN               | 34.6%       | —            |
| Random Forest      | **42.4%**    | 37.1%        |

- Highest performance: **PCA + Random Forest (42.4%)**
- Notable confusion between: *Fear vs. Disgust*, *Fear vs. Neutral*

## 📁 Contents
- `notebooks/`: Source code (Jupyter Notebook)
- `presentation/`: Slides used for project presentation
- `requirements.txt`: Dependencies

## 🔍 Key Takeaways
- Learned how to manually implement PCA & LDA
- Understood the effect of k in k-NN
- Gained hands-on experience with image classification and model evaluation

---

_This project helped me strengthen my understanding of classical ML workflows and dimensionality reduction techniques._
