# 🌿 Plant Disease Detection System for Sustainable Agriculture

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)

> A CNN-based plant disease classifier trained on 50,000+ images across 38 disease categories. Built during the AICTE AI/ML Internship — TechSaksham (Microsoft & SAP CSR Initiative), under the guidance of Dr. P. Raja.

**[🚀 Live Demo](https://plantdiseaseidentification-fjnhtuphau6ftksajmlfa4.streamlit.app)**

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| Training Accuracy | 98.06% |
| Validation Accuracy | 94.47% |
| Disease Classes | 38 |
| Dataset Size | 50,000+ images |
| Image Input Size | 128 × 128 px |

---

## 🧠 How It Works

1. User uploads a leaf image via the Streamlit interface
2. Image is resized to 128×128 pixels and preprocessed
3. CNN model extracts features through convolutional and pooling layers
4. Fully connected dense layers classify the disease
5. App returns the predicted disease class with confidence

---

## 🏗️ Model Architecture

- **Convolutional layers** — feature extraction from leaf images
- **Max-pooling layers** — dimensionality reduction
- **Dropout layers** — prevent overfitting
- **Dense layers** — final disease classification
- **Optimizer:** Adam
- **Loss Function:** Categorical Cross-Entropy
- **Epochs:** 7 | **Batch Size:** 32

---

## 🌱 Supported Plants & Diseases (38 Classes)

| Plant | Diseases Detected |
|---|---|
| Apple | Scab, Black Rot, Cedar Apple Rust, Healthy |
| Tomato | Bacterial Spot, Early Blight, Late Blight, Leaf Mold, Septoria Leaf Spot, Spider Mites, Target Spot, Yellow Leaf Curl Virus, Mosaic Virus, Healthy |
| Potato | Early Blight, Late Blight, Healthy |
| Corn | Cercospora Leaf Spot, Common Rust, Northern Leaf Blight, Healthy |
| Grape | Black Rot, Esca (Black Measles), Leaf Blight, Healthy |
| Peach | Bacterial Spot, Healthy |
| Pepper | Bacterial Spot, Healthy |
| Strawberry | Leaf Scorch, Healthy |
| Orange | Huanglongbing (Citrus Greening) |
| Blueberry | Healthy |
| Cherry | Powdery Mildew, Healthy |
| Raspberry | Healthy |
| Soybean | Healthy |
| Squash | Powdery Mildew |

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone https://github.com/SID1014/Plant_Disease_Identification.git
cd Plant_Disease_Identification

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run main.py
```

---

## 📁 Project Structure

```
Plant_Disease_Identification/
│
├── app.py                          # Streamlit app
├── trained_plant_disease_model.keras # Trained CNN model
├── requirements.txt                 # Dependencies
└── README.md
```

---

## 🛠️ Tech Stack

- **Model:** TensorFlow / Keras (CNN)
- **Interface:** Streamlit
- **Dataset:** PlantVillage (Kaggle)
- **Language:** Python 3.8

---

## 📌 Dataset

Trained on the [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) — an open dataset of 50,000+ labeled images of healthy and diseased plant leaves across 38 categories.

---

## 🔮 Future Improvements

- Add transfer learning (VGG16 / ResNet) for higher accuracy
- Expand to more crop varieties
- Add disease management tips alongside predictions
- Mobile-friendly deployment

---

## 🏆 Built During

**AICTE AI/ML Internship — TechSaksham**
A joint CSR initiative of **Microsoft & SAP**, implemented by Edunet Foundation.
Guided by **Dr. P. Raja**
