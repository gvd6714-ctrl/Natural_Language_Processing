# 🧠 NLP Preprocessing Engine (Advanced)

## 📌 Overview

This project implements a **robust NLP preprocessing pipeline** as part of the internship task.
The goal is to clean and normalize raw text data for further Natural Language Processing tasks.

---

## 🚀 Features Implemented

The preprocessing function includes:

* 🔤 Convert text to lowercase
* 🔗 Remove URLs and email patterns
* 🔢 Remove numbers
* 🔥 Handle repeated characters

  * Example: *"soooo goooood!!!" → "so good"*
* ✂ Remove punctuation and extra spaces
* 🧹 Remove very short tokens (≤ 2 characters)

  * Exception: meaningful words like **"no"**, **"not"**, **"so"** are retained
* 😊 Remove emojis / non-ASCII characters

---

## 🧪 Tasks Covered

### ✅ Task 1 & 2: Preprocessing Engine

* Built a reusable function: `preprocess_text(text)`
* Handles multiple cleaning operations efficiently

### ✅ Task 3: Stress Testing

Tested on diverse inputs including:

* Emojis
* Numbers
* Slang
* URLs
* Mixed case text

---

### ✅ Task 4: Token Analytics

For each sentence:

* Total tokens
* Unique tokens
* Average token length

---

### ✅ Task 5: Frequency Analysis

* Top 10 most frequent words
* Top 5 least frequent words

---

### ✅ Task 6: Full Pipeline

Implemented:

```python
def full_pipeline(text_list):
```

Returns:

* All tokens
* Cleaned sentences

---

### ✅ Task 7: Error Handling

Handled edge cases:

* Empty string
* Only emojis
* Only numbers

---

## 🛠 Technologies Used

* Python 🐍
* Regular Expressions (re)
* String processing
* Collections (Counter)

---

## 📂 Project Structure

```
📁 Natural_Language_Processing
 ┣ 📄  NLP-Preprocessing-Engine.ipynb
 ┣ 📄 README.md
```

---

## ▶ How to Run

1. Open the notebook in Jupyter / Colab
2. Run all cells:

```
Runtime → Run All
```

---

## 📊 Example

**Input:**

```
"soooo goooood!!!"
```

**Output:**

```
Tokens: ['so', 'good']
Cleaned Sentence: so good
```

---

## 🎯 Conclusion

This project demonstrates:

* Strong understanding of text preprocessing
* Ability to handle real-world noisy data
* Clean and modular coding practices

---

## 🔗 Submission

GitHub Repository (HTTPS):

```
https://github.com/gvd6714-ctrl/Natural_Language_Processing
```

---

**Your Name**
