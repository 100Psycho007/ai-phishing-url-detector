# 🛡️ AI Phishing URL Detector (v1)

> A browser-based phishing detector that uses image-based classification via [Teachable Machine](https://teachablemachine.withgoogle.com/). Upload a screenshot of a website, and this tool will predict if it's **Phishing** or **Safe**.

---

## 📌 Live Demo

👉 [Visit the Live Site](https://100psycho007.github.io/ai-phishing-url-detector/)

---

## 📸 How It Works

1. Upload a screenshot containing a visible website URL.
2. A pre-trained MobileNet model (via Teachable Machine) classifies it as:

   * ✅ Safe
   * 🚫 Phishing
3. Results are displayed instantly on the webpage.

> **Note:** Accuracy depends on the training dataset. This version is a proof-of-concept.

---

## ⚙️ Tech Stack

* HTML, CSS, JavaScript
* TensorFlow\.js
* Teachable Machine (MobileNet)
* GitHub Pages for deployment

---

## 🗂️ Folder Structure

```
├── index.html          # UI code
├── model/              # Exported TM model (model.json, metadata.json, weights.bin)
├── docs/               # 📄 Documentation & screenshots (to be added)
├── app/                # (optional) alternate versioning space for future refactor
└── README.md           # You're here
```

---

## 📁 docs/

| File             | Description                          |
| ---------------- | ------------------------------------ |
| `screenshots/`   | UI and sample result images          |
| `model-info.md`  | Notes on training params and classes |
| `walkthrough.md` | Simple usage guide with visuals      |

> 📝 *To be added by contributor*

---

## 🚀 How to Use

1. Go to the [Live Demo](https://100psycho007.github.io/ai-phishing-url-detector/)
2. Upload a screenshot image
3. See the prediction result below the image

---

## 🧪 Example Screenshots

📍 *(Place these in `docs/screenshots/`)*

* Safe site prediction ✅
* Phishing site prediction 🚫

---

## 📈 Accuracy

This version uses a small dataset with basic image classification.

| Model Type | Source            | Notes                                                   |
| ---------- | ----------------- | ------------------------------------------------------- |
| MobileNet  | Teachable Machine | Lightweight, fast, less accurate for fine-grained tasks |

### Known Limitations

* May misclassify clever phishing designs
* Cannot analyze URL text deeply
* Only works with visible screenshots

---

## 📦 License

[MIT License](LICENSE)

---

## 🚧 What's Next (v2 Preview)

A smarter hybrid phishing detector with:

* ✅ OCR (Tesseract.js) to extract URLs
* ✅ GPT/OpenRouter AI check
* ✅ VirusTotal API verification

> Follow progress in the upcoming `smart-phishing-detector` repo.

---

## 👤 Author

**[100Psycho007](https://github.com/100Psycho007)** – Final year BSc Botany + Zoology student interested in AI x Cybersecurity.
