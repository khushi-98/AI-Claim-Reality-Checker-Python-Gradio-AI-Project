# 🤖 AI Claim Reality Checker

A beginner-friendly **Artificial Intelligence project using Python and Gradio** that analyzes human claims and classifies them as **Realistic, Exaggerated, or Unrealistic** using predefined logical rules.

This project is designed for **Grade 8 students** to understand the basic concepts of **Artificial Intelligence, rule-based systems, logical reasoning, and responsible AI**.

---

## 🎯 Aim

The aim of this project is to design an Artificial Intelligence-based system that analyzes human claims and classifies them into three categories:

- ✅ Realistic
- ⚠️ Exaggerated
- ❌ Unrealistic

The project demonstrates that AI does not always need to blindly answer **"Yes"** or **"No"**. Instead, it can use logical rules to analyze a statement.

The project is designed to be **safe, simple, fun, and educational**.

---

## ❓ Problem Statement

People make different claims in their daily lives. Some claims may be normal, while others may contain exaggeration or unrealistic information.

For example:

> "I am the President of India."

A simple AI system might accept this statement without applying any reasoning.

Therefore, this project demonstrates how AI can use **logical rules** to check whether a claim appears realistic instead of blindly accepting it as true.

---

## 💡 Problem Solution

The **AI Claim Reality Checker** uses a simple **rule-based AI approach**.

The program checks the user's statement for:

1. High-profile roles
2. Extreme numbers or values
3. Exaggeration words

Based on these rules, the system returns one of three results:

| Result | Meaning |
|---|---|
| Realistic | No predefined unrealistic or exaggerated pattern was detected |
| Exaggerated | Strong exaggeration words were detected |
| Unrealistic | A high-profile role or extreme value was detected |

---

## ⚙️ How It Works

The project follows these steps:

```text
User enters a claim
        ↓
Convert the claim to lowercase
        ↓
Check for high-profile roles
        ↓
Check for extreme numbers
        ↓
Check for exaggeration words
        ↓
Apply predefined rules
        ↓
Display the result
