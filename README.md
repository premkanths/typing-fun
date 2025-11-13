
# **Learn Fun Typing Test**

### **🔗 Live Demo:**

👉 [https://premkanths.github.io/typing-fun/](https://premkanths.github.io/typing-fun/)

A modern, Monkeytype-inspired typing test built with **vanilla HTML, CSS, and JavaScript**. It features real-time WPM tracking, dynamic text generation using **Google Gemini API**, customizable themes, sound effects, and a clean responsive interface.

---

## 🚀 **Project Overview**

**Learn Fun** is designed to make typing practice engaging and customizable. Users can choose typing durations, select themes, switch fonts, enable sounds, and even generate entirely new typing passages using AI prompts.

The app is simple, fast, and works entirely in the browser—no backend required.

---

## ✨ **Features**

### 🔹 **Dynamic Content Generation**

* Enter any theme (e.g., *"short sci-fi story"*).
* The **Gemini API** generates a new typing passage instantly.

### 🔹 **Real-Time Typing Feedback**

* Correct letters highlight in **blue**.
* Incorrect letters highlight in **red**.

### 🔹 **Customizable Experience**

* Light, Dark, and Retro themes
* Multiple font styles
* Test durations: **15s, 30s, 60s, 120s**

### 🔹 **Full Audio Control**

* Toggle **spacebar click sound**
* Toggle **voice pronunciation** (Web Speech API)

### 🔹 **Advanced Typing Logic**

* Smooth error handling
* Backspace across previous words
* Accurate WPM and accuracy calculation

### 🔹 **Fully Responsive**

* Works perfectly on both **desktop and mobile**.

---

## 🛠️ **How to Run Locally**

Because this is a fully client-side app, you can run it directly in your browser.

### **1. Clone the Repository**

```bash
git clone https://github.com/YOUR_USERNAME/learn-fun-typing-test.git
```

### **2. Open the App**

* Go to the cloned folder
* Open **index.html** in any browser
* Done! 🎉

---

## ⚠️ **Important: Dynamic Content Generation & API Key**

The "Generate Content" button uses the **Gemini API**.


### If you want to change the key:

1. Get a new key from **Google AI Studio**
2. Open `index.html`
3. Find this line:

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

4. Replace it with your new key.

---

## 🧰 **Technologies Used**

* **HTML5** – Structure
* **CSS3** – Themes, layout, animations
* **JavaScript (Vanilla)** – Typing logic, WPM calculations, input handling
* **Web Speech API** – Word pronunciation
* **Web Audio API** – Spacebar click sounds
* **Google Gemini API** – Dynamic typing content generation

---

## 📜 **License**

This project is completely open-source.
You may add a license such as **MIT** if needed.

---

