# 📘 K-Nearest Neighbors (KNN)

## 1. What is K-Nearest Neighbors (KNN)?

**K-Nearest Neighbors (KNN)** is a **Machine Learning algorithm**.

It predicts an answer by looking at its **nearest (closest) neighbors**.

Think of it like asking your closest friends for advice before making a decision.

---

# 2. Important Terms

## 🤖 Machine Learning

Machine Learning means **teaching a computer using examples instead of writing every rule manually.**

---

## 📊 Data

**Data** means information.

### Example

- Name
- Age
- Marks
- Income

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

## 📤 Target (Output)

The **Target** is the answer that we want the computer to predict.

### Example

```
Loan Approved?
```

Possible outputs:

- Yes
- No

---

## 🎯 Prediction

Prediction is the **computer's guess** based on the available data.

### Example

```
Loan Approved
```

This predicted answer is called a **Prediction**.

---

## 👥 Neighbor

A **Neighbor** is the **closest data point** to the new data.

### Example

Suppose you are a new student in a school.

The teacher wants to guess your favorite game.

Instead of asking everyone, she looks at your **closest friends**.

Those closest friends are called **Neighbors**.

---

## 🔢 K

**K** represents the **number of nearest neighbors** the algorithm considers before making a prediction.

### Example

```
K = 3
```

Look at the **3 nearest neighbors**.

```
K = 5
```

Look at the **5 nearest neighbors**.

---

## 🏷️ Class

A **Class** is a category.

### Example 1

- Apple
- Banana
- Mango

These are **3 different classes**.

### Example 2

- Loan Approved
- Loan Rejected

These are **2 different classes**.

---

## 📌 Classification

**Classification** means **predicting a category or class**.

### Examples

- Cat or Dog
- Spam or Not Spam
- Loan Approved or Rejected
- Red or Blue

---

## 📈 Regression

**Regression** means **predicting a numerical value**.

### Examples

- House Price = ₹50 Lakhs
- Salary = ₹40,000
- Marks = 95
- Temperature = 35°C

---

# 3. How KNN Works

```text
Choose the Value of K
        │
        ▼
Find the Nearest Neighbors
        │
        ▼
Check Their Classes
        │
        ▼
Majority Vote Wins
        │
        ▼
Make the Prediction
```

---

# 4. Real-Life Example

Suppose a **new student** joins a school.

The nearest friends like:

- 🏏 Cricket
- 🏏 Cricket
- ⚽ Football

Since **most neighbors like Cricket**, the computer predicts:

> **The new student also likes Cricket.**

This is the basic idea behind **K-Nearest Neighbors (KNN).**

---

# 5. Loan Approval Example

### New Customer

| Feature | Value |
|---------|-------|
| Income | ₹60,000 |
| Credit Score | 750 |

### Nearest Customers

- ✅ Approved
- ✅ Approved
- ❌ Rejected
- ✅ Approved

### Prediction

> **Loan Approved**

Since the majority of the nearest neighbors were **Approved**, KNN predicts that the new customer will also be **Approved**.

---

# 6. Advantages

- ✅ Easy to understand
- ✅ Beginner-friendly
- ✅ No complex mathematics
- ✅ Works well for small datasets
- ✅ Simple to implement

---

# 7. Disadvantages

- ❌ Slow for large datasets
- ❌ Choosing the wrong value of **K** can reduce accuracy
- ❌ Performance decreases with high-dimensional data

---

# 8. Applications

KNN is commonly used in:

- 💳 Loan Approval Prediction
- 🩺 Disease Prediction
- 😊 Face Recognition
- 🎬 Recommendation Systems
- ✉️ Spam Detection
- 🛒 Customer Classification

---

# 🎯 Summary

- **K-Nearest Neighbors (KNN)** is a Machine Learning algorithm that predicts outcomes by looking at the **nearest neighbors**.
- It can be used for both **Classification** and **Regression**, but it is mainly used for **Classification** problems.
- The value of **K** determines how many neighbors are considered before making a prediction.
- The algorithm predicts the class that appears **most frequently** among the nearest neighbors (majority voting).

### KNN Workflow

```text
Input Data
     │
     ▼
Choose K
     │
     ▼
Find Nearest Neighbors
     │
     ▼
Majority Voting
     │
     ▼
Prediction
```