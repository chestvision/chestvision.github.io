# 🫁 ChestVision AI

<div align="center">
  <img src="hero-gifer.gif" alt="ChestVision AI Demo" width="150px" style="border-radius: 50%"/>
  <h3>Advanced Chest X-Ray Analysis Powered by AI</h3>
  <img src="https://img.shields.io/badge/TensorFlow-2.0+-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</div>

## 🌟 Overview

ChestVision AI is a state-of-the-art web application that leverages deep learning to assist medical professionals in analyzing chest X-ray images. Our platform offers rapid and accurate detection of various chest-related conditions, making it an invaluable tool for healthcare practitioners.

## ✨ Features

- 🔍 **Multi-Disease Detection**: Capable of identifying 14 different chest conditions
- 🏥 **Pneumonia Specialization**: Dedicated model for pneumonia detection
- 📊 **Real-time Analysis**: Instant results with confidence scores
- 📱 **Responsive Design**: Seamless experience across all devices
- 🔒 **Secure Processing**: Client-side analysis ensuring data privacy

## 🔧 Technical Specifications

### Dataset

- **Training**: 78,468 images from ChestX-ray14 Dataset
- **Validation**: 11,218 images
- **Testing**: 22,432 images

### Supported Conditions

Js
   
    ```const detectedConditions = [
      "Atelectasis", "Cardiomegaly", "Effusion", 
      "Infiltration", "Mass", "Nodule", 
      "Pneumonia", "Pneumothorax", "Consolidation",
      "Edema", "Emphysema", "Fibrosis", 
      "Pleural Thickening", "Hernia"
      ]
      '''
## Get Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chestvision-ai.git
    ```
2. Open **index.html** in your browser or set up a local server:
    ```bash
    python -m http.server 8000
    ```

Then, visit http://localhost:8000 in your browser.


## 💻 Usage

Follow these simple steps to get started with ChestVision AI:

1. **Select your preferred model**  
   Choose between **Multi-Disease Detection** or **Pneumonia Detection** to tailor the analysis for your needs.

2. **Upload a chest X-ray image**  
   Supported formats: **DICOM**, **JPG**, or **PNG**. Simply drag and drop the image into the uploader.

3. **Click "Analyze Image"**  
   Let the AI work its magic and process the image.

4. **View the detailed analysis results**  
   Get instant results with confidence scores for each detected condition.

---

## ⚠️ Disclaimer

> This AI-assisted diagnostic tool is designed to **supplement**, not replace, **professional medical judgment**.  
> Always consult with qualified healthcare professionals for medical decisions.

---

## 🛠️ Technologies Used

### **TensorFlow.js** - Real-Time AI Model Deployment
- **TensorFlow.js** powers the machine learning models deployed directly in the browser. This allows **ChestVision AI** to perform **real-time predictions** and inference, without needing to send sensitive medical data to external servers. The entire process happens on the user's device, ensuring **data privacy** and **speed**.
- The **Multi-Disease Detection Model** was trained by **Bach** using a **complex residual network**, enabling the model to accurately predict **14 different chest-related conditions** from X-ray images. The training process took **3.68 hours** using the **ChestX-ray14 Dataset**, with a total of **78,468 images** for training, **11,218 images** for validation, and **22,432 images** for testing.

### **Particles.js** - Interactive Background Animations
- To elevate the user experience, **Particles.js** adds stunning, interactive particle animations in the background. This dynamic and engaging effect helps guide the user’s focus toward the central content while creating a more immersive environment for image analysis.
- The interactive design responds to user actions such as scrolling and mouse movements, adding an element of fun and delight to the otherwise clinical environment of a medical app.

### **AOS (Animate On Scroll)** - Smooth Scroll Animations
- The **AOS library** is utilized to add smooth and captivating scroll-based animations. These animations trigger as the user scrolls down the page, adding a layer of engagement while also making the interface feel more fluid.
- Whether it's fading in the content, sliding in elements from the side, or other animations, **AOS** ensures the experience remains fresh and visually appealing as users explore the platform.

### **Modern CSS Techniques** - Responsive and Elegant Design
- **Flexbox** and **CSS Grid** were used extensively in the layout to ensure a **responsive**, **flexible**, and **user-friendly interface**. These powerful layout systems ensure that the platform adapts perfectly to any screen size, whether on a mobile, tablet, or desktop.
- **Glassmorphism** was incorporated to create a sleek, **frosted-glass** effect, adding modern aesthetics and enhancing visual clarity. This effect uses translucent backgrounds with subtle blur effects to keep the focus on the content while giving the platform a futuristic look.
  
### Model-Specific Details:

#### **Multi-Disease Detection Model** (14 conditions)
- **Training Time**: 3.68 hours
- **Network Architecture**: Complex residual network designed for accurate feature extraction from chest X-ray images.
- **Dataset**: **ChestX-ray14 Dataset**  
  - **Training Set**: 78,468 images
  - **Validation Set**: 11,218 images
  - **Testing Set**: 22,432 images
- **Supported Conditions**: This model detects 14 chest conditions including **Atelectasis**, **Cardiomegaly**, **Effusion**, and more.

#### **Pneumonia Detection Model** (Binary classification)
- **Training Time**: 22 minutes
- **Network Architecture**: **DenseNet-121**, a highly efficient convolutional neural network (CNN) known for its excellent performance in medical imaging tasks.
- **Dataset**: **Kaggle Chest X-ray dataset**  
  - **Training Set**: 5,863 images
- **Output**: The model classifies X-ray images into **Pneumonia** or **Non-Pneumonia** categories, providing a quick diagnosis for suspected pneumonia cases.

---

## 👥 Meet the Team

<div align="center">
  <table>
    <thead>
      <tr>
        <th>Member</th>
        <th>Role</th>
        <th>GitHub</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Bach</td>
        <td>ML Engineer</td>
        <td><a href="https://github.com/2006coder">@2006coder</a></td>
      </tr>
      <tr>
        <td>Samadhi</td>
        <td>Web Developer</td>
        <td><a href="https://github.com/samadhichandrasena">@samadhichandrasena</a></td>
      </tr>
      <tr>
        <td>Sora</td>
        <td>ML Engineer</td>
        <td><a href="https://github.com/sowada23">@sowada23</a></td>
      </tr>
    </tbody>
  </table>
</div>

---

## 📄 License

Copyright © 2024 **ChestVision AI**. All rights reserved.

---

<div align="center">
  Made with ❤️ at Earlham College
</div>
