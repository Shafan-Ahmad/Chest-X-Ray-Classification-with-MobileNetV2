# Chest X-Ray Classification with MobileNetV2

This project implements a binary classification model for chest X-ray images using **MobileNetV2**. The model predicts whether the X-ray is normal or abnormal. The implementation leverages **PyTorch** and **mixed precision training** for efficiency.

---

## Table of Contents

- [Features](#features)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## Features

- Efficient training using **MobileNetV2** with pre-trained weights.
- Mixed precision training for faster computation and lower memory usage.
- Data preprocessing includes resizing, normalization, and dataset reduction for testing.

---

## Dataset

The dataset is divided into three parts:
- **Train**
- **Validation**
- **Test**

Ensure your dataset is organized in the following structure:

chest_xray/
│
├── train/
│   ├── class_1/
│   └── class_2/
├── val/
│   ├── class_1/
│   └── class_2/
└── test/
├── class_1/
└── class_2/


---

## Requirements

- Python 3.8+
- PyTorch 1.9+ (or compatible with your CUDA version)
- torchvision
- matplotlib
- Google Colab (optional for running in the cloud)

Install the required libraries using the command:
```bash
pip install -r requirements.txt

git clone https://github.com/your-username/chest-xray-classification.git
cd chest-xray-classification

pip install -r requirements.txt

python -m venv env
source env/bin/activate  # On Mac/Linux
env\Scripts\activate     # On Windows


dataset_path = "/path/to/your/chest_xray"

python train.py

python test.py

---

### **Steps to Save the File:**

1. Open the Terminal and navigate to your project folder:
   ```bash
   cd /Users/Shafan/Desktop/chest-xray-project

touch README.md

open -e README.md  # Opens in TextEdit