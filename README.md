# 🌍 NLP for Moroccan Darija — Tackling Low-Resource Machine Translation

Merhaba! 👋 Welcome to **NLP-Darija** , a project where I explore, analyze, and challenge the boundaries of current Natural Language Processing (NLP) techniques by focusing on **Moroccan Darija**, a rich yet low-resource language.

---

## 🎯 Project Overview

In this project, I investigate the **capabilities and limitations of Large Language Models (LLMs)** — including **GPT-4** and **Claude** — for **Moroccan Darija to English Machine Translation**. My evaluation spans:

- 🧠 **Sentence-level translation**
- 🎭 **Idiomatic and sarcastic expressions**
- 🧩 **POS tagging and dependency parsing**
- 🗣️ **Code-switched text analysis (Darija, French, Arabic, Arabizi)**

This repository serves as a **call to action** in the NLP community, exposing the critical gaps in support for **non-standardized and underrepresented languages**. Moroccan Darija is particularly challenging due to its:

- Non-standardized orthography (including Arabizi)
- Morphological complexity
- Heavy linguistic borrowing from **Amazigh**, **French**, and **Modern Standard Arabic**
- Frequent **code-switching**
- Unique **phonetic substitutions using numbers** (e.g., 7 = ح)

---

## 🧪 What I Did

### 🧰 Tools & Techniques
- Syntax parsing with LLMs for **POS tagging** and **dependency parsing**
- Prompt engineering with **OpenAI GPT-4** and **Anthropic Claude**
- Evaluation via **human assessments** + **automatic metrics**
- Linguistic analysis of **idioms**, **sarcasm**, and **phonetic variation**

### 📊 Evaluation
- Compared LLM translations to human-annotated reference sets
- Highlighted failure points on idiomatic expressions and sarcasm
- Demonstrated how **prompt design** directly impacts translation quality
- Assessed how **LLMs handle Arabizi and code-switching**

---

## 🔍 Key Insights

- ✅ LLMs like GPT-4 and Claude perform decently on general translation tasks
- ❌ They **struggle** with:
  - Sarcasm
  - Idiomatic expressions
  - Arabizi (Romanized Arabic)
  - Context-heavy disambiguation

- 📌 **Translation quality improves with task-specific prompt tuning**
- ⚠️ No robust open-source **Darija-English parallel corpus** exists
- 🚨 There is an urgent need for **culturally aware NLP tools** and **dedicated datasets** for Darija and other low-resource dialects

---

## 🚀 Future Directions

- Build a **Darija-English fine-tuned model**
- Create a **parallel corpus** including Arabizi
- Develop **idiom-aware translation modules**
- Evaluate **multimodal LLMs** on low-resource dialects

---

## 👩‍💻 About Me

This project is part of my ongoing mission to bridge the digital gap for **underrepresented languages** in the AI space. As a Data Scientist passionate about **multilingual NLP**, **machine learning**, and **ethical AI**, I'm especially interested in designing solutions that are inclusive and culturally aware.

---

> 🤝 Let's make AI work for *all* languages — not just the well-resourced ones.
