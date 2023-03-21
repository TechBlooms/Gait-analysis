# Pose estimation approach for Gait analysis using machine learning

 **Gait analysis** is a useful tool for diagnosing senility and frailty diseases. By transferring the pose estimation data to a correct statistical analysis, gait analysis can be carried out utilizing machine learning and computer vision approach, allowing physiotherapists to analyse and treat patients accordingly. 
![](https://d2lfsu1qnyxzxu.cloudfront.net/cms/nga-feature.jpg)


# 01 Motivation
 
The main problem observed is that physiotherapists will analyse stroke patients' walking patterns on their own. As a result, this approach solves the problem by providing an accurate result of the observation. As everything is computerised, proper treatment can be provided with accurate data. A physiotherapist could also use machine learning classification techniques to analyse and classify the observed disorder and correct it. Our study mainly focuses on using machine learning approach instead of traditional sensor based or consultation just by vision. This will serve as a newer and better proposition of the same.

# 02 Setup
We have used intelOneApi devcloud in the implementation of this to make it optimized to work in different environments.

# 03 Implementation 

The framework used in pose estimation is mediapipe. For keypoint detection, we use COCO dataset.


# 04 Deployment of OneAPI
OneAPI is used enable the use of one platform for a range of different hardware, hence it eliminated the need for different languages, tools, and libraries when to code for CPUs and GPUs. 
Openvino was used in this project which helped in optimization of the computer vision packages that were used including OpenCV and other DL packages required for it.

Steps

Step 1: Create virtual environment
``` bash
python -m venv openvino_env
```
Step 2: Activate virtual environment
``` bash
openvino_env\Scripts\activate
```
Step 3: Upgrade pip to latest version
``` bash
python -m pip install --upgrade pip
```
Step 4: Download and install the package
``` bash
pip install openvino-dev==2022.3.0
```
Afer implementing the above commands, the terminal window has the openVINO vitual environment actiavted like shown below.



How to run,

![gait ss openvino -1](https://user-images.githubusercontent.com/118420309/226524641-22238c84-ac60-4df3-992a-a06b71f323ca.png)


Make sure the virtual environment is activated and the python file.
The resulting, will open a window of the output.

# 05 Poses Estimated
The keypoints in human body are detected and its respective skeletal image can also be brought.





