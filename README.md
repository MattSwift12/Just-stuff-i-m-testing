# 🤖 AI Translation Comparator

> Part of my **Linguistic Engineering Sandbox** (`stuff-im-testing`).

This project is a Python-based tool designed to evaluate and compare the output of different Machine Translation (MT) engines in real-time. It serves as a proof-of-concept for building customized translation environments.

## 🎯 Objective
To facilitate the post-editing process by providing a side-by-side comparison of:
- **Google Translate:** Standard neural machine translation.
- **MyMemory:** Collaborative translation memory (Human + Machine hybrid).

## 🛠️ Tech Stack
* **Python 3.x**: Core logic.
* **Streamlit**: For the interactive web interface.
* **Deep-Translator**: To handle API requests to multiple engines.
* **Pandas**: For data handling (future export features).

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/TU_USUARIO/stuff-im-testing.git](https://github.com/TU_USUARIO/stuff-im-testing.git)
    cd stuff-im-testing
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the app:**
    ```bash
    streamlit run main.py
    ```

4.  The application will open automatically in your browser at `http://localhost:8501`.

## ✨ Features
* **Real-time Comparison:** Input text once, receive multiple translations simultaneously.
* **Language Support:** Configured for major pairs including Spanish, English, Chinese (Simplified), French, and German.
* **Clean UI:** Distraction-free interface focused on the text analysis.

## 🔜 Roadmap (Future Improvements)
* [ ] Integration with DeepL API (requires API Key).
* [ ] "Export to Excel" button for terminology extraction.
* [ ] Sentiment analysis of the source text.

---
*Created by [Tu Nombre] - Exploring the intersection of Language and Code.*
