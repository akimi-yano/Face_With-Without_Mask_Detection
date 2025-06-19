# YOLOv3 vs YOLOv4 Object Detection Comparison for Face With/Without Mask Detection

This project compares the performance of **YOLOv3** and **YOLOv4** object detection models on two sample videos, by training machine learning models that classify a face with or without mask. The below image is an object detection using YOLOv4:

![](./visuals/mask_no_mask.png?raw=true)

## 🔍 Models Compared
- **YOLOv3**: Known for its speed and reliability in real-time applications.
- **YOLOv4**: Improved accuracy and better performance on complex scenes.

---

## 🎥 Detection Results Grid

|               | **Video 1**                             | **Video 2**                             |
|---------------|-----------------------------------------|-----------------------------------------|
| **YOLOv3**    | [YOLOv3 - Video 1](https://youtu.be/F86IRYvmNUc?si=Zpya-hQJMPN4Qbmc) | [YOLOv3 - Video 2](https://youtu.be/IBkcdNz4TWA?si=tjcpO8WC8pC3JYwh)|
| **YOLOv4**    | [YOLOv4 - Video 1](https://youtu.be/9BO3bRHGWqc?si=DmgusuBpez9ti0Sk) | [YOLOv4 - Video 2](https://youtu.be/DyJk7u_6VV4?si=q1p0w5Po09wJlt7S)|

---

## 📈 Observations
- YOLOv3 runs faster on lower-end GPUs but may miss subtle detections.
- YOLOv4 detects smaller or partially occluded objects more accurately.
