# FUTURE_ML_03
# 🤖Chatbot 

## 📌 Project Overview

This project demonstrates a simple, rule-based chatbot built in Python.  
It uses keyword matching to identify user intent from a dataset and responds accordingly based on pre-defined patterns and responses.

---

## 🛠️ Technologies Used

- **Python 3**
- **pandas** — for handling CSV data
- **re** — for regex-based text matching
- **random** — for random response selection
- **Command-line Interface** (CLI)

---

## 📂 Dataset

- Input file: `customer_support_tickets.csv`
- Output file: `intents.csv`

### Structure of `intents.csv`
| Intent | Patterns | Responses |
|--------|----------|-----------|
| billing_issue | payment error\|invoice issue | Please check your billing settings\|Try updating your payment method |

---

## 🔁 How It Works

1. Load the dataset and extract intents grouped by `Ticket Type`
2. Preprocess and save as `intents.csv`
3. Match user input using keywords (via regex)
4. Return a random response for the matched intent
5. Gracefully handle unknown or unmatched queries

---

## 💡 Features

- Keyword-based matching using word boundaries
- Custom dataset-to-intent extraction
- Randomized multi-response support
- CLI-based conversational interface
- Handles bad input and errors gracefully

---

## 🚀 Getting Started

```bash
# Step 1: Place your intents.csv in the working directory
# Step 2: Run the chatbot

