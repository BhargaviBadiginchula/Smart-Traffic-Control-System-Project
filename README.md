# AI-Based Smart Traffic Control System Using Density-Based Canny Edge Detection

## Overview

The AI-Based Smart Traffic Control System is a Python-based project designed to optimize traffic signal timing based on real-time vehicle density detection. The system uses OpenCV image processing techniques and the Canny Edge Detection algorithm to analyze traffic conditions and dynamically allocate signal timings.

This project aims to reduce traffic congestion, improve traffic flow efficiency, and demonstrate the practical application of computer vision in intelligent transportation systems.

---

## Features

* Vehicle density detection using image processing
* Dynamic traffic signal timing allocation
* Canny Edge Detection implementation using OpenCV
* Graphical User Interface (GUI) using Tkinter
* Traffic density analysis and monitoring
* Adaptive traffic management logic

---

## Technologies Used

| Technology | Purpose                             |
| ---------- | ----------------------------------- |
| Python     | Core programming language           |
| OpenCV     | Image processing and edge detection |
| Tkinter    | GUI development                     |
| NumPy      | Numerical computations              |

---

## Project Workflow

1. Capture or load traffic lane images.
2. Apply preprocessing techniques.
3. Perform Canny Edge Detection using OpenCV.
4. Calculate traffic density based on detected edges.
5. Dynamically allocate signal timing according to density.
6. Display results using the Tkinter GUI.

---

## System Architecture

```text
Input Traffic Image/Video
            ↓
Image Preprocessing
            ↓
Canny Edge Detection
            ↓
Vehicle Density Calculation
            ↓
Dynamic Signal Timer Allocation
            ↓
GUI Display and Monitoring
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/smart-traffic-control-system.git
```

### Navigate to the Project Folder

```bash
cd smart-traffic-control-system
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python main.py
```

---

## Required Libraries

Create a `requirements.txt` file with the following dependencies:

```text
opencv-python
numpy
tkinter
skimage
matplotlib
```

---

## Screenshots

### Traffic Monitoring GUI
# Gui Interface
<img width="1897" height="932" alt="Screenshot 2026-05-23 125232" src="https://github.com/user-attachments/assets/1519de2d-0a01-4d30-b481-dd40855d3947" />

# Uploading Image
<img width="1884" height="763" alt="Screenshot 2026-05-23 125253" src="https://github.com/user-attachments/assets/a1aef5a6-bd5e-4d7d-8f99-6632ad80f6b6" />

# Preprocessing Image
<img width="1779" height="839" alt="Screenshot 2026-05-23 125319" src="https://github.com/user-attachments/assets/a081ba1f-45c9-4580-9af6-5ab043eb45a3" />

# White Pixel Count
<img width="1919" height="948" alt="Screenshot 2026-05-23 125338" src="https://github.com/user-attachments/assets/30297194-604d-483a-a54b-b1866bd4bd49" />



### Traffic Density Detection

<img width="1900" height="865" alt="Screenshot 2026-05-23 125358" src="https://github.com/user-attachments/assets/c9816741-eb03-43c3-b957-a63ff77624fd" />


---

## Future Improvements

* Real-time CCTV camera integration
* Machine Learning-based traffic prediction
* Emergency vehicle prioritization
* Cloud-based traffic monitoring system
* Multi-lane traffic optimization

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Computer Vision fundamentals
* OpenCV image processing techniques
* Canny Edge Detection algorithm
* GUI application development using Tkinter
* Traffic density calculation logic
* Real-world problem solving using Python

---

## Project Applications

* Smart City Traffic Management
* Intelligent Transportation Systems
* Traffic Congestion Reduction
* Automated Traffic Monitoring

---

