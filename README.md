# Helmet Detection for Motorcyclists in Traffic
Helmet Detection system detects if motorcyclist if equiped with helmet with live feed from the traffic camera.

## Feature of Helmet Detection Model
Helmet Detection Model is trained using Object Detection YoloV5 model with custom dataset on Deep Neural Network

Helmet Detection Model use Deep Neural Network with CNN architecture model for Image Classification.

The model is potential to predicting multiple helmet with or without helmet at the same time and have proven results of recognition and classification to implement on traffic camera.

## Preview


# Installations
Follow steps to use this project:

1. Clone repository
```
git clone https://github.com/YashBorikar/Helmet-Detection.git
```
2. Change directory to clone repository
```
cd Helmet-Detection/yolov5
```
3. Run Following Command
```
python detect.py --weights runs/train/exp/weights/best.pt --img 416 --conf 0.1 --source ../Testing Data/**

Replace:
** with : Video/Image Name
** with : 0 to use Camera
```

# Important Files
1. Model Weights > best.pt : yolov5\runs\train\exp\weights\best.pt
2. Results > yolov5\runs\detect\exp

# Results

<a href="https://colab.research.google.com/drive/1FyvWRk-9U-pZo3Yt0MgagLwUtxN74oON?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

mAP@.5 : 79.00%
 ### Accuracy Report
<p>
  <img src="Git Assets/Reports 1.jpg" width="550" alt="Accuracy">
</p>
<p>
  <img src="Git Assets/Reports 2.png" width="550" alt="Accuracy">
</p>

 ### Classification Report
<p>
  <img src="Git Assets/Confusion Matrix.png" width="350" alt="Accuracy">
</p>

### Detection Result
<p>
  <img src="Git Assets/Detection Result.jpg" width="350" alt="Accuracy">
</p>

# Connect me
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/yashborikar/)
