## Pneumonia-detection-using-Deep-Learning
Pneumonia detection using chest X-rays: Deep Learning <br /> 
Author: Sarthak Das Roy

![Chest X-Ray](https://user-images.githubusercontent.com/48868854/78462200-c42bdd80-76c7-11ea-8c6d-857debe39c6f.png)

> __Overview:__  
> Domain             : Computer Vision, Machine Learning <br /> 
> Sub-Domain         : Deep Learning, Image Recognition <br />
> Techniques         : Deep Convolutional Neural Network <br />
> Application        : Image Recognition, Image Classification, Medical Imaging <br />

> #### Data:  
> Dataset Name     : Chest X-Ray Images (Pneumonia) <br /> 
> Dataset Link     : Chest X-Ray Images (Pneumonia) Dataset ([Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)) <br /> 
> Original Paper   : Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning
                   (Daniel S. Kermany, Michael Goldbaum, Wenjia Cai, M. Anthony Lewis, Huimin Xia, Kang Zhang)
                   https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5 <br /> 

> #### Dataset details:
> Dataset Name            : Chest X-Ray Images (Pneumonia) <br /> 
> Number of Class         : 2 <br /> 
> Number/Size of Images   :  <br /> 
>> Total      : 5856 (1.15 Gigabyte (GB)) <br /> 
>> Training   : 5216 (1.07 Gigabyte (GB)) <br /> 
>> Validation : 320  (42.8 Megabyte (MB)) <br /> 
>> Testing    : 320  (35.4 Megabyte (MB)) <br /> 


> #### Model details: ####<br /> 

Detected Pneumonia from Chest X-Ray images using Custom Deep Convololutional Neural Network. <br /> 
>Model Architecture: 
>>The model is built on Convolution-Pooling layers set back to back. <br />
>>All the convolution layer have 32 filters with a (3*3) filter formation. <br />
>>The weights are initialized uniformly and rectified linear ('relu') activation function is used. <br />
>>Pooling layers of pool size (2*2) is used after each convolution operation. <br />
>>Post Flattening the layers, two more dense layers are added with 256 nodes with rectified linear activation function. <br />
>>Final layer with a single node and a probabilistic 'sigmoid' activation function is used. <br />
>>The model is then compiled using 'adam' optimizer with 'binary_crossentropy' as the loss funtion and 'accuracy' as the metrics. <br />


> #### Model Performance: #### <br />


After completing 25 epochs the model performance is listed below. <br />

>> Training set: Accuracy: 96.22% Loss: 10.33% <br />
>> Test set: Val_accuracy: 91.03% Val_loss: 46.61% <br />
