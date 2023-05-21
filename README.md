# Rock-Paper-Scissors with YOLOv5 Object Detection

This is a Yolov5 Project that allows you to play rock-paper-scissors in front of a webcam using YOLOv5 object detection. The project utilizes computer vision techniques to detect hand gestures and classify them as rock, paper, or scissors and processes them to display who won.

## Demo



https://github.com/PhilReg/RPS_Yolo/assets/116729488/73e98368-caa8-429c-a211-bba85e853e98



### Additional information:
-Trained following the yolov5 documentation for custom models (https://github.com/ultralytics/yolov5)
-Trainingset in repository only includes the original images. An augmentationspipeline is in place to augment these for additional data
-The only hyperparameter changed from the original settings is the confidence threshold (0.25->0.05)
-For the best results play infront of a white background
