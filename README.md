🌟 BMI Predictor App
SwiftUI • TensorFlow Lite • On-Device Machine Learning
A beautifully designed BMI Prediction App built using SwiftUI and powered by a TensorFlow Lite model for fast & secure on-device inference.
This project blends modern iOS UI design, machine learning, and health analytics to deliver a smooth and intuitive user experience.
<div align="center">
🧠 ML-Powered BMI Classification
⚡ Real-Time Predictions
🎨 Elegant SwiftUI Interface
🔒 100% Offline — Privacy First
</div>
🚀 Overview
The BMI Predictor app allows users to input lifestyle and health parameters such as age, weight, height, exercise, and sleep habits.
Using a custom TensorFlow Lite (.tflite) model, the app predicts:
BMI Value
BMI Category (Underweight, Normal, Overweight, Obese)
All predictions happen instantly and locally, making the app both fast and privacy-focused.
✨ Key Features
🧮 Smart BMI Prediction
Calculates BMI using ML, not just formulas
Adjusts based on lifestyle factors
Provides meaningful BMI category output
🧠 TensorFlow Lite Integration
On-device inference
Works offline
Optimized .tflite model
🎨 Modern SwiftUI UI
Clean, minimal, card-based input design
Smooth interactive components
Adaptive layout for all iPhones
🔧 Advanced Input Options
Age, Height, Weight
Sleep Duration
Diet Quality
Alcohol Intake
Exercise Frequency
Gender
Smoking
Chronic Disease
🔐 Privacy Respecting
No user data is uploaded or stored.
Everything stays on the device.
🧠 Machine Learning Model
The ML model (bodexmodel.tflite) was trained using:
Python
TensorFlow
Jupyter Notebook
Input: 10 lifestyle & biometric features
Output: BMI prediction (float), plus category mapping in app logic
