# FACIAL EMOTION DETECTION USING DL

# 😊 Facial Emotion Detection

This project aims to build a **Facial Emotion Detection System** using a machine learning model trained on the **FER2013** dataset. The system classifies facial expressions into seven categories: **Anger, Disgust, Fear, Happy, Sad, Surprise, Neutral**.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Colab](https://img.shields.io/badge/Google-Colab-brightgreen.svg)
![Emotion Detection](https://img.shields.io/badge/Emotion%20Detection-Deep%20Learning-blueviolet.svg)

---

## 📑 Features
- **Data Loading:** Reads the FER2013 dataset.
- **Data Preprocessing:** Prepares the data for training and validation.
- **Model Training:** Uses TensorFlow for training a neural network model.
- **Emotion Mapping:** Maps predicted labels to emotion categories.

---

## 📂 Project Structure

🚀 How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/facial-emotion-detection.git
Open the notebook in Google Colab:
sh
Copy
Edit
https://colab.research.google.com/
Follow the steps in the notebook:
Mount Google Drive.
Load and preprocess the dataset.
Train the model.
Evaluate and visualize the results.
🧰 Requirements
Python 3.8 or higher
TensorFlow 2.x
Pandas, NumPy, Matplotlib
Google Colab for execution
Install the required packages:

sh
Copy
Edit
pip install tensorflow pandas numpy matplotlib
📊 Sample Code
python
# Load the dataset
df = pd.read_csv("/content/drive/MyDrive/fer2013/fer2013.csv")

# Label to emotion mapping
label_to_text = {0: 'Anger', 1: 'Disgust', 2: 'Fear', 3: 'Happy', 4: 'Sad', 5: 'Surprise', 6: 'Neutral'}

# Display the unique emotions in the dataset
print(df.emotion.unique())

# Load the dataset
df = pd.read_csv("/content/drive/MyDrive/fer2013/fer2013.csv")

# Label to emotion mapping
label_to_text = {0: 'Anger', 1: 'Disgust', 2: 'Fear', 3: 'Happy', 4: 'Sad', 5: 'Surprise', 6: 'Neutral'}

# Display the unique emotions in the dataset
print(df.emotion.unique())
🛡️ License
This project is licensed under the MIT License. See the LICENSE file for details.

💡 Future Improvements
Add a more robust CNN model.
Implement real-time emotion detection using a webcam.
Deploy the model as a web application.
