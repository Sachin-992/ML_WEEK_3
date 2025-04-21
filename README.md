# ML_WEEK_3
<h2>Project Summary<h2>
 <h4>This repository shows my learning and implementation of deep learning models step by step using popular image datasets like CIFAR-10, Dog Breed, and MNIST.<h4>



🔹 Step 1: CNN with CIFAR-10
I started by learning and implementing a basic Convolutional Neural Network (CNN) using the CIFAR-10 dataset to understand how image classification works with deep learning.

🔹 Step 2: Model Comparison on CIFAR-10
After that, I created a file to compare three deep learning models on the CIFAR-10 dataset:

  1)basic CNN model

  2)CNN with Data Augmentation to improve accuracy

  3)CNN using ResNet architecture to solve the vanishing gradient problem

🔹 Step 3: Transfer Learning with Dog Breed Dataset
Once I understood CNNs and ResNet, I moved on to Transfer Learning. I used a pre-trained ResNet model to classify dog breeds in a new dataset, learning how to fine-tune existing models for custom tasks.

🔹 Step 4: MNIST Digit Classification
Finally, I implemented a CNN model for the MNIST handwritten digit dataset to test and practice everything I learned in a simple classification task.
 
<h2>Learnings<h2>
 
 1)Learn and implement CNNs from scratch.
 
 2)Understand ResNet architecture and how it helps with vanishing gradients.
 
 3)Apply data augmentation techniques to improve validation accuracy.
 
 4)Analyze and compare model performance.

  # Model Performance Summary

| Model                  | Train Accuracy | Val Accuracy | Train Loss | Val Loss |
|------------------------|----------------|--------------|------------|----------|
| **Basic CNN**          | 74.23%         | 66.21%       | 0.7454     | 1.0237   |
| **ResNet**             | 95.02%         | 79.71%       | 0.1456     | 0.5853   |
| **ResNet + Augment**   | 84.00%         | 82.64%       | 0.4632     | 0.5156   |

##  Accuracy and Loss Plots

![17a2485e-049c-4302-98aa-62d4e7dfa2e1](https://github.com/user-attachments/assets/ef888a82-065e-471c-98f9-e2aaf9b511b0) 


![26dbb838-e871-4b1a-941d-a12a7087b3b9](https://github.com/user-attachments/assets/6f5a3770-9012-4efb-acf7-aa0699be9acd) 


![708bde74-b0fa-4e35-a37b-3f70c2d15d7d](https://github.com/user-attachments/assets/96a520a0-ce2c-4b9d-9bf3-1b03aee7be58)


![cdfdd227-b0d5-473d-a0b9-7679d49d9e17](https://github.com/user-attachments/assets/5cffd458-3ec1-4139-ba5c-3af1cb865085)


<H1>MNIST DATASET<H1>

<h3>ACCURACY AND LOSS PLOTS</h3>
 
![8bc3090e-72be-4958-911f-495aae438b6c](https://github.com/user-attachments/assets/832eb44b-bb7c-4522-a10b-7bdc70ce6877)

![07015e8b-e6ac-4fd9-a8c8-ae8b1c05cd85](https://github.com/user-attachments/assets/15a867e9-48fa-42e7-b98a-7e542b5264a6)

<h3>PREDICTED SAMPLES<h3>
 
![02d3bb78-734a-4ece-807f-c0bd816b2e8c](https://github.com/user-attachments/assets/6178027d-848a-4d3a-bf6d-3b5289d14182)

![325deeb5-6106-4891-808a-1544f4bc5fe3](https://github.com/user-attachments/assets/30efc3f7-374c-4ec7-9639-9a2cc6fc0371)
