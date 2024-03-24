# 🩺 Skin Lesion Segmentation & Classification  

Deep learning project for **automated skin lesion analysis** – including **segmentation** (FCN, UNet) and **classification** (CNN into 7 categories).  
I trained & fine-tuned models on benchmark medical datasets to achieve strong performance on both tasks.  

---

## 📊 Datasets Used
- **[PH² Database](https://www.fc.up.pt/addi/ph2%20database.html)** – 200 dermoscopic images (segmentation)  
- **[HAM10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)** – 10,015 images (classification)  

Example samples:  
<p align="center">
  <img src="images/PH2_image_sample.png" width="300">
  <img src="images/HAM10000_image_sample.png" width="300">
</p>

---

## 🧠 Models

### 🔹 Segmentation
1. **Fully Convolutional Network (FCN)**  
   <p align="center">
     <img src="images/FCN.png" width="400">
   </p>  

2. **U-Net**  
   <p align="center">
     <img src="images/UNet.png" width="400">
   </p>  

### 🔹 Classification
1. **Convolutional Neural Network (CNN)**  
   <p align="center">
     <img src="images/CNN-Image-Classifier-Model-shows-an-overview-of-convolutional-neural-network.png" width="500">
   </p>  

---

## 🚀 Results

### Segmentation Results
| Model | IOU (Test) | Dice | Accuracy |
|-------|------------|------|----------|
| **FCN** | 94.08 | 76.05 | 95.22% |
| **U-Net** | 94.87 | 88.57 | 94.88% |

<p align="center">
  <img src="images/Skin_Lesion_Segmentation_Result_FCN.png" width="400">
  <img src="images/Skin_Lesion_Segmentation_Result_UNet.png" width="400">
</p>  

Training curves:  
<p align="center">
  <img src="images/Skin_Lesion_Segmentation_Accuracy-Loss_FCN.png" width="400">
  <img src="images/Skin_Lesion_Segmentation_Accuracy-Loss_UNet.png" width="400">
</p>  

---

### Classification Results
7-class skin lesion classification using CNN:  

<p align="center">
  <img src="images/Skin_Lesion_Classification.png" width="400">
  <img src="images/Skin_Classification_model.png" width="400">
</p>  

Training performance:  
<p align="center">
  <img src="images/Skin_Lesion_Classification_accuracy.png" width="400">
  <img src="images/Skin_Lesion_Classification_Loss.png" width="400">
</p>  

---

## 🛠️ Tech Stack
- Python, TensorFlow / Keras  
- Jupyter Notebooks  
- GPU Training + Fine-Tuning  

---

## 🌟 Key Takeaway
This project demonstrates **end-to-end medical image analysis**, with **segmentation + classification pipelines** trained and fine-tuned for dermatology applications.  

---
