# ROS_YOLO
This repository is to operacionalize YOLO model encapsulated into ROS2 middleware.


## Project Structure

- **train.py: File responsible for training YOLOv8 with the dataset using a .yaml configuration.**
- **test.py: File responsible for performing tests to verify if the integration between the camera and OpenCV is functioning correctly.**
- **yolo_opencv.py: File responsible for performing inference with the chosen dataset using images from the camera.**
- **keypoints.py: File responsible for testing YOLOv8 Pose keypoints for the desired angle.**
- **objects.py: File responsible for detecting pointed objects.**
- **multiperson_objects.py: File responsible for detecting pointed objects in multi-person scenarios.**
- **dataset/: Folder responsible for storing the pose dataset.**
- **runs/: Folder responsible for storing the trained model with the dataset and the obtained metrics.**
- **runs/weights/best.pt: File responsible for performing inferences (trained model).**
- **ros2_ws/: Folder containing files responsible for performing pose classification and pointed object detection in ROS 2.**

