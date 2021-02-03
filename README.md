# Human Pose Pose Matching : Computer Vision

## Goal of the Project
The goal of this project is to perform human pose estimation and matching. Given two images, a reference image and a trial image, human poses would be detected using keypoints and compared to determine the similarity between them. These key points can be plotted as a 2D stick-figure. The reference image would be overlayed on the trial image to find the similarity between the poses which are depicted in both of the images.

## Purpose of the project
Pose estimation and matching have a wide range of applications. Many individuals like dancers, athletes, yoga enthusiasts, etc. learn from following videos of experts in their field. This helps them learn various different poses, but it’s difficult for them to assess the correctness of these poses. By correctness, this means how close the position of their body parts matches the true position.
Our application would be of utmost use to them to instantly assess the differences in their pose compared to that of the experts. Being able to see the overlay can help them spot differences instantaneously and learn how to correctly position themselves.

## Instructions on how to use and run the code -
1. Ensure that the caffemodel and prototxt files for the pose estimation, as well as the utils.py are in the same folder as the Jupyter notebook.
2. Change the paths in the code to that of the new test and reference images. 3. Run all the cells of the Jupyter Notebook.
Requirements: OpenCV, Numpy, Matplotlib, Pandas

## Sample Outputs - 

### Example 1 

![IP1](https://github.com/KshitijaSAPatel/Pose-Matching---Computer-Vision/blob/main/Images/Sport.png)
![OP1](https://github.com/KshitijaSAPatel/Pose-Matching---Computer-Vision/blob/main/Images/Sport-ans.png)

### Example 2

![IP2](https://github.com/KshitijaSAPatel/Pose-Matching---Computer-Vision/blob/main/Images/Yoga.png)
![OP2](https://github.com/KshitijaSAPatel/Pose-Matching---Computer-Vision/blob/main/Images/Yoga-ans.png)

Do read the report for additional examples and details regarding the formula and methods used 
