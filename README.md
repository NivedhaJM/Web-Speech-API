# 🗣️ Text-to-Speech Web App

A simple browser-based app that converts text input into speech using the **Web Speech API**. Just type your text and click **Play Converted Sound** — your browser will speak it aloud!

---

## 🚀 Features

* Converts any typed text into speech.
* Uses the browser's built-in **SpeechSynthesis** (no extra libraries required).
* Simple and user-friendly interface.
* Displays an error if no text is entered.

---

## 🛠️ Technologies Used

* **HTML** – Structure
* **CSS** – Basic styling (assumed)
* **JavaScript** – Event handling and speech logic
* **Web Speech API (SpeechSynthesis)** – For text-to-speech conversion

---

## 📂 How to Use

1. Open `main.html` in a modern web browser (Chrome, Edge, Firefox, etc.).
2. Type any text into the text area.
3. Click the **Play Converted Sound** button.
4. The browser will read your text aloud.
5. If no text is entered, it shows an error message.

---

## 📄 Example Code Snippet

```javascript
const speechSynth = window.speechSynthesis;
const newUtter = new SpeechSynthesisUtterance(enteredText);
speechSynth.speak(newUtter);
```

---

## 📝 Sample Output

If you type:
`Hello, how are you?`

The browser will speak:

> “Hello, how are you?”

---

## 📌 Note

* This works only in browsers that support the **Web Speech API**.
* Ensure your system volume is on and not muted.

---

## 📜 License

This project is open-source and free to use.
