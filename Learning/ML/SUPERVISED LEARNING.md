# 📘 Supervised Learning

## 1. What is Supervised Learning?

**Supervised Learning** is a type of **Machine Learning** where the computer learns from data that **already contains the correct answers (labels).**

Think of it like a teacher teaching a student.

```text
Teacher Gives Questions + Answers
              │
              ▼
        Student Learns
              │
              ▼
     Student Solves New Questions
```

A computer learns in the same way by studying examples with known answers.

---

# 2. Why is it Called "Supervised"?

It is called **Supervised Learning** because the computer learns under the **supervision of correct answers**, also known as **Labels**.

The model first studies data with known outputs and then uses that knowledge to predict answers for new data.

---

# 3. Important Terms

## 📊 Data

**Data** means information.

### Examples

- Age = 20
- Marks = 80
- Income = ₹50,000

---

## 📂 Dataset

A **Dataset** is a collection of many data points.

### Example

Information of **1000 students**.

---

## 📥 Feature (Input)

A **Feature** is the information given to the computer to make a prediction.

### Examples

- Study Hours
- Attendance
- Income
- Credit Score

---

## 📤 Target (Output / Label)

The **Target** (also called a **Label**) is the correct answer that the computer has to learn and predict.

### Examples

- Loan Approved? → Yes / No
- Marks
- House Price

---

## 🎓 Training

**Training** is the process of teaching the computer using the dataset.

During training, the computer learns patterns from the data.

---

## 🤖 Model

A **Model** is the trained version of the computer.

Once training is complete, the trained algorithm is called a **Machine Learning Model**.

---

## 🎯 Prediction

A **Prediction** is the computer's guess for new data.

### Example

**Input**

```text
Income = ₹60,000
Credit Score = 750
```

**Prediction**

```text
Loan Approved
```

---

# 4. How Supervised Learning Works

```text
Collect Dataset
       │
       ▼
Provide Correct Answers (Labels)
       │
       ▼
Train the Computer
       │
       ▼
Computer Learns Patterns
       │
       ▼
New Data is Given
       │
       ▼
Make Prediction
```

---

# 5. Types of Supervised Learning

## A. Classification

**Classification** predicts a **category or class**.

### Examples

- 🐶 Dog or Cat
- 📧 Spam or Not Spam
- 💳 Loan Approved or Rejected

---

## B. Regression

**Regression** predicts a **numerical value**.

### Examples

- 🏠 House Price
- 💰 Salary
- 📝 Marks
- 🌡️ Temperature

---

# 6. Real-World Applications

Supervised Learning is used in many real-life applications, such as:

| Industry | Application |
|----------|-------------|
| 🎬 Netflix | Movie Recommendation |
| 🏦 Banking | Loan Approval |
| 🏥 Healthcare | Disease Prediction |
| 📧 Gmail | Spam Detection |

---

# 7. Advantages

- ✅ Easy to understand
- ✅ High accuracy when trained on good-quality data
- ✅ Widely used in real-world applications
- ✅ Suitable for both classification and regression problems

---

# 8. Disadvantages

- ❌ Requires labeled data for training
- ❌ Poor-quality data leads to poor predictions
- ❌ Preparing labeled datasets can be time-consuming and expensive

---

# 🎯 Summary

- **Supervised Learning** is a Machine Learning technique where the model learns from **labeled data**.
- The computer studies examples with **known answers** and uses them to predict outcomes for new data.
- There are **two main types** of Supervised Learning:
  - **Classification** → Predicts categories.
  - **Regression** → Predicts numerical values.
- It is widely used in applications like **loan approval, spam detection, disease prediction, and recommendation systems**.

### Supervised Learning Workflow

```text
Labeled Dataset
      │
      ▼
Train the Model
      │
      ▼
Learn Patterns
      │
      ▼
Receive New Data
      │
      ▼
Make Prediction
```