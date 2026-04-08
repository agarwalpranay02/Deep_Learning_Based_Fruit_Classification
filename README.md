# Deep_Learning_Based_Fruit_Classification
---

# Deep Learning-Based Classification of Fresh and Rotten Fruits 🍎🍌🍊

## Overview
This repository contains the implementation of the project *“Deep Learning-based Classification of Fresh and Rotten Fruits using Convolutional Neural Networks”*, developed as part of an academic project exploring deep learning and real-world image classification applications.  

The project leverages **Convolutional Neural Networks (CNNs)** and **transfer learning** to automate fruit quality inspection, classifying fruit images into **fresh** or **rotten** categories. The system aims to reduce human subjectivity, minimize food waste, and support agricultural and retail industries with scalable AI-driven solutions.

## Key Features
- 📊 **Dataset**: Kaggle dataset with ~10,901 images across six classes:
  - Fresh Apples, Rotten Apples  
  - Fresh Bananas, Rotten Bananas  
  - Fresh Oranges, Rotten Oranges  
- 🧹 **Preprocessing**: Image resizing, normalization, and augmentation for robust training.  
- 🧠 **Models Implemented**:
  - Normal CNN  
  - Custom CNN  
  - VGG16 (transfer learning)  
  - MobileNetV2 (transfer learning, best performing model)  
- ⚙️ **Performance**:
  - MobileNetV2 achieved **98.41% validation accuracy** with strong precision, recall, and F1-score.  
- 🌐 **Deployment**:
  - Flask/FastAPI backend serving predictions via API.  
  - Web-based frontend (React.js) for intuitive image upload and classification.  


MobileNetV2 emerged as the best-performing model, balancing accuracy and efficiency, making it suitable for real-world deployment.

## Applications
- ✅ Automated fruit quality inspection in warehouses and supermarkets.  
- ✅ Consumer-facing apps for freshness detection.  
- ✅ Agricultural supply chain monitoring to reduce waste.  

## Future Scope
- Multi-class severity detection (e.g., overripe, bruised).  
- Deployment on mobile devices using TensorFlow Lite.  
- IoT integration for real-time monitoring in storage/transport.  
- Cloud deployment for scalability and accessibility.  
- Real-time video-based fruit sorting in industrial settings.  

