# Surface Defect Classification using CNN

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) for multiclass classification of surface defects using the NEU dataset.

## 📊 Dataset
Classes:
- Crazing
- Inclusion
- Patches
- Pitted Surface
- Rolled-in Scale
- Scratches

   Download from:- https://www.kaggle.com/datasets/kaustubhdikshit/neu-surface-defect-database 

## ⚙️ Model Details
- Framework: PyTorch
- Architecture: CNN (3 Conv layers + FC layers)
- Input Size: 224x224
- Optimizer: Adam
- Loss Function: CrossEntropyLoss
- Epochs: 10
- Batch Size: 32

## 📈 Results
- Validation Accuracy: ~89%
- Test Accuracy: ~95%

## 📊 Outputs
- Training Graph
- Confusion Matrix
- Excel Reports

## 📁 Files
- notebook.ipynb → full implementation
- model_code.py → clean script
- model.pth → trained model
- results.xlsx → training logs

## 🚀 Future Improvements
- Data Augmentation
- Transfer Learning
- Hyperparameter tuning

## Note:-
model.pth file cannot be viewed directly, but can load in Pytorch.

by using the code:-
- model = CNN(len(classes))
- model.load_state_dict(torch.load("/content/drive/MyDrive/ML_Project_NEU/model.pth"))
- model.eval()
  
