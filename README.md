# ⚡ Sentinel-X // Cognitive Anomaly Shield

An interactive, cyberpunk-themed real-time transaction monitoring and anomaly detection platform powered by a custom Autoencoder Neural Network built entirely in Vanilla JavaScript.

🌐 **Live Demo:** https://illustrious-cupcake-f2b408.netlify.app

---

## 📌 Overview

Sentinel-X is an experimental fraud detection and anomaly monitoring system that demonstrates how machine learning models can be implemented directly in the browser without relying on external frameworks such as TensorFlow or PyTorch.

The application combines neural network fundamentals, real-time visualization, and an immersive cyberpunk-inspired interface to simulate transaction monitoring in financial systems.

---

## 🔍 Problem Statement

Modern payment networks process millions of transactions every day.

Traditional rule-based fraud detection systems are:

* Difficult to maintain
* Easy to bypass
* Unable to adapt to new fraud patterns

Cloud-hosted machine learning solutions can improve accuracy but often introduce:

* Infrastructure costs
* Network latency
* Scalability challenges

Sentinel-X explores an alternative approach by running anomaly detection directly inside the browser.

---

## 💡 Solution

Sentinel-X uses an Autoencoder Neural Network trained on normal transaction behavior.

The network:

1. Receives transaction features.
2. Compresses them into a latent representation.
3. Attempts to reconstruct the original transaction.
4. Calculates reconstruction error.
5. Flags high-error transactions as potential anomalies.

This approach allows the system to identify patterns that differ significantly from normal behavior.

---

## 🧠 Neural Network Architecture

Input Layer (6 Features)

↓
Encoder

↓
Latent Bottleneck (3 Nodes)

↓
Decoder

↓
Reconstructed Output (6 Features)

### Input Features

* Amount
* V1
* V2
* V3
* V4
* V5

### Detection Mechanism

* Low Reconstruction Error → Normal Transaction
* High Reconstruction Error → Potential Fraud / Anomaly

---

## 🚀 Features

### Machine Learning

* Custom Autoencoder Neural Network
* Forward Propagation
* Backpropagation
* Stochastic Gradient Descent (SGD)
* LeakyReLU Activation Function
* Reconstruction Error-Based Detection

### Real-Time Monitoring

* Live Transaction Stream
* Dynamic Error Analysis
* Adjustable Detection Thresholds
* Fraud Injection Testing

### Visualization

* Neural Network Visualizer
* Weight Strength Visualization
* Activation Monitoring
* Real-Time Error Charts

### User Experience

* Cyberpunk Dashboard Design
* Glassmorphism Interface
* Animated Telemetry Effects
* Critical Threat Alert System

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### Visualization

* Canvas API

### Machine Learning

* Custom Autoencoder
* Matrix Operations
* Gradient Descent
* Mean Squared Error (MSE)

### Deployment

* Netlify

---

## 📂 Project Structure

```text
Sentinel-X/
│
├── index.html
├── style.css
├── app.js
├── model.js
├── data.js
├── server.py
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/sentinel-x.git
cd sentinel-x
```

Run locally:

```bash
python server.py
```

Open:

```text
http://localhost:8080
```

---

## 🎯 Learning Outcomes

This project helped me gain hands-on experience with:

* Neural Network Fundamentals
* Autoencoders
* Anomaly Detection
* Backpropagation
* Gradient Descent
* Data Visualization
* Frontend AI Applications
* Browser-Based Machine Learning

---


## 👨‍💻 Author

**Kolapalli Jaswanth Kumar**

B.Tech Computer Science Engineering (AI & ML)

Vellore Institute of Technology (VIT)

---

## ⭐ Future Improvements

* Train on real transaction datasets
* Model persistence using Local Storage
* WebGPU acceleration
* Multiple anomaly detection models
* Explainable AI visualizations
* Historical analytics dashboard

---

If you found this project interesting, consider giving it a ⭐ on GitHub.
