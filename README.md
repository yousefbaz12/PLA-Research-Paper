# Deep Learning for Physical-Layer Security in Wireless IoT (WIoT)
<p align="center">
  <img src="https://github.com/user-attachments/assets/6dfce373-9124-4f4d-86d2-a2dbc58294d5?raw=true" alt="PLA Security" width="500"/>
</p>

**A comprehensive survey, experimental analysis, and future outlooks on leveraging deep learning to enhance physical-layer security in Wireless Internet of Things (WIoT) systems.**

This repository accompanies the research paper *"Deep Learning for Physical-Layer Security in Wireless Internet of Things (WIoT): A Survey, Experimental Analysis, and Outlooks"*. It provides code, datasets, research versions, proposal versions, high level architecture and prototype to explore and reproduce the application of deep learning (DL) techniques—such as Convolutional Neural Networks (CNNs), Reinforcement Learning (RL), and Generative Adversarial Networks (GANs)—to strengthen physical-layer security (PLS) in WIoT systems. The work addresses the growing security challenges in WIoT, driven by the proliferation of over 25 billion IoT devices by 2025, and proposes lightweight, adaptive solutions for resource-constrained environments.

---

## 1. Overview

### 1.1 Research Context
The Wireless Internet of Things (WIoT) integrates billions of low-power devices—sensors, actuators, and wearables—into modern infrastructure, enabling real-time data exchange in applications like smart cities, healthcare, and Industry 4.0. However, the wireless medium’s inherent vulnerabilities expose WIoT to threats such as eavesdropping, jamming, and spoofing. Traditional upper-layer cryptographic methods (e.g., RSA, AES) are computationally intensive and ill-suited for WIoT’s resource constraints, prompting the exploration of PLS, which leverages physical channel properties like Channel State Information (CSI) and RF fingerprints.

### 1.2 Role of Deep Learning
DL enhances PLS by adapting to dynamic WIoT environments and detecting complex threats in real time. This survey reviews DL techniques from 2018-2025, provides experimental validation, and outlines future directions, including 6G integration and adversarial resilience. It bridges theoretical advancements with practical implementations, addressing gaps in prior studies like the lack of experimental evidence and narrow focus on authentication.

---

## 2. Repository Contents

### :computer: 2.1 Code
- This subsection contains the **Source Code** developed to implement and validate deep learning (DL) techniques for enhancing physical-layer security (PLS) in 
  Wireless Internet of Things (WIoT) systems. It includes notebooks downloaded from kaggle in **ipynb** files  
- The code is designed to ensure reproducibility of experimental results presented in the paper.

### :floppy_disk: 2.2 Datasets
- The subsection contains datasets provided to support the experimental analysis of DL-based PLS in WIoT  They comprise real-world data, such as RF signal captures 
  and Channel State Information (CSI) from IoT devices and synthetic datasets simulating WIoT channel conditions.

### :globe_with_meridians: 2.3 Research Paper Versions 
- This subsection archives versions of the research paper , it includes the multiple versions of the edited one based on the new requirements and  will be updated 
  upon new tasks, ensuring traceability of the research evolution.

### 📋 2.4 Proposal Versions 
- This area stores initial and revised research proposals that outline the objectives, methodology, and scope of the study. These documents highlight the 
  motivation for applying DL to PLS in WIoT 

### :triangular_ruler: 2.5 High Level Architecture , Diagrams and Use Case 
- This subsection presents the high-level architecture of DL-based PLS systems for WIoT, accompanied by diagrams  and use cases such as smart city security  It 
  also includes a prototype implementation demonstrating real-time threat detection (e.g., jamming mitigation ,spoofing,.. using DL ) These materials illustrate 
  the practical application and system design, supporting the experimental and theoretical contributions outlined.

---

