# Social_Distancing_Project
<img src="https://github.com/RituYadav92/Social_Distancing_Project/Output_Demo1.gif" alt="alt text" width="300" height="200">

### 1. Run .yml file to create the enviornment for this project.
```conda env create -f environment.yml```
### 2. Drop an email to download the pre-trained YOLO v3 weights on coco dataset.
### 3. Run the code using following command
```python social_distance_detector.py --input pedestrians.mp4 --output output.avi```

### 4. If X server error then 

#### prevent any future commands in this session from connecting to your real X environment
```unset DISPLAY XAUTHORITY```

#### run yourcode.py with a fake X environment provided by xvfb-run
```xvfb-run python yourcode.py```
