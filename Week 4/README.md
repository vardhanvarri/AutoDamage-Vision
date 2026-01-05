# Week 4 – Training & Evaluating an Object Detection Model

## Learning Goals
- Train an object detection model on real-world data
- Understand the end-to-end training pipeline
- Learn how object detection models are evaluated
- Perform qualitative and quantitative error analysis

---

## What This Week Is About
This week transitions from **understanding object detection** to **building a complete system**.

You will:
- Prepare a dataset for training
- Train an object detection model
- Evaluate model performance
- Analyze model failures and limitations

This week is **not about achieving high accuracy**, but about understanding *why models behave the way they do*.

---

## Model Choice (Important)
- **Week 3:** YOLOv3 was used for conceptual clarity and architectural understanding
- **Week 4:** YOLOv8 is used for training due to its clean, stable, and beginner-friendly pipeline

The underlying ideas of object detection remain the same across versions.

---

## Core Topics & Resources

### 1. Object Detection Training – High-Level Overview
- YOLO explained simply  
  https://www.youtube.com/watch?v=sv3txuThfmg

- How object detection models learn  
  https://www.youtube.com/watch?v=rZl5dO0gK_s

---

### 2. Bounding Boxes & Intersection over Union (IoU)
- IoU explained visually  
  https://www.youtube.com/watch?v=NYoHDzQkU1Q

- Object detection evaluation basics  
  https://www.youtube.com/watch?v=FppOzcDvaDI

---

### 3. Precision & Recall (Detection Context)
- Precision vs Recall intuition  
  https://www.youtube.com/watch?v=Z_p2bK2kLSo

- Why accuracy is misleading for detection  
  https://www.youtube.com/watch?v=R3P8xX1E9gE

---

### 4. YOLO Training (Practical)
- Ultralytics YOLOv8 documentation  
  https://docs.ultralytics.com

- YOLOv8 training walkthrough  
  https://www.youtube.com/watch?v=em_lO2ZXNfw

---

### 5. Common Failure Modes in Object Detection
- Why object detectors fail  
  https://www.youtube.com/watch?v=0tGZC0F_v0Y

- Small object & data bias issues  
  https://www.youtube.com/watch?v=Yb2M0Yk9kGg

---

## Tasks
- Prepare a small subset of the vehicle damage dataset
- Train a YOLO-based object detection model
- Evaluate the trained model using metrics and visualizations
- Perform qualitative error analysis

---

## Submission
- Completed notebooks
- Training logs or metrics
- Prediction visualizations
- Short written reflection on model behavior

---

## Key Takeaway
Training a model is easy.  
Understanding **why it succeeds and fails** is the real learning outcome.
