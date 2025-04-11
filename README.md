# Hand Sign Recognition with CNN (0 to 5)

A simple convolutional neural network (CNN) model that recognizes static hand signs representing numbers from **0 to 5**. Originally developed as a university project, it's now structured as an open-source educational project for demonstration and reuse.

---

## 🧠 Features

- CNN model built using TensorFlow/Keras
- Trained on grayscale images of hand signs
- Easily test custom input images
- Modular and well-documented notebook

---

## 🗂 Project Structure

```
hand-sign-cnn-0-to-5/
├── Hand_Sign_Recognition_with_CNN_Final.ipynb  # Main notebook
├── datasets/                                   # .h5 training and test data
├── test/                                       # Custom input test images
├── model.h5                                    # Saved trained model (optional)
├── LICENSE                                     # MIT license
└── README.md                                   # Project documentation
```

---

## ⚙️ Installation

Install Python dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook Hand_Sign_Recognition_with_CNN_Final.ipynb
```

---

## 🧪 Usage

1. Train the model using provided `.h5` datasets
2. Test predictions using your own hand sign images placed in `test/`
3. Run the last cell to get predictions from the trained model

---

## 📸 Example

> Image input → CNN model → Predicted class

| Image | Prediction |
|-------|------------|
| ✊     | 0          |
| ✌️     | 2          |
| 🖐     | 5          |

---

## 🧾 Requirements

- Python 3.8+
- TensorFlow
- NumPy
- Matplotlib
- Pillow

Install them with:

```bash
pip install tensorflow numpy matplotlib pillow
```

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙋‍♂️ Author

**Ruslan Sadyrbekov**  
