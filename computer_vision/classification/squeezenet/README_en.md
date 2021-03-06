EN|[CN](README.osc.md)
#### Model Description
Image classification inference model

##### Notice:
When converting the model, you can directly use the network model in the warehouse. If you need to retrain, you can refer to the network model link of the original model in readme

##### Pre-trained Model Link:
https://obs-model-ascend.obs.cn-east-2.myhuaweicloud.com/squeezenet/squeezenet.caffemodel

##### Original Model Network Link:
https://github.com/DeepScale/SqueezeNet/tree/master/SqueezeNet_v1.1

##### Input Data Description:
The input image should be resized to 227*227 pixels, and padding to 256*224 pixels, YUV420SP_U8.

##### Out Data Description:
The pre-trained model is trained for image recognition, and its results follow 1000 lables of ImageNet.

