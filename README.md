# Pneumonia Detection Using Transfer Learning RESNET50

* Pneumonia is a potentially serious respiratory illness that affects one or both lungs and is commonly caused by bacterial, viral, or fungal infections.
 
* Chest X-rays are widely used to identify pneumonia, but their interpretation requires a trained medical professional. Delays or inaccuracies in diagnosis often result in severe consequences, including loss of life.
* Advancements in computing power have made it feasible to create automated systems for pneumonia detection and treatment, which can be especially beneficial for patients in remote locations with limited access to healthcare services.
* In this project, we aim to identify the presence of pneumonia using chest X-ray images. 
* In this Web application, we used a Transfer Learning model [**RESNET50**](https://keras.io/api/applications/resnet/) for prediction

* This Web application is created and deployed in [**Streamlit**](https://streamlit.io/)

## ⏳ DataSet 

<img width="449" height="146" alt="image" src="https://github.com/user-attachments/assets/1751d916-48da-4716-9aa9-11599cd34a70" />

The normal chest X-ray (left panel) depicts clear lungs with no any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows). In contrast, viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

The dataset used in this study is organised into two folders containing .jpg images: one labelled “Normal,” which includes chest X-rays of healthy individuals, and the other labelled “Pneumonia,” which contains X-rays of patients diagnosed with pneumonia.

The chest X-ray images (anterior–posterior view) were collected from pediatric patients aged one to five years at the Guangzhou Women and Children’s Medical Centre. These scans were obtained as part of standard clinical procedures.

The above Dataset was taken from Kaggle: 
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data

## 📝 Project Architecture

### Machine Learning Pipeline Steps:

1. Data Acquisition – Sourced from Kaggle
2. Data Validation – Performed if required
3. Data Preprocessing & Feature Engineering – Completed
4. Model Development/Training – Completed
5. Model Performance Evaluation – Completed
6. Web Application Deployment – Completed
7. System Testing – Completed


## Dataset Details

* Dataset Name            : Chest X-Ray Images (Pneumonia)
* Number of Class         : 2
* Number/Size of Images   : Total  : 5856 (1.15 Gigabytes (GB))
                            * Training   : 5216 (1.07 Gigabyte (GB))
                            * Validation : 320  (42.8 Megabytes (MB))
                            * Testing    : 320  (35.4 Megabytes (MB))
a. Model Parameters:

* Machine Learning Library: Keras
* Base Model              : RESNET50 and Custom Deep Convolutional Neural Network
* Optimizers              : Adam
* Loss Function           : categorical_crossentropy

b. For Custom Deep Convolutional Neural Network : 
* Training Parameters:

* Batch Size              : 32
* steps_per_epoch         : len(train_generator)
* Number of Epochs        : 15

## 🖥️ Libraries Used

* Tensorflow
* Keras
* Scikit-learn
* Streamlit

## 🧑🏼‍💻 Contributors

1. Amulya Tandur
