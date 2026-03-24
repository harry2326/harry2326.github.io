# Harpreet Singh Munday

**Robotics | Artificial Intelligence | Computer Vision**

📍 Punjab, India
📧 [harpreetsinghmunday55@gmail.com](mailto:harpreetsinghmunday55@gmail.com)
🔗 GitHub: https://github.com/harry2326

---

## 🎯 Profile

I am a Robotics and AI enthusiast with hands-on experience in **computer vision/deep learning, embedded systems, and mechanical design**. My work focuses on building **end-to-end intelligent systems**, from hardware design to perception and control.

I am particularly interested in **Robot cognition, robot perception,  autonomous systems, and learning-based control**, and I aim to pursue advanced study in these areas.

---

## 🔥 Featured Project

## 🤖 5-Axis Robotic Arm (Custom Design | Kinematics | Embedded Control)

### 🎯 Overview

This project presents a fully functional **5-axis robotic arm** designed and built from scratch using custom 3D-printed components and multi-stage transmission systems. The system integrates **mechanical design, embedded control, and kinematic modeling** to achieve precise end-effector positioning.

The robotic arm is controlled using an **Arduino UNO**, with a **Python-based GUI** implementing forward and inverse kinematics for intuitive control and real-time visualization.

### 🧠 Key Contributions

* Designed complete mechanical structure with multi-stage gear reduction
* Implemented **forward and inverse kinematics** for Cartesian control
* Developed interactive GUI for real-time control and visualization
* Integrated embedded system with serial communication protocol
* Built an end-to-end robotics system combining **hardware + software + control**

### ⚙️ Mechanical Design

* Custom **3D-printed body structure and reducers**
* **Cycloidal gearbox (19:1)** for high precision and torque
* **GT2 belt transmission (4:1)**
* **Spur gear stage (2:1)**
* **Gear rod transmission (1:1)**
* **11:1 planetary gearbox** on base joint

👉 Multi-stage reduction enabled improved torque output and smoother motion control.

### 🔩 Actuation System

* **J1:** NEMA23 motor (10 kg·cm torque) + 11:1 planetary gearbox
* **J2–J6:** NEMA17 motors (5.6 kg·cm torque each)

### 🔌 Electronics & Control Hardware

* Arduino UNO (main controller)
* 6 × TB6600 stepper motor drivers
* Individual 12V power supplies
* USB serial communication

### 💻 Software Architecture

**GUI & Control Layer:**

* Tkinter + ttkbootstrap (user interface)
* IKPy (forward & inverse kinematics)
* Matplotlib (3D pose visualization)
* OpenCV (startup animation)

**Control Pipeline:**

1. User input (joint / Cartesian)
2. IK computation (if Cartesian mode)
3. Angle generation
4. Serial transmission to Arduino
5. Motor actuation via TB6600 drivers

### 🚀 Features

* Manual joint control (**−180° to +180° per joint**)
* Adjustable speed and acceleration
* Single-run and loop-run execution modes
* Real-time forward kinematics visualization
* Cartesian positioning using inverse kinematics (**X, Y, Z control**)
* Serial-based communication protocol

### 🧪 Kinematics & Modeling

* Implemented forward kinematics for pose estimation
* Applied inverse kinematics using IKPy
* Initial URDF-based modeling attempted; later replaced with **Matplotlib-based pose visualization** due to integration constraints

### 🎥 Demonstration

👉 [Watch Robotic Arm Demo](https://drive.google.com/drive/folders/15EBxHBVPbexHDDdc4UJPTtGjX7ANmkdU?usp=sharing)

### 📂 Project Repository

👉 [DETAILED_GIT_REPO](https://github.com/harry2326/5-Axis-Robotic-Arm-.git)

---


## 🚗 Computer Vision Projects

### 🔹 Lane Detection (Basic - Classical CV)

**Pipeline:**

* RGB → Grayscale
* Gaussian Blur
* Canny Edge Detection
* Hough Line Transform

🎥 **Output:**
(Add GIF here)

📂 Repo:
https://github.com/yourusername/lane-detection-basic

---

### 🔹 Lane Detection (Advanced)

**Techniques:**

* Camera calibration
* Perspective transform (Bird’s Eye View)
* Color & gradient thresholding
* Histogram-based lane detection
* Polynomial curve fitting

🎥 **Output:**
(Add GIF or video link)

📂 Repo:
https://github.com/yourusername/lane-detection-advanced

---

## 🧠 Machine Learning & Deep Learning

### 🔹 Perceptron from Scratch

* Implemented binary classifier without libraries
* Understood weight updates and convergence behavior

📂 Repo:
https://github.com/yourusername/perceptron-from-scratch

---

### 🔹 Neural Network from Scratch (MNIST)

* Built feedforward neural network from scratch
* Implemented forward + backpropagation
* Trained on MNIST dataset

📂 Repo:
https://github.com/yourusername/mnist-nn

---

### 🔹 CNN (LeNet - CIFAR-10)

* Implemented CNN architecture from scratch
* Trained on CIFAR-10 dataset
* Explored feature extraction and convolution layers

📂 Repo:
https://github.com/yourusername/cnn-cifar10

---

### 🔹 Traffic Sign Classification (CNN)

**Highlights:**

* Trained CNN for multi-class classification
* Applied preprocessing and normalization
* Achieved strong classification performance

🎥 **Output / Demo:**
(Add link)

📂 Repo:
https://github.com/yourusername/traffic-sign-classification

---

## 🛠 Technical Skills

**Programming:**
Python, C/C++, Arduino

**Robotics & Hardware:**
Embedded Systems, Motor Drivers (TB6600), Mechanical Design, Gear Systems

**AI / ML:**
Neural Networks, CNNs, Computer Vision

**Tools & Frameworks:**
OpenCV, NumPy, TensorFlow (basic), Jupyter Notebook

**Systems:**
Linux (WSL2), Git

---

## 🎯 Research Interests

* Autonomous Robotics
* Robot Perception
* Computer Vision for Navigation
* Learning-based Control Systems
* H
