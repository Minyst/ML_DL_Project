# 🎓 Data Analyst Portfolio

Welcome to my Data Analyst portfolio! Here you can find my projects, skills, and contributions to the field of data analysis.

---

## 📊 Projects

### Project 1: Credit Card Fraud Detection
**Objective**: To determine which model performs best when data is reduced or augmented.

**Technologies Used**:
- Dimensionality Reduction: PCA, tSNE, UMAP
- Dimensionality Augmentation: SMOTE, BorderLineSMOTE, ADASYN
- Machine Learning Models: RandomForest, XGBoost, CatBoost, LightGBM
- Deep Learning Models: TensorFlow, Pytorch 

**Key Results**:
To compare whether dimensionality reduction or augmentation improves model performance, 
I used various machine learning and deep learning models. 
As a result, I was able to create a ranking table showing which method and model combination yielded the best performance.
The accuracy was similar, so I ranked them based on the ROC_AUC_SCORE.
url: https://github.com/Minyst/ML_DL_Portfolio/tree/main/Credit%20Card%20Fraud%20Detection

---

### Project 2: YOLOv10 Pretrained vs Custom
**Objective**: To compare which performs better between the pretrained and custom YOLOv10 models.

**Technologies Used**:
- Model: YOLOv10
- Package: ultralytics, supervision, cv2

**Key Results**:
After capturing the video and creating multiple frames, 
each frame was trained with the model, and then these frames were reassembled into a single video. 
For the pretrained model, predictions were made directly using the model. 
For the custom model, pre-prepared data was trained using the original YOLOv10 weights, 
and the best weights obtained were selected as the final weights for the model, which was then used for predictions. 
This process is similar to a relay race.

When comparing the pretrained and custom models, there was a significant difference. 
The custom model, which was provided with images of various classes consistently, had a broader prediction range than the automatically recognizing pretrained model. 
However, its accuracy was much lower compared to the pretrained model.

---

## 📈 Skills

- **Programming Languages**: Python, SQL
- **Data Visualization**: Matplotlib, Seaborn, Tableau
- **Machine Learning & Deep Learning**: Scikit-Learn, TensorFlow, Pytorch
- **Data Manipulation**: Pandas, NumPy
- **Databases**: MySQL
- **Tools**: Jupyter Notebook

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

---

## 📫 Contact

Feel free to reach out for inquiries or collaboration opportunities:

- **Email**: [username@example.com](mailto:username@example.com)
- **LinkedIn**: [linkedin.com/in/username](https://www.linkedin.com/in/username)
- **GitHub**: [github.com/username](https://github.com/username)
