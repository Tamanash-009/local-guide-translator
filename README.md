# 🌍 Local Guide Translator

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB.svg?logo=python&logoColor=white)](https://python.org)
[![Framework: Kiro AI](https://img.shields.io/badge/Framework-Kiro%20AI-orange.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

An AI-driven context-aware hyper-local slang and cultural insights translator. Designed for travelers, digital nomads, and researchers seeking to decipher regional idioms, colloquial metaphors, and colloquial local insights.

---

## 🌟 Overview

Standard translation APIs frequently fail when encountering localized regional vernacular, slang, and cultural humor. **Local Guide Translator** solves this by marrying context-driven dictionaries with adaptive natural language processing models, extracting the true nuanced meaning behind regional phrases.

---

## ✨ Features

- **Contextual Slang Mapping**: Dynamic resolution of colloquial terms (including regional Bengali, Hindi, and Indian English idioms).
- **Cultural Nuance Insights**: Explains not just the literal translation, but the social subtext and appropriate usage contexts.
- **Kiro AI Integration**: Reads project context rules from `.kiro/product.md` to preserve terminology consistency.
- **Interactive CLI**: Fast command-line interface for rapid queries and dictionary lookups.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher

### Installation

```bash
git clone https://github.com/Tamanash-009/local-guide-translator.git
cd local-guide-translator

# Run the translator
python main.py
```

---

## 📖 Usage Example

```python
from main import LocalGuideTranslator

translator = LocalGuideTranslator()

# Translate localized idiom
insight = translator.translate_slang("bengali", "aloo")
print(insight)
# Output: Cultural context, connotations, and colloquial translation
```

---

## 📁 Repository Structure

```
local-guide-translator/
├── .kiro/
│   └── product.md          # Domain knowledge guidelines & context rules
├── main.py                 # Core translation engine and slang database
└── README.md               # Documentation
```

---

## 👨‍💻 Author
**Tamanash Chakraborty**
- GitHub: [@Tamanash-009](https://github.com/Tamanash-009)
