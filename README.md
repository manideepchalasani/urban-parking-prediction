# urban-parking-prediction

# Urban Parking Spot Availability Prediction using CNN-LSTM and LLMs

This project focuses on forecasting real-time urban parking availability using a hybrid deep learning model that combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM)networks. It also integrates Large Language Models (LLMs)like FLAN-T5 and ChatGPT to generate natural language summaries of model outputs for enhanced usability.

---

## 📌 Problem Statement
Finding real-time parking in metropolitan cities remains a major issue, especially during peak hours. This project predicts the availability of parking spots at various locations based on historical usage patterns, time features, and external factors.

---

##  Key Features
- CNN-LSTM hybrid architecture for spatial-temporal prediction
- Natural language generation using FLAN-T5 and ChatGPT
- Real-time availability predictions across multiple urban zones
- Integration with real-world public datasets (parking sensors, timestamps, occupancy)

---

##  Technologies Used
- **Python**
- **TensorFlow / Keras**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **FLAN-T5 (Google T5)** for summary generation
- **OpenAI’s GPT (ChatGPT)** for interpretability

---

##  Model Architecture
- **CNN Layers**: Capture spatial features (zones, grid-based parking data)
- **LSTM Layers**: Capture sequential and temporal patterns
- **Dense Layers**: Final prediction of availability (binary or percentage)
- **LLMs**: Translate prediction outputs into user-friendly text

---

## Dataset
- Public urban parking datasets
- Cleaned_Activites_Data
- Cleaned_Parking_Zones
- Cleaned_Weather 
- Features include:
  - Timestamp
  - Occupancy status
  - Sensor location
  - Day of week, time of day
  - Weather 

---

## Results
- Achieved **85% accuracy** in forecasting next-15-minute parking availability
- Reduced prediction error using hybrid deep learning vs. traditional LSTM alone
- Generated dynamic summaries like:
  > “Zone 5 is likely to have high parking demand in the next 30 minutes. Consider alternate zones nearby.”

---

## 📄 Folder Structure
