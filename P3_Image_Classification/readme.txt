Implemented an image classification model using MobileNet architecture.

MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications, Howard et al, 2017.
MobileNets are a class of small, low-latency, low-power models that can be used for classification, detection, and other common tasks convolutional neural networks are good for. 
Because of their small size, these are considered great deep learning models to be used on mobile devices.
The size of one of the currently largest MobileNets is about 17 MB,as compare to size VGG16 about 553 MB.
One more difference is number of parameters VGG16 has 138 million parameters and MobileNet has just 4.2 million parameters.
The MobileNet model is designed to be used in mobile applications, and it is TensorFlow’s first mobile computer vision model.
MobileNet uses depthwise separable convolutions. It significantly reduces the number of parameters when compared to the network with regular convolutions with the same depth in the nets. This results in lightweight deep neural networks.
For MobileNets the depthwise convolution applies a single filter to each input channel. The pointwise convolution then applies a 1×1 convolution to combine the outputs the depthwise convolution. 
1.Depthwise convolution.   
It is a map of a single convolution on each input channel separately. Therefore its number of output channels is the same as the number of the input channels.               
2.Pointwise convolution.
Convolution with a kernel size of 1x1 that simply combines the features created by the depthwise convolution.
