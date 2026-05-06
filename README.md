# Animal Species Classification
**Student:** Star Yarbrough
**Course:** ITAI 1378 - Computer Vision and AI
**Project Tier:** Tier 1 Computer Vision Project

## Problem Statement
Identifying animal species from images can be time-consuming and often requires expert knowledge. Automaating species classification can assist wildlife researchers and biodiversity monitoring efforts by speeding up the identification process.

## Solution Overview
This project proposes an image classification system that predicts the species of an animal from an input image and outputs the predicted species along with a confidence score. 

## Technical Approach
- **Technique:** Object Detection
- **Model:** YOLOv8 (pre-trained)
- **Framework:** Ultralytics YOLO + Python
- **Method:** A pretrained YOLOv8 model was used to test oject detection performance on  various animal and object images in Google Colab. 

## Dataset Plan
- **Source:** Personal test images and publicly available animal images. 
- **Content:** Images included real dogs, a backyard cat, stuffed animal objects, decorative objects, and online wildlife images. 
- **Purpose:** The images were used to evaluate how a pretrained YOLOv8 model performs on different types of animal and object imagery. 
- **Preparation:** Images were uploaded into Google Colab and processed individually during YOLOv8 inference. 

## Success Metrics
- **PrimarybMetric:** Classification accuracy &ge; 80%
- **Secondary Metric:** Inference time < 1 second per image

## Week-by-week Plan
- **Week 10:** Dataset selection and environment setup
- **Week 11:** Model configuration and baseline training
- **Week 12:** Evaluation and performance improvements
- **Week 13:** Output generation and testing
- **Week 14:** Documentation and final adjustments
- **Week 15:** Presentation

## Resources Needed
- Google Colab (free GPU)
- PyTorch
- Public wildlife dataset
- Estimated Cost: $0

## Risk & Mitigation
- **Risk:** Dataset complexity
  - *Mitigation:* Limit number of species/classes
- **Risk:** Low accuracy
  - *Mitigation:* Apply data augmentation or adjust model selection

## AI Usage Log
AI tools were used to assist with brainstorming project structure, refining documentation language, and clarifying technical planning decisions. 
All implementation adn final decisions were made by myself, the project author. 

This section will be updated as development continues.

## Current Status 
- [x] Repository created
- [x] YOLOv8 Notebook comlpeted
- [x] Multiple image detection tests completed 
- [x] Project analysis and obersavtions completed
- [x] AI Usage Logs created
- [ ] Final Presentation ready
