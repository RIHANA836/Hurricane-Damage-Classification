#  Hurricane Damage Classification Using CNN  

## 📌 Project Overview  
This project leverages **Convolutional Neural Networks (CNNs)** to classify images as either **damage** or **no damage**, assisting in **post-hurricane disaster assessment**.  

## 📊 Dataset  
- **Training Set**: Labeled images of **damaged** and **non-damaged** areas  
- **Testing Set**: Separate images for performance evaluation  

## 🔧 Technologies & Libraries Used  
- **Python**, with:  
  - **Pandas** and **NumPy** for data processing  
  - **Seaborn** and **Matplotlib** for visualization  
  - **TensorFlow** and **Keras** for deep learning  
  - **Scikit-learn** for evaluation metrics  

## 🔄 Preprocessing Steps  
- Loaded and **shuffled** images for better learning  
- Resized images to match **CNN input dimensions**  
- Split dataset into **training and testing sets**  

## 🤖 Model Architecture  
- **Conv2D Layers**: Extract spatial patterns  
- **MaxPooling Layers**: Reduce feature map size  
- **Flatten Layer**: Convert matrices into a vector  
- **Dense Layers**: Fully connected layers for prediction  
- **Sigmoid Activation**: Final layer for **binary classification**  

## 📈 Results & Evaluation  
- **Accuracy** evaluated on test data  
- **Confusion matrix** visualization  

## 📚 Conclusion  
This project demonstrates how **deep learning** can be applied for **disaster impact assessment**, helping automate **damage detection** using **CNN models**.  
