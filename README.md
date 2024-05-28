# Car-Object-Detection-Faster-RCNN/n
🚗 Here is a Faster-RCNN Model for single class object detection, here car./n
Faster RCNN model consists of Region Proposal Network for Boundary Box Selection which is 2500x time faster than Primitive RCNN method of selection of boundary box by selective window./n
Evaluation is done by IoU method, means for Boundary box IoU>0.45 are considered and other are considered as scrap./n
IoU=(A∩B)/(A∪B) ; A=Ground Truth Boundary Box, B=Predicted Boundary Box , in test case sample.
