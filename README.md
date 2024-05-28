# Car-Object-Detection-Faster-RCNN
🚗 Here is a Faster-RCNN Model for single class object detection, here car.
Faster RCNN model consists of Region Proposal Network for Boundary Box Selection which is 2500x time faster than Primitive RCNN method of selection of boundary box by selective window.
Evaluation is done by IoU method, means for Boundary box IoU>0.45 are considered and other are considered as scrap.
IoU=(A∩B)/(A∪B) ; A=Ground Truth Boundary Box, B=Predicted Boundary Box , in test case sample.
