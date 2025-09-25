# A Motion Tracking System using Raspberry Pi

This repository contains the thesis **"A Motion Tracking System using Raspberry Pi"**, which explores the deployment of advanced deep learning–based object tracking algorithms on edge devices. The project demonstrates how computer vision applications can be optimized for low-resource hardware, specifically using a Raspberry Pi combined with a Neural Compute Stick (NCS).

---

## 📖 Abstract
Computer Vision (CV) applications are undergoing a significant revolution, as they are being applied in previously difficult or impossible areas. This includes object detection and tracking within different environments. The development of CV is closely tied to the advancements in Artificial Intelligence (AI) and Deep Learning (DL), which have enabled the creation of powerful algorithms for object tracking and detection. However, these algorithms require significant computational resources and are typically deployed on powerful servers or the cloud. This can be cost-prohibitive and may not be feasible for certain applications or users.  

The proliferation of edge devices, such as Internet of Things (IoT) devices, presents a significant opportunity for the deployment of CV applications. However, deploying these algorithms on edge devices is challenging due to computational power, memory, and storage limitations. To tackle these limitations, recent developments in hardware such as Neural Compute Stick (NCS) accelerator make it possible to increase the inference speed and perform offline computations. Nevertheless, the challenge of deploying deep learning algorithms on edge devices still exists.  

This thesis proposed a DL-based model that follows the tracking-by-detection approach to track multiple objects. The model is deployable in edge computing thanks to an optimization phase that enables deploying the YOLOv8 and DeepSORT on devices with limited resources, namely Raspberry Pi. The experiments conducted on a custom dataset showed that the model, in both the normal and tiny versions, obtained good results in comparison with other state-of-the-art traditional algorithms.  

**Keywords:** Computer Vision, Deep Learning, Internet of Things, Neural Compute Stick, Object Tracking, Object Detection, YOLOv8, DeepSORT, Raspberry Pi.

---

## 📂 Repository Structure
- `thesis.pdf` → Full thesis document.  
- `README.md` → Overview of the project.  
- *(Available upon Request)* `notebooks/` → Example experiments and demo notebooks.  
- *(Available upon Request)* `results/` → Sample outputs, visualizations, or evaluation metrics.  

---

## 📑 Thesis
📄 You can read the full thesis here: [MasterThesis.pdf](https://github.com/zinelabidineleghelimi/MotionTrackingSystem/blob/main/MasterThesis.pdf)  

---

## 🚀 Technologies & Tools
- Raspberry Pi (edge device)  
- Neural Compute Stick (Intel Movidius NCS)  
- YOLOv8 (object detection)  
- DeepSORT (object tracking)  
- Python, OpenCV, PyTorch  

---

## 🔮 Future Work
- Integration with real-time IoT pipelines.  
- Further model compression and pruning.  
- Deployment on alternative edge devices.  

---

## 📬 Contact
If you have questions, feel free to reach out!  
**Author:** [zinelabidineleghelimi.research@gmail.com]  
**Email:** your.email@example.com  
**LinkedIn/GitHub:** [Your Profile Link]  
