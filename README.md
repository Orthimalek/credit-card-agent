# 💳 Credit Card AI Agent

A portable, browser-based AI agent that analyzes your credit card statements, finds hidden subscriptions, flags suspicious charges, and tells you exactly where to save money — powered by Claude AI.

**🌐 Live Demo:** [orthimalek.github.io/credit-card-agent](https://orthimalek.github.io/credit-card-agent)

---

## ✨ Features

- 📄 **No file limits** — upload as many PDF or CSV statements as you want
- 🔄 **Subscription detector** — finds every recurring charge and flags predatory ones
- 🕵️ **Hidden charge finder** — catches scam sites, duplicate charges, and mystery merchants
- 📊 **Spending categorization** — Food, Transport, Shopping, Education, Utilities and more
- 📈 **Monthly trend analysis** — see how your spending changes over time
- 🏪 **Top merchant breakdown** — know exactly where your money goes
- 💡 **AI-powered insights** — personalized recommendations based on your actual data
- ✅ **Action plan** — prioritized list of what to cancel and what to keep
- 💬 **Follow-up chat** — ask questions about your spending after the analysis

---

## 🚀 How to Use

### 1. Get a free Anthropic API key
Go to [console.anthropic.com](https://console.anthropic.com) → Sign up → Create an API key. New accounts get free credits.

### 2. Open the app
Visit [orthimalek.github.io/credit-card-agent](https://orthimalek.github.io/credit-card-agent) or download `index.html` and open it locally in any browser.

### 3. Enter your API key
Paste your key into the field in the top right corner. It stays in your browser and is never stored or transmitted anywhere except directly to Anthropic's API.

### 4. Upload your statements
Drag and drop your bank statement files — PDF, CSV, TXT, or Excel. Upload as many months as you want.

### 5. Click Analyze
The AI reads all your statements and generates a full financial report in 30–60 seconds.

### 6. Ask follow-up questions
Use the built-in chat to ask things like:
- *"Which subscription is costing me the most per year?"*
- *"How much did I spend on food last month?"*
- *"Are there any charges I should dispute?"*

---

## 🔒 Privacy & Security

- **Your data never leaves your browser** except to go directly to Anthropic's API
- **No server, no database, no tracking** — this is a pure client-side app
- **Your API key is never stored** — it lives only in your browser tab
- **Files are processed in memory** and discarded after analysis
- Each person who uses this needs their own Anthropic API key

---

## 📁 Supported File Types

| Format | Notes |
|--------|-------|
| `.pdf` | Best results — most bank statements export as PDF |
| `.csv` | Works great for exported transaction data |
| `.txt` | Plain text exports |
| `.xlsx / .xls` | Excel spreadsheets |

---

## 🛠️ Running Locally

No installation needed. Just download `index.html` and open it in any modern browser:

```bash
git clone https://github.com/Orthimalek/credit-card-agent.git
cd credit-card-agent
open index.html   # macOS
# or double-click index.html on Windows
```
