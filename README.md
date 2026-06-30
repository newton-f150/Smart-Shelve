# SmartShelf AI Platform

<div align="center">
  <img src="https://img.shields.io/badge/AI-Powered-blue?style=for-the-badge&logo=tensorflow"/>
  <img src="https://img.shields.io/badge/Rust-2023-orange?style=for-the-badge&logo=rust"/>
  <img src="https://img.shields.io/badge/YOLOv11-Computer%20Vision-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IoT-ESP32-yellow?style=for-the-badge&logo=espressif"/>
  <img src="https://img.shields.io/badge/Real--Time-MQTT-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-Ready-326CE5?style=for-the-badge&logo=kubernetes"/>
</div>

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Hardware Requirements](#hardware-requirements)
- [Software Stack](#software-stack)
- [AI & Computer Vision](#ai--computer-vision)
- [Installation Guide](#installation-guide)
- [API Documentation](#api-documentation)
- [Deployment Guide](#deployment-guide)
- [Monitoring & Observability](#monitoring--observability)
- [Security](#security)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact & Support](#contact--support)

---

## 🎯 Overview

**SmartShelf AI Platform** is a cutting-edge, end-to-end automated retail management solution that transforms traditional shelves into intelligent, self-aware inventory systems. Leveraging state-of-the-art computer vision and machine learning, it eliminates manual scanning and provides real-time inventory intelligence at scale.

### 🌟 Key Benefits

- **Zero Barcode Dependency** - Fully visual recognition of products
- **Real-Time Intelligence** - Instant detection of picks, returns, and anomalies
- **Scalable Architecture** - From single shelf to thousands of locations
- **Commercial Grade** - Production-ready with enterprise security
- **Cost Efficient** - Reduces shrinkage and optimizes restocking

### 🔥 Target Use Cases

- 🏪 **Retail Stores** - Smart shelves for supermarkets
- 📚 **Libraries** - Automated book tracking
- 🏥 **Hospitals** - Medical supply management
- 🔧 **Tool Shops** - Equipment tracking
- 💊 **Pharmacies** - Medicine inventory control
- 🏭 **Warehouses** - Smart bin management
- 🥫 **Vending Machines** - Automated restocking alerts

---

## ✨ Features

### Core Capabilities

| Feature | Description | Status |
|---------|-------------|--------|
| **Product Detection** | Real-time detection of all products using YOLOv11 | ✅ |
| **Product Recognition** | Identifies individual products without barcodes | ✅ |
| **Inventory Tracking** | Automatic count and stock level monitoring | ✅ |
| **Event Detection** | Pick, return, misplace, and restock events | ✅ |
| **Shelf Mapping** | Dynamic shelf slot and occupancy mapping | ✅ |
| **Analytics Engine** | Demand forecasting and anomaly detection | ✅ |
| **Real-time Alerts** | Instant notifications for critical events | ✅ |
| **Multi-Camera Support** | Synchronized multi-view monitoring | ✅ |

### Advanced AI Capabilities

- 🎯 **Object Detection** - YOLOv11, RT-DETR
- 🔍 **Instance Segmentation** - SAM2 for precise product boundaries
- 📍 **Object Tracking** - DeepSORT, ByteTrack, OCSORT
- 🧠 **Product Recognition** - Grounding DINO for zero-shot learning
- 📊 **Shelf Analysis** - Occupancy, mapping, and health monitoring

### Event Detection

- **🖐️ Product Picked** - Detects item removal
- **🔄 Product Returned** - Identifies item returns
- **⚠️ Misplaced Products** - Detects incorrect shelf placement
- **📦 Shelf Refilled** - Recognizes restocking events
- **🔴 Shelf Empty** - Alerts for depleted slots
- **❓ Unknown Products** - Flags unregistered items
- **💥 Product Falls** - Detects dropped items
- **📊 Multiple Products Removed** - Identifies bulk removal

---

## 🏗️ System Architecture

### High-Level Flow
