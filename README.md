# Orchid-Flower-Classification-Model

### Problem statement : 

To develop a robust CNN-based classification model capable of accurately categorizing 156 distinct orchid species based on their visual attributes, using a dataset of 7156 labeled images. The objective is to create an automated system that significantly improves the efficiency and accuracy of orchid species identification compared to manual methods, benefiting fields such as botany, horticulture, and ecological research.


### Data source:
Dataset is available at the following link : https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0HNECY

### What analysis were performed

We have utilized a dataset containing 7156 high-resolution images of orchid flowers, each labeled with one of the 156 orchid species. Our project consists of two main components:

##### 1.	CNN Classification Models:

Model 1: CNN Classification Model from Scratch: We have designed and implemented a CNN architecture from scratch, which learns to extract meaningful features from orchid flower images and classify them into their respective species.
Model 2: Transfer Learning/Fine-Tuning: Leveraging the power of transfer learning, we have explored the use of pre-trained models to enhance the classification performance. Fine-tuning a pre-trained model allows us to adapt it to the specific task of orchid species classification.

#### 2.	Multi-Task Model:
We have developed a multi-task model that serves a dual purpose. This model predicts not only the orchid species but also the number of flowers present in an image. By using a functional API and incorporating two output layers, we aim to provide more comprehensive information about the orchid images in a single pass.
Our project is aimed at delivering a well-structured and highly accurate orchid species classification model.

#### Files Overview:

```Orchid_Species_Classification_Model.ipynb``` : This notebook contains the following  :
-  Model 1  CNN Classification Model from scratch
-  Model 2: Used Transfer learning or fine-tuning to build the model

```Orchid_Multitask_Model.ipynb``` : Built a multi-task model that predicts the species and number of flowers using functional API and two output layers.

