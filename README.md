# Object Detection from Scratch Using a Simplified YOLO Architecture

## Overview

Completed a custom object detection project using a simplified YOLO-style model. The goal was to detect a single object class (such as cats) in images by dividing the input into a 7×7 grid and predicting bounding box coordinates along with objectness scores.

## Highlights

- Built a custom model using a **ResNet-34 backbone**, modified for object detection  
- Designed a **YOLO-style loss function** to jointly learn objectness and bounding box regression  
- Trained the model from scratch using a small, labeled dataset  
- Used **Albumentations** for robust data augmentation  
- Visualized both ground truth and predicted bounding boxes on sample images

## Final Results

- **Train Loss:** 63.43  
- **Train IoU:** 0.91  
- **Test Loss:** 61.44  
- **Test IoU:** 0.72

These results indicate that the model was able to generalize reasonably well, even with limited data and a simplified architecture.

## Tools and Libraries

- **Framework:** PyTorch  
- **Backbone:** ResNet-34  
- **Augmentation:** Albumentations  
- **Visualization:** Matplotlib

## Key Learnings

This project helped me gain deeper insight into:

- Designing custom CNN-based architectures for object detection  
- Implementing bounding box regression and IOU evaluation  
- Debugging training dynamics and monitoring performance  
- Visualizing and interpreting model outputs effectively
<img width="436" height="441" alt="image" src="https://github.com/user-attachments/assets/5d5284ba-fb8b-4ca9-94a0-45561a980731" />
<img width="426" height="436" alt="image" src="https://github.com/user-attachments/assets/abd0faf5-4f4a-48a6-b78e-69eddd43c2b8" />
<img width="436" height="437" alt="image" src="https://github.com/user-attachments/assets/a845a2f2-aca2-47b9-9826-da555724f169" />
<img width="437" height="431" alt="image" src="https://github.com/user-attachments/assets/76f441e2-da0e-4994-ab28-663d69ffc174" />




