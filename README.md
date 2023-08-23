# Automatic Number Plate Detection and Recognition using YOLOv8
This project is about automatic number plate detection and recognition using YOLOv8, a state-of-the-art deep learning model for object detection. The project consists of the following steps:

**Vehicle detection:** using a custom-trained YOLOv8 model to locate and crop the vehicles in the input video frames.
**License plate detection:** using custom-trained YOLOv8 model to locate and crop the license plates in the cropped vehicle frames.
**License plate recognition:** using optical character recognition (OCR) techniques to read and output the characters and numbers on the license plates.

The project is designed to work in scenarios where the vehicle traffic is from the same entry/exit point, such as parking lots. This allows for calibrating the video frame and specifying the regions of interest for license plate detection, which improves the accuracy of the system.

## CLI
```
python predict.py model='name_of_your_model.pt' source='name_of_your_input_file.mp4'
```
### You can train your model on a custom dataset using Roboflow notebook: 
https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov8-object-detection-on-custom-dataset.ipynb

### Pretrained Model Link: 
```
gdown "https://drive.google.com/uc?id=1dIyJooVaowaNUj0R1Q-HUnu-utiGsEj8&confirm=t"
```

### RESULTS

#### Licence Plate  Detection and Recognition  


https://github.com/SiddharthUchil/ANPR_YOLOv8/assets/36127139/7a6ccc64-c133-44a5-841c-2729be49a3f6

