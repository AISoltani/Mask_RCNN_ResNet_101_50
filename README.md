# Mask-RCNN

Using Mask R-CNN over TensorFlow < 2.0 and Keras > 2.1.5

# What is Mask-RCNN?
Mask R-CNN is a deep learning model that combines object detection and instance segmentation. It is an extension of the Faster R-CNN architecture.

The key innovation of Mask R-CNN lies in its ability to perform pixel-wise instance segmentation alongside object detection. This is achieved through the addition of an extra "mask head" branch, which generates precise segmentation masks for each detected object. This enables fine-grained pixel-level boundaries for accurate and detailed instance segmentation.

Two critical enhancements integrated into Mask R-CNN are ROIAlign and Feature Pyramid Network (FPN). ROIAlign addresses the limitations of the traditional ROI pooling method by using bilinear interpolation during the pooling process. This mitigates misalignment issues and ensures accurate spatial information capture from the input feature map, leading to improved segmentation accuracy, particularly for small objects.

FPN plays a pivotal role in feature extraction by constructing a multi-scale feature pyramid. This pyramid incorporates features from different scales, allowing the model to gain a more comprehensive understanding of object context and facilitating better object detection and segmentation across a wide range of object sizes.
