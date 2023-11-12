# Project 1: Face Recognition

## Model creator
```text
Vgg-16 & Vgg-19
-Hendra
-Fatturahman
GoogLeNet
-Yogi
-Dani
ResNet50
-Harisson
-Fitrah
```

## Introduction
In the modern digital era, security and identity management have become pressing issues. One of the primary challenges faced is the efficient supervision and control of access, especially in dense and complex environments. To address this issue, Face Recognition technology has emerged as a solution.

Face Recognition is a technology that utilizes algorithms to automatically identify and verify human faces. This process involves analyzing facial features such as the shape of the nose, eyes, and mouth to create a unique template for identification. The technology has rapidly advanced and found applications in various fields, including security, facial recognition on mobile devices, and identity management.

### Benefits of Face Recognition with AI

1. High-Level Security: Face Recognition systems supported by AI provide a high level of security, identifying individuals even in challenging situations.

2. Access Management: The use of this technology in access management to restricted areas or sensitive information helps enhance control and reduce the risk of unauthorized access.

3. Crime Recognition: In law enforcement, this technology can assist in identifying and tracking criminals more efficiently.

4. Identity Management: In a business context, Face Recognition aids in employee identity management, optimizing attendance processes and reducing internal security risks.

![face](https://github.com/Fitrah-just/Fitrah-Ramadhan/assets/84637046/250574ca-d1bd-430b-aa29-c42f0b705f98)

This image depicts how Face Recognition technology collaborates with AI to identify individuals with high accuracy. The process involves analyzing facial features and machine learning, ensuring precise recognition even in less-than-ideal conditions, such as low lighting or varied facial expressions.

By adopting Face Recognition technology supported by AI, challenges in identification and security can be more effectively addressed, bringing significant benefits to various industries and identity management needs.

## Getting Started

"We hope that the model we have created can be useful as intended.

The first thing you need to do is:

1. Import libraries 
Example:

```text
from keras.preprocessing.image import ImageDataGenerator
```
#This code for image augmentaion

3. Prepare your dataset
Example:

      ```text 

            google.colab import drivedrive.mount('/content/drive')
            image_path = os.listdir(os.path.join(Data_path, 'Images'))
            list_att =(os.path.join(Data_path, 'list_attribute2.txt'))
            df = pd.read_csv(list_att, usecols=['image_id','Male'], delimiter=r'\s+', skiprows=1)
    ```
#This code for import your data using google drive

5. Split dataset into train,test,and validation

6. Preprocess your dataset

7. Build the model

8. Train your model

9. Evaluation


## The Result

"The results of our model using VGG16, VGG19, GoogLeNet, and ResNet50 vary significantly.

### The result from ResNet :

1. This model accuracy is 94%

2. Image prediction result


![image](https://github.com/Fitrah-just/Fitrah-Ramadhan/assets/84637046/2328d2b5-784e-4ff5-bec8-2f17a39fd509)


### The result from GoogLeNet :

1. This model accuracy is 97%

2. The Graphic Result

![image](https://github.com/Fitrah-just/Fitrah-Ramadhan/assets/84637046/d32ba71b-9a0b-413c-8b3f-1ab79fbef807)

### The result from Vgg-19 & Vgg-16 :

1. This model accuracy is 92%

2. The Confusion Matrix Result

![image](https://github.com/Fitrah-just/Fitrah-Ramadhan/assets/84637046/be2050f8-3e2a-40cc-8e4a-79f3f234e11a)

So far, our best-performing model is GoogLeNet with high accuracy





## following Python libraries installed:

* Basic Libraries: [NumPy](http://www.numpy.org/), [Matplotlib](http://matplotlib.org/), [Pandas](https://pandas.pydata.org/)
* Domain-specific Libraries: [OpenCV](https://opencv.org/)
* Deep-learning Frameworks: [Keras](https://keras.io/), [PyTorch](https://pytorch.org/), [TensorFlow](https://www.tensorflow.org/)

 That's all, for any discussion kindly contact me here: ramadhanfitrah2@gmail.com


            
