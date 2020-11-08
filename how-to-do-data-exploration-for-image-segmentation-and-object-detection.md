# How to Do Data Exploration for Image Segmentation and Object Detection

Data exploration is key to a lot of machine learning processes. That said, when it comes to object detection and image segmentation datasets there is **no straightforward way to systematically do data exploration.** 

There are multiple things that distinguish working with regular image datasets from object and segmentation ones:

* The label is strongly bound to the image. Suddenly you have to be careful of whatever you do to your images as it can break the image-label-mapping. 
* Usually much more labels per image.
* Much more hyper-parameters to tune \(especially if you train on your custom datasets\)

This makes evaluation, results exploration and error analysis much harder. You will also find that choosing a single performance measure for your system can be quite tricky – in that case manual exploration might still be  a critical step.

[https://neptune.ai/blog/data-exploration-for-image-segmentation-and-object-detection](https://neptune.ai/blog/data-exploration-for-image-segmentation-and-object-detection)

