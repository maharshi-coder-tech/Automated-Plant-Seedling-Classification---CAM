# Automated Plant Seedling Classification with Class Activation Mapping for Effective Weed Management

## Overview
Our results indicate that the **MobileNetV2** based model is highly suitable for real-time applications in precision agriculture, where **accurate and early identification of crop and weed seedlings** is crucial for effective weed management and optimization of crop yield.

## Model Details
The model was trained using a **MobileNetV2** architecture with **transfer learning**. The training process was carried out for **10 epochs** with **early stopping** to prevent overfitting.

### **Training and Validation Performance:**
- **Training Accuracy:** 97.76%  
- **Validation Accuracy:** 97.49%  
- **Training Loss:** 0.0641  
- **Validation Loss:** 0.1139  

### **Test Performance:**
- **Test Loss:** 0.13207  
- **Test Accuracy:** 96.93%  

## **Evaluation Metrics of Proposed Model**
![image](https://github.com/user-attachments/assets/606430df-723e-49f3-8317-e6066b536def)


## **Results**
![image](https://github.com/user-attachments/assets/721a5005-9047-4ce4-be94-f11ff61c7e41)
- **With Heatmap**
![image](https://github.com/user-attachments/assets/766ab95a-10ac-4dd5-8593-fa0838decf5d)



## **Environment Setup**
The following dependencies were used for the project:

- **Python** 3.6  
- **OpenCV** 3.4.1  
- **TensorFlow** 1.8.0 GPU  
- **Keras** 2.1.6  
