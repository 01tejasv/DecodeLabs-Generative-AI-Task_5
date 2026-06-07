# AI Safety & Bias Audit Report (Task 5)

## 📌 Project Overview
This project performs a structured AI Safety Audit using Red Teaming and Bias Testing techniques. The goal is to evaluate how an AI model responds to unsafe prompts and whether it shows any gender or racial bias in outputs.

We also propose a Safety Framework (Guardrails) to improve AI system reliability and safety before public deployment.

---

## 🎯 Objectives

- Perform Red Teaming (Jailbreak Testing)
- Identify potential unsafe AI responses
- Test AI for gender and racial bias
- Analyze behavior patterns
- Propose AI Safety Guardrails

---

## 🧪 Methodology

### 1. Red Team Testing
We tested the model using harmful, misleading, and jailbreak-style prompts to check if it violates safety rules.

### 2. Bias Testing
We tested prompts related to professions and roles to detect gender or racial bias.

### 3. Safety Framework Design
We proposed guardrails to prevent unsafe or biased outputs.

---

## 📊 Results Summary

- AI consistently refused unsafe prompts
- No successful jailbreak observed
- Minor stereotype tendencies may appear in hypothetical image generation prompts (depending on model behavior)
- Model follows strong safety alignment guidelines

---

## 🛡️ Proposed Safety Framework

- Input Filtering System to block unsafe prompts
- Jailbreak Detection Layer
- Output Moderation System
- Bias Detection & Fairness Scoring
- RLHF (Reinforcement Learning from Human Feedback)
- Continuous Red Team Testing Pipeline
- Audit Logging System for transparency

---

## 📂 Files in this Repository

- audit_report.md → Full analysis report
- jailbreak_tests.md → Red teaming test cases
- bias_tests.md → Bias testing results
- screenshots/ → Evidence (optional)

---

## 🚀 Conclusion

This audit demonstrates the importance of continuous AI safety evaluation. While modern AI systems are highly aligned, proactive red teaming and bias audits are essential for safe real-world deployment.
