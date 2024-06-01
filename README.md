# Mini-Project
  This is the repository created based on my mini project which was done in 6th sem.
# Dataset:
   https://www.kaggle.com/arjuntejaswi/plant-village
# Requirments:
   matplotlib
   numpy
   notebook
   tensorflow-addons
   tensorflow-model-optimization
   tensorflow==2.5
   flask
# Introduction:
   Agriculture plays a pivotal role in sustaining the global population, with potatoes being one of the most widely grown and consumed crops worldwide. However, potato plants are susceptible to a variety of diseases like early blight disease, late blight disease and other rust that can significantly impact yield and quality. Early detection and diagnosis of these diseases are crucial for effective management and control, minimizing losses, and ensuring food security.

# Objective:
  The primary objective of this project is to develop an automated system for detecting diseases in potato leaves using deep learning techniques. This system leverages the power of TensorFlow and Keras for building and training a convolutional neural network (CNN) model to classify images of potato leaves into healthy or diseased categories. Additionally, a user-friendly web interface is developed using Flask, allowing farmers and agricultural professionals to upload leaf images and receive instant disease diagnoses.

# Components of the System:
1. Data Collection and Preprocessing:
   The system utilizes a dataset containing images of healthy and diseased potato leaves. These images are preprocessed to enhance model performance, including resizing, normalization, and augmentation to increase the dataset's diversity.
2. Model Development:
   TensorFlow and Keras, popular frameworks for deep learning, are employed to develop a convolutional neural network (CNN) capable of classifying potato leaf images. The CNN architecture is designed to automatically extract features from the images, learning patterns that distinguish healthy leaves from those affected by various diseases.
3. Training and Evaluation:
    The model is trained on the preprocessed dataset, with techniques such as data augmentation and regularization applied to prevent overfitting. The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Hyperparameter tuning is performed to optimize the model's performance.
4. Web Interface Development:
   Flask, a lightweight web framework for Python, is used to develop the front-end interface. This web application allows users to upload images of potato leaves and obtain real-time predictions on their health status. The interface is designed to be intuitive and accessible, ensuring ease of use for individuals with varying levels of technical expertise.
5. Deployment and Integration:
   The trained model is deployed as a web service using Flask, making it accessible to end-users. The web application integrates the model, providing a seamless experience where users can simply upload an image and receive diagnostic results. Additionally, the system can be expanded to include more features, such as providing recommendations for treatment based on the detected disease.

# Conclusion:
  This project demonstrates the potential of combining deep learning with web technologies to address real-world agricultural challenges. By automating the detection of potato leaf diseases, the system aims to assist farmers in making informed decisions, ultimately contributing to improved crop management and productivity. The integration of TensorFlow, Keras, and Flask provides a robust and scalable solution that can be adapted for various types of crops and diseases, showcasing the versatility and impact of modern AI-driven approaches in agriculture.
