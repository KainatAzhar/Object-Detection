# Real-Time Object Detection with YOLOv5

### Project Overview
This project demonstrates the implementation of a real-time object detection system using the **YOLOv5** (You Only Look Once) model. It is designed to identify and localize multiple objects within an image or video frame with high speed and accuracy. This project highlights proficiency in a state-of-the-art computer vision model, a key skill for applications like autonomous systems and video surveillance.

### Dataset
The project utilizes a pre-trained **YOLOv5 model** from the PyTorch Hub. The model was originally trained on the large-scale **COCO dataset**, which contains over 300,000 images and 80 object categories. This approach showcases the power of transfer learning in object detection.

### Methodology
1.  **Model Loading:** A pre-trained YOLOv5s model is loaded directly from the PyTorch Hub. This bypasses the need for extensive training and allows the model to be used for inference immediately.
2.  **Inference on Images:** The model is used to detect objects in a static image, outputting bounding boxes and confidence scores.
3.  **Real-Time Video Inference:** The model is applied to a video stream, processing each frame in real-time to perform live object detection. The results are displayed with bounding boxes and class labels.
4.  **Post-processing:** The project handles the common post-processing step of **Non-Maximum Suppression (NMS)**, which filters out duplicate bounding boxes to ensure clear and accurate detection.

### Concluded Results
The model successfully performs real-time object detection, demonstrating its ability to accurately identify and locate various objects in both images and video streams. The project serves as a strong example of a practical, high-impact computer vision application and highlights a deep understanding of modern object detection frameworks.

### Technologies Used
- Python
- PyTorch
- OpenCV
- YOLOv5
- Jupyter Notebook
