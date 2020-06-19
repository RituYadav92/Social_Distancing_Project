# Social_Distancing_Project
### Distance between people is calculated between the center of lower edge of detected bounding boxes.
### 1. Run .yml file to create the enviornment for this project.
```conda env create -f environment.yml```
### 2. Drop an email to download the pre-trained YOLO v3 weights on coco dataset.
### 3. Run the code using following command
```python social_distance_detector.py --input pedestrians.mp4 --output output.avi```
