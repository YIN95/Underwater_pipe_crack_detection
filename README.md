# Underwater_pipe_crack_detection
## Abstract
In recent years, image-based detection technologies have been developed and widely applied in various industries. 
Damage detection on underwater pipeline is one of the meaningful applications. 
In this project, we implemented an image-based damage detection system using transfer learning with models including VGG16 and MobileNet pre-trained on ImageNet in Keras. 
We tested different transfer learning techniques: 
(1) retrain fully-connected layers and fine-tune the last convolutional block; 
(2) use pre-trained network as feature extractor with normal SVM or one-class SVM. 
We also tested a shallow convolutional network for reference. 
All models were evaluated on the same non-public dataset, with additional visualization techniques for analysis. 
ost practically promising results were achieved by utilizing MobileNet model. 
Based on it, a simple demo program is established at the end, to illustrate a standard workflow using our network. 

## Acknowledgement
Thanks to Professor Josephine Sullivan for guidance in and after class.  
Thanks to teaching assistant Taras-Svitozar Kucherenko and Yue Liu for helpful suggestions.  
Thanks to Professor John Folkesson for the datasets and general advices.  
This project is financed by the Swedish Maritime Robotic Centre (SMaRC), 
a national centre funded by the Swedish Foundation for Strategic Research (SSF)  
Our VGG16 reference code is:https://github.com/Arsey/keras-transfer-learning-for-oxford102  
The MobileNet reproduce reference is:https://www.tensorflow.org/hub/tutorials/image\_retraining  
