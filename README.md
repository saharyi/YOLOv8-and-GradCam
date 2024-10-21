
# YOLOv8 Object Detection with Grad-CAM using Captum

This project implements object detection using the **YOLOv8** model combined with the **Grad-CAM** technique to provide explainability for model predictions. The goal is to highlight the regions in an image that contribute most to the model’s decision-making process, enabling better interpretability of deep learning results.

**Key Features**:
- **YOLOv8 Object Detection**: A pre-trained YOLOv8 model is used to detect objects in input images.
- **Explainability with Grad-CAM**: Gradient-weighted Class Activation Mapping (Grad-CAM) is applied to visualize the areas of the image that significantly influence the detection output.
- **Captum Library Integration**: The Captum library is utilized to apply Grad-CAM in a simple and modular fashion, providing detailed model insights.

## Project Goals
The main goal of this project is to combine state-of-the-art object detection with explainable AI techniques. This helps in understanding the behavior of deep learning models by showing which parts of the image the model focuses on during object detection. This can be especially useful in areas such as healthcare, autonomous driving, and any domain where model transparency is crucial.

