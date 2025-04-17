## 📌 Project Overview

The system performs **trigger word detection**, similar to "Hey Siri" or "OK Google." It involves two main phases:

1. **🔊 Audio Synthesis**  
   - Generates a synthetic dataset by inserting trigger words (e.g., "activate") into background audio  
   - Produces training and dev sets with labeled audio examples

2. **🧠 Model Training**  
   - A neural network model (based on RNNs) is trained to detect the trigger word's presence and position in audio clips  
   - Outputs a chime or signal when the word is detected

## 📁 Required Data

Download the training and dev sets before running the code:

- [XY_train.zip](https://drive.google.com/drive/folders/18FOdz6mlofD-Nz20ol6HyssO36-8xYmZ?usp=share_link)  
- [XY_dev.zip](https://drive.google.com/drive/folders/1VFhiiwMfXm7Kj6OOklDAoASqj9pcZnPE?usp=share_link)

> Unzip both folders and place them in the project directory.
