## 🧠 Arabic Spell Checker – NLP-based Contextual Correction Tool

### 📋 Overview

This project presents an **Arabic spell checker** that leverages **Natural Language Processing (NLP)** techniques to provide intelligent, context-aware corrections. It aims to improve the accuracy and reliability of spell checking for Arabic, one of the most morphologically rich and complex languages.

### 🎯 Objectives

* Detect misspelled Arabic words.
* Suggest corrections based on **context** and **linguistic patterns**.
* Compare traditional edit-distance methods with probabilistic language models.

---

### 🧩 Methodology

#### 🔹 Dataset

* Dictionary dataset: **~890,000 Arabic words** for Levenshtein algorithm.
* Arabic corpus: **8,660 lines** for the n-gram model.
* Both datasets were collected from open online linguistic resources.

#### 🔹 Algorithms Used

1. **Levenshtein Distance** – for edit-distance-based correction.
2. **N-gram Language Model** – for context-based probability scoring.
3. **Beam Search** – for combining frequency-based scoring with contextual correction.
4. **Tokenization, Stemming, POS Tagging** – for text preprocessing and linguistic analysis.

---

### 🛠️ Tools & Technologies

* **Language:** Python
* **Libraries:** NLTK, NumPy, Tkinter
* **NLP Techniques:** Tokenization, Stemming, POS Tagging
* **Interface:** GUI built using Tkinter

---

### 🧮 Results

* The **Levenshtein method** effectively handled minor typographical errors (insertions, deletions, substitutions).
* The **N-gram model** achieved higher contextual accuracy and better prediction of common word sequences.
* Combining both approaches enhanced overall correction accuracy and flexibility.

---

### 🧰 How to Run

1. Open the `UI` folder.
2. Run the file:

   ```bash
   main.exe
   ```

   or

   ```bash
   python main.py
   ```
3. Enter Arabic text in the GUI to test the spell checker interactively.

---

### 👥 Group Members

* **Jalila Moaddi** – [1201611@student.birzeit.edu](mailto:1201611@student.birzeit.edu)
* **Maryan Kassis** – [1200861@student.birzeit.edu](mailto:1200861@student.birzeit.edu)
* **Obada Hattab** – [1171616@student.birzeit.edu](mailto:1171616@student.birzeit.edu)

Department of Electrical and Computer Engineering – **Birzeit University**

---

### 🔮 Future Enhancements

* Expand the Arabic corpus for better contextual accuracy.
* Integrate modern **BERT-based** language models for semantic understanding.
* Optimize runtime efficiency and GUI usability.
* Develop a web-based interface for public testing.

---

### 📚 References

* Jurafsky, D., & Martin, J. H. (2024). *N-gram Language Models*. Stanford University.
* Saturn Cloud (2024). *Stemming in Natural Language Processing*.
* UBIAI (2023). *NLP Techniques: Tokenization, POS Tagging and NER*.
* ScienceDirect (2024). *Levenshtein Distance Overview*.

