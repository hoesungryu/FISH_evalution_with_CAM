# FISH_evalution_with_CAM

## Description

In this repository we applied CAM(Class Activation Mapping) method to expalian the Deep Learning network. The goal is to create a model to classify the class and then produce visual explanations with variety of the CAM method.  

## Dataset
This dataset contains 9 different seafood types collected from a supermarket.
[A Large-Scale Dataset for Segmentation and Classification](https://www.kaggle.com/crowww/a-large-scale-fish-dataset)

## Train
```
python train.py --data_dir /path/your/data/dir --save_dir /path/your/save/dir
```
## Evaluation
```
python evaluation.py --image_dir /path/your/image/dir --label_dir /path/your/label/dir --target_class 0~8
```
Class\
0: Black Sea Sprat,\
1: Gilt-Head Bream\
2: Hourse Mackerel\
3: Red Mullet\
4: Red Sea Bream\
5: Sea Bass\
6: Shrimp\
7: Striped Red Mullet\
8: Trout

## Requirment
torch                  1.7.1\
torchcam               0.2.0\
torchvision            0.8.2\
tqdm                   4.62.3\
Pillow                 8.1.1\
opencv-python          3.4.8.29\
numpy                  1.21.2\
matplotlib             3.3.2
