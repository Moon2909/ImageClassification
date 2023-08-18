# ImageClassification
**MULTI-CLASS CHEST X-RAY IMAGE CLASSIFICATION OF LUNG DISEASES INCLUDING COVID-19**

Ho Thanh Duy Khanh†, Nguyen Thi Nguyet†, Nguyen Thanh Nhan†, Ngo Thi Phuc† and Nguyen Thi Phuong Thao†

**†** VNUHCM - University of Information Technology, Viet Nam.

Contributing authors: [20521445, 20521689, 20521701, 20521765, 20521936]@gm.uit.edu.vn

## Abstract
Accurate classification of lung diseases from chest X-ray images is essential in the process of diagnosing and treating illnesses. This study focuses on the multi-label classification of chest X-ray images related to lung diseases, including COVID-19. Machine learning models used in the study include Support Vector Machines (SVM), Random Forest, eXtreme Gradient Boosting (XGBoost), Multilayer Perceptron (MLP), and Convolutional Neural Networks (ConvNet). Each model has its own advantages and limitations, and combining the use of multiple models enhances the accuracy of classification. In addition, the study also experiments with various data balancing methods on the dataset to ensure that the model is not biased towards a large number of more important labels. Data balancing may involve adjusting the sample ratio between labels or using data re-balancing techniques. The results of the study contribute to providing an important diagnostic and treatment tool for lung diseases from chest X-ray images. Accurate classification of lung diseases from chest X-ray images assists healthcare professionals in making accurate and prompt treatment decisions, reducing time and effort in the diagnosis process.

## Methods
Support vector machines (SVM), Random Forest, eXtreme Gradient Boosting (XGBoost), Multilayer Perceptron (MLP), Convolutional Neural Network (CNN)

## Dataset
[Link Kaggle](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database)

![Dataset](https://github.com/Moon2909/ImageClassification/blob/main/dataset.png)

## Result
- **Classification results on 6 models**
![Result1a](https://github.com/Moon2909/ImageClassification/blob/main/Result1a.png)

![Result1b](https://github.com/Moon2909/ImageClassification/blob/main/Result1b.png)


- **Classification results on 6 models when using data balance methods (Measurement F1-score and Accuracy)**


![Result2](https://github.com/Moon2909/ImageClassification/blob/main/Result2.png)
