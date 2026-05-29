AquaNexus is an IoT + Deep Learning aquaponics system that monitors water quality, automates environmental control, and classifies spinach plant growth stages using computer vision. 
# AquaNexus - Automated Aquaponics and Plant Growth Monitoring System

## Overview

AquaNexus is a smart aquaponics monitoring and automation system that combines IoT, Deep Learning, and cloud technologies to create a sustainable farming solution.

The system continuously monitors critical environmental parameters such as pH, temperature, turbidity, humidity, and nutrient concentration while using computer vision models to analyze spinach plant growth stages. Real-time sensor data is collected through ESP32-based hardware and visualized through a cloud-connected dashboard, enabling remote monitoring and control of the aquaponics ecosystem. 

---

## Features

### IoT-Based Monitoring

* Real-time monitoring of:

  * pH
  * Water Temperature
  * Turbidity
  * Total Dissolved Solids (TDS)
  * Air Temperature
  * Humidity
* Continuous sensor data collection using ESP32 microcontrollers.

### Automation

* Automated environmental monitoring.
* Water circulation management.
* Remote actuator control for pumps and other devices.
* Cloud-based data logging.

### Deep Learning-Based Plant Growth Analysis

* Growth stage classification of spinach plants.
* Image preprocessing and augmentation.
* CNN-based plant growth monitoring.
* Comparative evaluation of multiple deep learning architectures.

### Remote Dashboard

* Live sensor visualization.
* Historical data tracking.
* Remote access from anywhere.
* Real-time notifications and monitoring.

---

## System Architecture

```text
Sensors
│
├── pH Sensor
├── TDS Sensor
├── Turbidity Sensor
├── DS18B20 Water Temperature Sensor
├── DHT11 Temperature & Humidity Sensor
│
▼

ESP32 Microcontroller
│
├── Data Collection
├── Device Control
└── Cloud Communication
│
▼

Raspberry Pi
│
├── Image Processing
├── Deep Learning Inference
└── Growth Stage Classification
│
▼

Cloud Platform
│
└── Dashboard & Data Storage
│
▼

User Interface
```

---

## Hardware Components

| Component        | Purpose                                      |
| ---------------- | -------------------------------------------- |
| ESP32            | Sensor data acquisition and communication    |
| Raspberry Pi     | Deep learning inference and image processing |
| pH Sensor        | Water acidity monitoring                     |
| TDS Sensor       | Nutrient concentration measurement           |
| Turbidity Sensor | Water quality monitoring                     |
| DS18B20          | Water temperature measurement                |
| DHT11            | Air temperature and humidity monitoring      |
| Camera Module    | Plant image acquisition                      |

---

## Software Stack

### Embedded Systems

* ESP32
* Arduino IDE

### Machine Learning

* Python
* TensorFlow
* Keras
* OpenCV

### Web Development

* React.js
* JavaScript
* HTML
* CSS

### Cloud & Data

* ThingSpeak
* IoT Cloud Services

---

## Deep Learning Models Evaluated

The project compares multiple deep learning architectures for spinach plant growth stage classification:

| Model        | Accuracy |
| ------------ | -------- |
| DenseNet     | 96.73%   |
| LNN          | 95.79%   |
| EfficientNet | 88.14%   |
| CNN          | 86.40%   |

These models were trained using a labeled spinach image dataset with preprocessing and data augmentation techniques. 

---

## Dataset

The dataset consists of labeled spinach plant images captured at different growth stages.

### Preprocessing

* Image resizing
* Normalization
* Data augmentation
* Train-validation split

### Classification Goal

Predict the growth stage of spinach plants from captured images.

---

## Objectives

* Automate aquaponics monitoring.
* Reduce manual intervention.
* Improve resource efficiency.
* Enable remote management.
* Monitor plant growth using deep learning.
* Support sustainable agriculture practices. 

---

## Results

* Successful integration of IoT sensors with cloud monitoring.
* Real-time environmental data acquisition.
* Automated monitoring of water quality parameters.
* Deep learning-based plant growth classification with up to 96.73% accuracy.
* Remote dashboard for monitoring and control. 

---

## Future Improvements

* Plant disease detection.
* Fish health monitoring using computer vision.
* Predictive analytics for crop yield estimation.
* Solar-powered deployment.
* Mobile application support.
* Advanced AI-based recommendation system. 

---

## Team

* Sashwat Navin
* Tushar Jain
* Jasnoorpreet Kaur
* Ishanpreet Uppal
* Manish Kumar

---

## License

This project was developed as a Capstone Project at Thapar Institute of Engineering and Technology.
