# Class Activation Mapping (CAM) Visualization

This repository contains a Python script to generate and visualize **Class Activation Maps (CAM)** using a modified ResNet50 deep learning model. The purpose of CAM is to identify and highlight the regions of an image that the model focuses on for a specific class prediction.

---

## Features
- Uses a pre-trained **ResNet50** model with added custom layers.
- **Class Activation Mapping (CAM)** for interpretability in image classification tasks.
- Visualizes a heatmap superimposed on the input image to explain the model's decision.

---

## Dependencies
Make sure you have the following installed:
- `numpy`
- `tensorflow`
- `matplotlib`
- `opencv-python`
- `Pillow`

Install them using pip:
```bash
pip install numpy tensorflow matplotlib opencv-python Pillow
```
## Usage
Clone this repository:

```bash
Copy code
git clone https://github.com/your-username/Class-Activation-Mapping-CAM.git
cd Class-Activation-Mapping-CAM
```
Add your input image (e.g., IMG20240605140005.jpg) in the repository folder.

Run the script:

```bash
Copy code
python cam_visualization.py
```
### The script will:
Predict the class of the input image.
Generate a heatmap showing the important regions for the predicted class.
Display the input image with the superimposed heatmap.

## Applications
Explainability in deep learning models.
Debugging and improving model predictions.
Object localization in images.
