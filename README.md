# Computer Vision Project: PCB Test Point Pad Detection

## Overview
In this project, I developed and compared various machine learning models (Logistic Regression, Decision Trees, Random Forests, Artificial Neural Networks) to detect test-point pads on PCB images. The highest accuracy, approaching 100%, was achieved using an Artificial Neural Network (ANN).

### Data Source:
The data used for this project was sourced from Kaggle:  
[PCB Processed Image Dataset](https://www.kaggle.com/datasets/gauravduttakiit/printed-circuit-board-processed-image)

---
# What is PCB?
A printed circuit board (PCB), also called printed wiring board (PWB), is a medium used to connect or "wire" components to one another in a circuit. PCBs are crucial components in modern electronics, serving as a base for assembling and connecting electronic components.

More on that... [Wikipedia article on PCBs](https://en.wikipedia.org/wiki/Printed_circuit_board).

# What are test-point-pads in a PCB?
## What are Test-Point Pads in a PCB?
**Test-point pads** in a PCB are exposed **copper pads** on a PCB designed for testing and troubleshooting electronic circuits. They serve as accessible locations where engineers can connect probes to measure voltages, currents, or signals during various testing procedures.

### **Location:**
Test-point pads are typically located on the exterior layers of the PCB to ensure easy access for testing equipment. This positioning allows for effective contact with probes during testing.
### **Importance:**
Test-point pads are essential for verifying the functionality and integrity of PCBs during manufacturing and assembly. They allow that electrical connections are intact, all components operate as intended and identifying faults in the circuit design or assembly.

![image](https://github.com/user-attachments/assets/e7eadf28-75b1-4124-ae4f-ea6fc48f620f)  

## Data Overview
The dataset consists of pixel data from a PCB image, organized in a simple CSV format. Each row represents the properties of a single pixel on the image. 

### Variables:
- **X:** X-coordinate of the pixel.
- **Y:** Y-coordinate of the pixel.
- **R:** Red intensity value of the pixel.
- **G:** Green intensity value of the pixel.
- **B:** Blue intensity value of the pixel.
- **Grey:** Label indicating whether the pixel is considered grey (binary classification).

The dataset includes over **723,552 pixels** (one image), and the data is clean with no missing values. All variables are numeric, making it well-suited for training machine learning models.
