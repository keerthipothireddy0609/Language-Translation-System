# 🛡️ Miscommunication Shield Business Translator

> AI-powered translation system that detects cultural miscommunication risks **before** you send international business messages.

## 💡 The Problem

International businesses lose **$75B annually** from cultural miscommunication. Examples:
- ❌ "No, this won't work" → Offensive in Japanese business culture
- ❌ "Hey! Send ASAP" → Unprofessional in French
- ❌ "I'm embarrassed" → Translates to "I'm pregnant" in Spanish

**We detect these mistakes BEFORE sending.**

---

## ✨ What It Does

```
Input: "No, this is impossible to deliver"
Target: Japanese

⚠️ RISK: HIGH (90% confidence)
├─ Direct refusal detected ("No", "impossible")
├─ Inappropriate for Japanese business context
└─ May damage client relationship

💡 RECOMMENDATION: ❌ DO NOT SEND - Rewrite required

✅ SAFE VERSION:
"We appreciate your request and would like to explore 
alternative timelines that better align with our capacity."
```

**Key Features:**
- 🚨 Real-time risk detection (Low/Medium/High)
- 🧠 Hybrid AI (Rule-based ML + GPT-4 translation)
- 📊 80% accuracy across 5 languages
- ⚡ < 1 second processing time

---

## 🚀 Quick Start

```bash
# Clone and install
git clone https://github.com/keerthipothireddy0609/Language-Translation-System.git
cd Language-Translation-System
pip install openai gradio pandas numpy

# Run notebook
jupyter notebook Miscommunication_Shield.ipynb
```

**Run all cells top-to-bottom** - outputs generate automatically!

---

## 🏗️ How It Works

```
Input Message
    ↓
Risk Detection (Rule-based ML)
├─ Pattern matching (50+ cultural risk words/language)
├─ Feature extraction (tone, formality, commands)
└─ Confidence scoring
    ↓
Translation (GPT-4)
├─ Cultural adaptation
└─ Business tone preservation
    ↓
Output: Risk warnings + Safe translation
```

**Technical Stack:**
- **Dataset**: 100 synthetic + expert-labeled examples
- **Languages**: Japanese, French, Spanish, Hindi, Arabic
- **Model**: Hybrid (custom rules + OpenAI GPT-4o-mini)
- **Metrics**: 80% accuracy, 75% avg confidence

---

## 📊 Performance

| Metric | Score |
|--------|-------|
| Accuracy | 80% |
| Processing Time | < 1 sec |
| Languages Supported | 5 |
| Training Examples | 100 |

**Test Results:**
```
✅ "No, this won't work" → Japanese → HIGH RISK (Correct)
✅ "Hey! Send ASAP" → French → HIGH RISK (Correct)  
✅ "We appreciate your patience" → Japanese → LOW RISK (Correct)
```

---

## 📁 Project Structure

```
Language-Translation-System/
├── Miscommunication_Shield.ipynb    # Main notebook (all code)
├── README.md                         # This file
└── requirements.txt                  # Dependencies
```

---

## 🎓 Academic Info

**Course**: IIT Ropar Minor in AI - Module E  
**Track**: Language Translation System  
**Components**: Problem definition • Data prep • ML model • Evaluation • Ethics

---

## 🔮 Future Work

- [ ] Train custom BERT model (10K+ examples)
- [ ] Browser extension for Gmail/Slack
- [ ] Expand to 20+ languages
- [ ] Voice tone analysis for meetings

---

## ⚖️ Ethics & Limitations

**Considerations:**
- Patterns may not apply to all individuals
- Synthetic data may miss edge cases  
- Advisory tool only (human has final say)

**Responsible AI:**
- ✅ Transparent methodology
- ✅ No message storage (privacy)
- ✅ Explainable warnings

---

## 👤 Author

**[KEERTHI POTHIREDDY]** - IIT Ropar Minor in AI Course 2024-26

📧 keerthipothireddy0609@gmail.com
---

## 📚 Key References

- Market data: Holmes Report 2023 - "Cost of Poor Communication"
- Cultural patterns: "The Culture Map" by Erin Meyer
- False friends: Collins Dictionary
