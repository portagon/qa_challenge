# 🧪 QA Engineer Challenge

## 🏦 Context

You’re working on our fintech web application and our engineering team. Investors use the platform to onboard, upload identification documents, and make investments. You’ll be helping the product owner ensure that releases are well-tested and stable.

> [!IMPORTANT]
> We'd appreciate it if you could limit the use of AI-generated content, as it's often easy to identify and we’re looking for authentic, personal input.
---

## 🔍 Your Challenge

This challenge is divided into 3 parts to evaluate your QA thinking, test design, communication, and debugging — without focusing on any specific programming language or test framework.

---

### ✅ Part 1: Analyze a Feature and Design Tests

**Feature: Investor uploads identification documents**

> Users can upload their passport or ID card. The system only accepts:
>
> - Files in PDF or JPG format  
> - Files smaller than 5 MB  
> - A `valid_until` date that must be in the future  
> - Each investor can only upload **one document at a time**. New uploads replace old ones.

#### Your Tasks:

1. Write a **test plan** for this feature. Include:
   - At least 5 **positive and negative test scenarios**
   - The **type of test** (e.g., manual, automated, UI, backend)
2. Suggest **two edge cases** that are easy to overlook but important to test
3. Explain how you would test this if the system used **background processing** for uploads

---

### ✅ Part 2: Investigate and Debug a Realistic Bug Report

**Bug report:**

> “A user uploaded a valid ID document, and the upload was accepted, but a few minutes later it disappeared from their dashboard.”

#### Your Tasks:

1. Write a short **investigation plan**: what logs, tools, or parts of the system would you check?
2. Propose **two hypotheses** for the root cause of this bug
3. Suggest a way to **prevent this in the future** using testing, logging, or monitoring

---

### ✅ Part 3: Communicate with the Team

You notice that a recent feature behaves differently from the product specification. The investor sees a success message even when the upload fails due to a background error (e.g., storage issue).

#### Your Tasks:

1. Write a short message you would send to the **product owner or engineer** to raise this concern
2. Suggest one **improvement to the QA process** that could help catch this kind of issue earlier

---

## 📦 Deliverables

Please send me a single Markdown, PDF, or Google Doc file that includes:

- **Part 1:** Test plan with scenarios and edge cases
- **Part 2:** Bug investigation write-up
- **Part 3:** Communication message and QA process improvement

---

> [!IMPORTANT]
> We'd appreciate it if you could limit the use of AI-generated content, as it's often easy to identify and we’re looking for authentic, personal input.

