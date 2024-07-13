![image](https://github.com/user-attachments/assets/6058a7b1-46f0-4c60-abe4-07f87c6667d9)

# Rice Leaf Diseases Detection using CNN
Original Github Organization : https://github.com/Capstone-Project-Padi-Care

## Bangkit 2023 Capstone Project - C23-PS226 
- **M350DSX0169 - Ivan Tandella- Universitas Sumatera Utara - Machine Learning**
- **M350DSY0137 - Putri Yanti Nahampun - Universitas Sumatera Utara - Machine Learning**
- A350DKX4428 - Reinaldhy Suzeta Purba - Universitas Sumatera Utara- Mobile Development
- A163DSX2278 - Muhammad Khoirul Afwan - Universitas Dian Nuswantoro- Mobile Development
- C163DSX2962 - Royef Fahrezal Setya Ar anysah - Universitas Dian Nuswantoro - Cloud Computing
- C163DSX2963 - Muchamad Yudhistira - Universitas Dian Nuswantoro - Cloud Computing

## Background
Rice, a staple food for nearly half of the world's population, is cultivated across the globe, with Indonesia being a prime example. However, farmers and crop production professionals continua ly face numerous agricultural chalenges, including various rice diseases that have persisted over the centuries. These severe rice diseases can signi cantly impact yields, highlighting the need for a fast, automatic, inexpensive, and accurate method of disease detection in the eld of agroinformatics. 

Our project aims to address this need by developing a user-friendly and e cient application that utilizes image recognition technology to detect and control plant diseases. We strive to support farmers by providing comprehensive disease information, recommended solutions, and fertilizer suggestions to optimize disease management and prevention. Our team, possessing a deep understanding of agribusiness and a passion for sustainable agriculture, is commi ed to making a positive impact on farmer livelihoods, agricultural productivity, and global food security

## Machine Learning Work
As a machine learning team, we developed a CNN-based model to classify rice plant diseases using leaf images. We designed and trained a Convolutional Neural Network (CNN) architecture with TensorFlow to accurately detect various rice plant diseases. To enhance the model's accuracy and mitigate overfitting, we utilized image augmentation techniques. Additionally, we converted the trained model to TensorFlow.js for deployment on a cloud server.

### Dataset
The dataset we obtained is rice leaf image data from Kaggle with a total of 120 images consisting of 
- 40 images of brown spot
- 40 images of bacterial leaf blight disease
- 40 images of leaf smut disease

### Preprocessing
1. Splitting Data
   - 80% training data
   - 20% validation data
2. Data Augmentation
   - 40% rotation 
   - 20% width shift 
   - 20% height shift 
   - 20% shear 
   - 20% zoom
   - horizontal flip
![image](https://github.com/user-attachments/assets/f528f69d-a10f-4394-bc6d-682f4a0ca3e8)

### Model Architecture
![model json](https://github.com/user-attachments/assets/713cf978-0268-4151-82b8-a009cc788cef)

### Result
![image](https://github.com/user-attachments/assets/126aa36e-5132-4eb6-88a9-1892ddb1f1e2)


## Links
Original Github Organization : https://github.com/Capstone-Project-Padi-Care

Original dataset (Kaggle) : https://www.kaggle.com/datasets/vbookshelf/rice-leaf-diseases

Preprocessed Dataset : https://drive.google.com/file/d/1BlpYYR9u8dDaoJgmHmOixrRiQUN4Pbpi/view?usp=drive_link 


