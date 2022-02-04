# Object detection + Depth Estimation Network

In this repository, we will develop and use depth estimation and object detection networks on [NYU Depth Dataset V2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html).

After preprocessing and generating bounding boxes from each image mask, we saved them for further use.

- For object detection networks, we tried the following networks:

>* Faster RCNN
>* YOLO-v3

- For Depth Estimation, we implemented two networks:

>* U-Net
>* Combination of MiDaS network and our self-trained network in TensorFlow

Then we estimated the errors of the combined network and developed a GUI at the last part.

You can run GUI part separately, but pay attention to running the preparing dataset subsection and the first two blocks of the GUI part before running the last one.

## Sample Results

<p align="center">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-1.jpeg" width="600">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-2.jpeg" width="600">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-3.jpeg" width="600">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-4.jpeg" width="600">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-5.jpeg" width="600">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-6.jpeg" width="600">
  <img src="https://github.com/Omid-SH/DeepLearning_FinalProject/blob/main/sample-outputs/sample-7.jpeg" width="600">
</p>
