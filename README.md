# car-classification
this is a car classifier using ResNet50 (including training and test)

## Env
python3.6
tensorflow-gpu 2.3.1
keras 2.4.3

## Car Dataset
![DATASET]https://github.com/zq1335030905/car-classification/blob/main/%E5%9B%BE%E7%89%871.png

original dataset : 链接：https://pan.baidu.com/s/1T1uI_B7_HsPqr5QpD3thjg 提取码：g49w 

resize and rename dataset (Recommend!) : 链接：https://pan.baidu.com/s/11yt_RhEYwe-8AqRrgINRyw  提取码：f40t 

## Pretrained Model
You can train the model by yourself, or you can download the pretrained model for test.

链接：https://pan.baidu.com/s/11yt_RhEYwe-8AqRrgINRyw  提取码：f40t

## Folder
---- renas.py                %rename and resize dataset

---- resnet.py               %main file: including train and test

---- resnet_model_car2.h5    %pretrained model, can be used for test

---- acc.npy                 %test report(including precision, recall and f1-score)

## Train and Test
```
python resnet.py

![train]

![test]


