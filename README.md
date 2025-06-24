# About the Project

The detection of brain tumors is a critical task in the field of medical imaging, as it can significantly impact patient outcomes. However, accurately detecting brain tumors can be challenging due to the complex nature of the human brain and the variability in the appearance of tumors. Therefore, there is a need for an automated and accurate brain tumor detection system that can assist healthcare professionals in diagnosing brain tumors.

The goal of this project is to develop a brain tumor detection system that can accurately classify brain scans as either containing a tumor or not. We aim to create a model that can handle the variability in brain scans and provide accurate results in a timely manner. To achieve our goal, we will use a dataset consisting of brain scan images. We will preprocess and augment the dataset to increase its size and variability. We will then use a pre-trained ResUnet model and CNN## to train the data and generate predictions for new images.

After training, we evaluated the performance of the model on a separate test set. We obtained an accuracy of 99% on the test set, which indicates that the model is able to accurately classify brain scans as either having a tumor or not.We aim to improve the accuracy and speed of brain tumor diagnosis, ultimately leading to better patient outcomes.

## Dataset
We're going to use an open data source from Kaggle: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation



## Some Demo Output

## 1. interactive bar chart
![IMG_20250624_120511](https://github.com/user-attachments/assets/9c255e0b-f962-4231-b4c0-9a40e00c7558)


## 2. Brain mask
![IMG_20250624_120531](https://github.com/user-attachments/assets/264120a6-e2b9-4a12-8d53-2b71c965c85e)

## 3. randomly selected (1) MRI scan images from only sick patients followed by (2) corresponding mask, (3) both MRI image and the corresponding mask (in blue color) on top of each other
![IMG_20250624_120604](https://github.com/user-attachments/assets/e4a8b77f-9c1d-48f8-9a50-d0f7c64eae43)


## 4. Predicted data
![IMG_20250624_120628](https://github.com/user-attachments/assets/233a5d47-6eec-48ad-8a63-483eecf7257c)

## 5. Confusion Matrix
![IMG_20250624_120649](https://github.com/user-attachments/assets/12c5365f-5df3-4146-b719-367eb82e5527)

## 6. Final prediction output
![Brain_tumor_output](https://github.com/user-attachments/assets/cdf0ec4c-e892-4a7b-a310-bd3290d4e899)

