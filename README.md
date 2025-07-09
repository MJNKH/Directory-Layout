# Driver Behavior Recognition Based on Deep Learning and In-Vehicle Sensor Data

This project focuses on recognizing and classifying driver behavior using a novel deep learning framework that combines multimodal data from dashboard cameras and in-vehicle sensors. The system is designed to improve the safety and intelligence of modern driving systems, including autonomous vehicles.

## 🚗 Overview

Traditional methods for driver behavior recognition often rely on handcrafted features and rule-based logic, which struggle to generalize across real-world scenarios. This project introduces **DriveFormer**, a hybrid deep learning architecture built to address these limitations through:

- **Transformer-based global reasoning**
- **Convolutional spatial sensitivity**
- **Multimodal spatiotemporal input processing**
- **Dynamic behavior reasoning using memory-guided attention**

## 🧠 Key Components

### DriveFormer
A hybrid architecture that combines:
- **Transformer modules** for long-range temporal modeling
- **Convolutional layers** for localized spatial feature extraction

### Perceptual-Memory Attention Strategy
Inspired by cognitive science, this mechanism:
- Uses a **learned memory bank** of behavior prototypes
- Enables reasoning under uncertainty and enhances classification of **semantically similar actions**

## 📊 Input Modalities

The model processes synchronized sequences of:
- **Visual data** (e.g., dashboard camera frames)
- **In-vehicle sensor data** (e.g., speed, acceleration, steering angle)

## 🧪 Experimental Results

Our evaluations demonstrate that the proposed method:
- Outperforms traditional rule-based and CNN/RNN-based models
- Maintains robustness across **complex and dynamic driving environments**
- Offers improved **behavior disambiguation** accuracy

## 🧰 Technologies Used

- Python
- PyTorch (or TensorFlow, depending on your implementation)
- Transformers
- CNNs
- Sensor fusion techniques

## 📁 Project Structure
