# 🧪 Walkthrough – How to Use the Phishing Detector (v1)

This guide walks through how to use the Teachable Machine-based phishing detector available at:
👉 [https://100psycho007.github.io/ai-phishing-url-detector/](https://100psycho007.github.io/ai-phishing-url-detector/)

---

## 📥 Step 1: Upload a Screenshot

* Click the **"Choose File"** button
* Select a PNG or JPG screenshot of a website (including the address bar if possible)

**Example:**

> Upload a screenshot of `google.com` or a suspicious login page

---

## 🔍 Step 2: Let the AI Predict

* Once uploaded, the image is previewed on the page
* The model automatically runs and shows one of two results:

  * ✅ `Safe` — classified as a legitimate website
  * 🚫 `Phishing` — flagged as potentially dangerous

---

## 💬 Step 3: Read the Confidence Score

* The model shows something like:

  ```
  🔍 Prediction: Phishing (86.7%)
  ```
* This means it is 86.7% confident the image belongs to the `Phishing` class

---

## 💡 Best Practices

* Try to include **full browser window screenshots** with visible URL bars
* Avoid blurry or cropped images
* The model is trained on visuals — it does **not** read the text inside the screenshot

---

## ⚠️ Known Limitations

* Might misclassify professional-looking phishing pages
* Not reliable without full screenshot context

---

## 🚀 What’s Next?

The next version (v2) will:

* Use **OCR** to extract URL
* Use **GPT + VirusTotal** to analyze the actual text
* Combine visual + URL intelligence for high accuracy

Stay tuned!
