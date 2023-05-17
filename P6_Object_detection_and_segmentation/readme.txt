Object detection/Image segmentation using Mask_RCNN Architecture.

Object detection:
In computer vision, object detection involves both localizing one or more objects within an image and classifying each object in the image.
For localizing the object we draw bounding boxes around each detected object in the image(frame).
And for object classification, the model predicts the correct class of the localized object.

Object segmentation :
Object segmentation is an extension of object detection that involves marking the specific pixels in the image that belong to each detected object instead of using coarse bounding boxes during object localization.
The Region-Based Convolutional Neural Network, or R-CNN, is a family of convolutional neural network models designed for object detection.
There are four versions of it: R-CNN , Fast-RCNN , Faster- RCNN , Mask R-CNN.
Mask R-CNN: Extension of Faster R-CNN that adds an output model for predicting a mask for each detected object.
