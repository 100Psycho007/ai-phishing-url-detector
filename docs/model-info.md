# 🧠 Model Info – AI Phishing URL Detector (v1)

This file documents the configuration and structure of the Teachable Machine model used in v1 of the phishing detector.

---

## 📦 Model Architecture

| Property       | Value              |
| -------------- | ------------------ |
| Model Type     | MobileNet (image)  |
| Framework      | TensorFlow\.js     |
| Platform       | Teachable Machine  |
| Input Type     | Image (screenshot) |
| Output Classes | 2                  |
| Classes        | `Phishing`, `Safe` |

---

## ⚙️ Training Configuration

| Setting       | Value           |
| ------------- | --------------- |
| Epochs        | 50              |
| Batch Size    | 16              |
| Learning Rate | 0.001 (default) |
| Image Size    | 224x224 px      |

> 📝 *Training was done in-browser via Teachable Machine’s UI using uploaded screenshot data.*

---

## 📁 Model Files

Located in the `model/` folder:

* `model.json` – Model topology
* `metadata.json` – Class names and config
* `weights.bin` – Model weights

---

## 📌 Notes

* \~100 total images used (50 per class recommended minimum)
* Accuracy limited due to small dataset and lack of domain-based features
* Works only on screenshots with visible content and URL

---

## 🚧 Future Plans

In v2, the model will be replaced or supplemented with:

* Text-based features (OCR + GPT)
* Real-world malware/VT lookup
* Larger dataset trained via Python/Keras or similar

> This model serves as a quick image-based proof-of-concept.

