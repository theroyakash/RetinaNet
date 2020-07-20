# RetinaNet
Object Detection with RetinaNet
Object detection a very important problem in computer vision. Here the model is tasked with localizing the objects present in an image, and at the same time, classifying them into different categories. Object detection models can be broadly classified into "single-stage" and "two-stage" detectors. 

Two-stage detectors are often more accurate but at the cost of being slower. Here in this example, we will implement RetinaNet, a popular single-stage detector, which is accurate and runs fast. RetinaNet uses a feature pyramid network to efficiently detect objects at multiple scales and introduces a new loss, the Focal loss function, to alleviate the problem of the extreme foreground-background class imbalance.
