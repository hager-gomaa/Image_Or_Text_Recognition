# 🔢 Image Recognition (Basic) — Handwritten Digit Classifier

A basic image recognition project that trains a Support Vector Machine (SVM) classifier to recognize handwritten digits (0–9) from 8x8 grayscale images, then visualizes predictions against the actual labels.

## 📌 Overview

| | |
|---|---|
| **Goal** | Implement a basic image recognition task using available libraries |
| **Algorithm** | Support Vector Classifier (SVM) |
| **Dataset** | `digits` dataset from scikit-learn (1,797 images, 8x8 pixels, 10 classes) |
| **Language** | Python 3 |
| **Dependencies** | `scikit-learn`, `matplotlib` |

## ✨ Features

- Loads and inspects the handwritten digits dataset
- Splits data into training and testing sets
- Trains an `SVC` model to recognize digits
- Reports overall model accuracy on the test set
- Performs recognition on sample images and prints predicted vs. actual labels
- Saves a visual output (`digit_recognition_output.png`) showing sample digit images with their predictions

## 🛠️ Key Skills Demonstrated

- Using AI/ML libraries (scikit-learn)
- Understanding and interpreting model outputs
- Image data handling (pixel arrays as features)
- Data visualization with Matplotlib

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- scikit-learn
- matplotlib

```bash
pip install scikit-learn matplotlib
```

### Run it
```bash
python project4_image_recognition.py
```

### Example output
```
Dataset shape: (1797, 64)
Model accuracy on test set: 98.89%
Sample 1: Predicted = 6, Actual = 6
Sample 2: Predicted = 9, Actual = 9
Sample 3: Predicted = 3, Actual = 3
Sample 4: Predicted = 7, Actual = 7
Sample 5: Predicted = 2, Actual = 2

Output image saved as digit_recognition_output.png
```

![Sample digit predictions](digit_recognition_output.png)

## 📂 Project Structure
```
.
├── project4_image_recognition.py
└── digit_recognition_output.png   # generated after running the script
```

## 🔮 Possible Extensions
- Swap in the larger MNIST dataset (28x28 images) for a tougher challenge
- Try a CNN with TensorFlow/Keras or PyTorch for deep learning–based recognition
- Extend to real photo input using OpenCV for preprocessing
- Add a simple Streamlit interface to upload and classify a custom digit drawing

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
