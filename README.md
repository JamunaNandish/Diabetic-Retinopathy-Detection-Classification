# Diabetic Retinopathy Detection & Classification 🩺👁️

This project uses deep learning to detect and classify diabetic retinopathy from retinal images. The goal is to assist early diagnosis and prevent vision loss by identifying the severity of retinopathy.

---

## 🧠 Project Objective

- Automatically classify the stage of diabetic retinopathy (from 0 to 4)
- Use a Convolutional Neural Network (CNN) for image classification
- Train and evaluate using Kaggle’s Diabetic Retinopathy dataset

---

## 📂 Project Structure

```
diabetic-retinopathy-detection/
│
├── data/                  # Image dataset (organized by class folders)
├── notebooks/             # Jupyter notebooks for EDA, training, etc.
├── models/                # Saved models (h5/pth files)
├── venv/                  # Virtual environment (not tracked by Git)
├── requirements.txt       # All Python dependencies
├── README.md              # You are here
└── main.py                # Entry point (optional)
```

---

## 🔧 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/<your-username>/diabetic-retinopathy-detection.git
cd diabetic-retinopathy-detection

# Create virtual environment
python -m venv venv
source venv/Scripts/activate    # or: source venv/bin/activate (Linux/macOS)

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 To Do Next

- [ ] Load & visualize sample images
- [ ] Preprocess image data (resize, normalize)
- [ ] Build CNN model
- [ ] Train & evaluate model
- [ ] Save trained model & plot metrics

---

## 📊 Dataset

We'll use the [Kaggle Diabetic Retinopathy Detection dataset](https://www.kaggle.com/c/diabetic-retinopathy-detection/data), which contains labeled retinal images.

---

## ✨ Author

**Jamuna Nandish**  
Passionate about AI, healthcare, and building impactful solutions.

---

## 📌 License

This project is for educational purposes. Model is not for real-world diagnosis.
