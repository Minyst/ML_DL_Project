# 🎓 Data Analyst Portfolio

Welcome to my Data Analyst portfolio! Here you can find my projects, skills, and contributions to the field of data analysis.

---

## 📊 Projects

### Project 1: Credit Card Fraud Detection

**Objective** <br/> 
To determine which model performs best when data is reduced or augmented.

**Technologies Used** <br/>
- Dimensionality Reduction: PCA, tSNE, UMAP
- Dimensionality Augmentation: SMOTE, BorderLineSMOTE, ADASYN
- Machine Learning Models: RandomForest, XGBoost, CatBoost, LightGBM
- Deep Learning Models: TensorFlow, Pytorch 

**Key Results** <br/>
To compare whether dimensionality reduction or augmentation improves model performance, <br/>
I used various machine learning and deep learning models. <br/>
As a result, I was able to create a ranking table showing which method and model combination yielded the best performance. <br/>
The accuracy was similar, so I ranked them based on the ROC_AUC_SCORE.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio/tree/main/Credit%20Card%20Fraud%20Detection

---

### Project 2: YOLOv10 Pretrained vs Custom

**Objective** <br/>
To compare which performs better between the pretrained and custom YOLOv10 models.

**Technologies Used** <br/>
- Model: YOLOv10
- Package: ultralytics, supervision, cv2

**Key Results** <br/>
After capturing the video and creating multiple frames, <br/>
each frame was trained with the model, and then these frames were reassembled into a single video. <br/>
For the pretrained model, predictions were made directly using the model. <br/>
For the custom model, pre-prepared data was trained using the original YOLOv10 weights, <br/>
and the best weights obtained were selected as the final weights for the model, which was then used for predictions. <br/>
This process is similar to a relay race.

When comparing the pretrained and custom models, there was a significant difference. <br/>
The custom model, which was provided with images of various classes consistently, had a broader prediction range than the automatically recognizing pretrained model. <br/>
However, its accuracy was much lower compared to the pretrained model.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio/tree/main/YOLO

---

### Project 3: Detectron2 Pretrained vs Custom

**Objective** <br/>
To compare which performs better between the pretrained and custom Detectron2 models.

**Technologies Used** <br/>
- Model: Detectron2
- Package: detectron2, cv2

**Key Results** <br/>
Detectron2 is almost identical to YOLOv10, but there are two key differences. <br/>
First, Detectron2 uses Faster RCNN weights, unlike YOLOv10. <br/>
Second, while YOLOv10 shows some differences in results between pretrained and custom models, <br/>
Detectron2 exhibits no noticeable differences."

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio/tree/main/Detectron

---

### Project 4: AI Cover - RVC

**Objective** <br/>
Using the RVC model to make one singer's voice sing another singer's song.

**Technologies Used** <br/>
- Model: RVC

**Key Results** <br/>
This project can be explained in five steps. 
First, split the downloaded YouTube music into vocals and background music. 
Second, slice the vocals into multiple segments to enhance the model's learning. 
Third, download the RVC_pretrained model. 
Fourth, train the model. 
Fifth, generate a music file where the singer performs a different song.

I was amazed at how natural the generated music sounded. 
Detailed adjustments can be made, and having an expert involved could further improve the synchronization and overall quality.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio/tree/main/AI%20Cover

---

### Project 5: CNN - CIFAR-10

**Objective** <br/>
Using CIFAR-10 data, build a complex CNN with TensorFlow and PyTorch.

**Technologies Used** <br/>
- Tensorflow, Pytorch

**Key Results** <br/>
All processes of the CNN with TensorFlow and PyTorch are included: Data Augmentation, Padding, Batch Normalization, Pooling, Dropout, Flatten.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio/tree/main/CNN

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
