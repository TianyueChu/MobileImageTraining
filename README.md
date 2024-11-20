# On-Device Training on Android (Java)

This repository demonstrates how to perform **on-device training** on Android devices with Java.  devices, enabling efficient, decentralized learning.

## Features

- **On-Device Training**: Train models directly on Android devices without requiring server interaction.
- **ONNX Runtime**: Leverages the ONNX Runtime library for efficient model inference and training.
- **Android Integration**: Example project designed for Android Studio with Java.
- **Pre-trained Model Fine-Tuning**: Includes a Jupter notebook for importing pre-trained MobileNet models from [FedFlower](https://github.com/TianyueChu/FedFlower) project.

---

## Prerequisites

Before starting, ensure you have:

1. **Android Studio** installed.
2. **ONNX Runtime libraries** integrated into your project.
3. A compatible Android device (or emulator) with camera for testing.
4. JDK 8 or later.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/TianyueChu/MobileImageTraining.git
```

### 2. Set up Enviroment
- Open the Project: Launch the project in Android Studio.
- Add Dependencies: Ensure that the ONNX Runtime library is properly configured in your project.
- Prepare Your Device: Connect a physical Android device or set up an emulator to test your app.

### 3. Follow the Guide

We provide a step-by-step [video](https://www.youtube.com/watch?v=iHx9nd1dtF0) tutorial to help you implement on-device training and inference. Watch the video on YouTube to get started.