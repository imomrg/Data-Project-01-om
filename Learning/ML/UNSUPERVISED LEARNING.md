# 📘 Unsupervised Learning

## 1. What is Unsupervised Learning?

**Unsupervised Learning** is a type of **Machine Learning** where the computer learns from **unlabeled data** (data without correct answers).

Instead of being told the correct answer, the computer finds **patterns**, **similarities**, and **relationships** on its own.

Think of it like giving a child a box of mixed toys without telling them how to sort them.

```text
Unlabeled Data 
       │
       ▼
Computer Looks for Patterns
       │
       ▼
Groups Similar Data Together
```

The computer learns without any teacher or correct answers.

---

# 2. Why is it Called "Unsupervised"?

It is called **Unsupervised Learning** because **no teacher or correct answers (labels)** are provided.

The computer studies the data by itself and tries to discover hidden patterns or relationships.

Unlike Supervised Learning, there is **no right or wrong answer** during training.

---

# 3. Important Terms

## 📊 Data

**Data** means information.

### Examples

- Age
- Salary
- Height
- Weight
- Shopping Amount

---

## 📂 Dataset

A **Dataset** is a collection of many data points.

### Example

Information of **5000 customers**.

---

## 🏷️ Label

A **Label** is the correct answer associated with the data.

### Example

```text
Image of Dog  → Dog

Email → Spam

Loan → Approved
```

In **Unsupervised Learning**, labels are **NOT available**.

---

## 📥 Feature (Input)

A **Feature** is the information given to the computer.

### Examples

- Income
- Age
- Credit Score
- Shopping Amount

---

## 🔍 Pattern

A **Pattern** is a relationship or similarity found by the computer.

### Example

The computer notices that customers with similar incomes often buy similar products.

---

## 📦 Cluster

A **Cluster** is a group of similar data.

### Example

```text
Cluster 1 → Students

Cluster 2 → Office Workers

Cluster 3 → Senior Citizens
```

The computer creates these groups automatically.

---

# 4. How Unsupervised Learning Works

```text
Collect Unlabeled Dataset
          │
          ▼
Choose an Algorithm
          │
          ▼
Train the Model
          │
          ▼
Find Hidden Patterns
          │
          ▼
Group or Transform Data
          │
          ▼
Analyze the Results
```

---

# 5. Types of Unsupervised Learning

## A. Clustering

**Clustering** groups similar data into different clusters.

The computer automatically places similar data into the same group.

### Example

An online shopping website groups customers into:

- 👨‍🎓 Students
- 👨‍💼 Office Workers
- 👴 Senior Citizens

without anyone telling it who belongs to which group.

### Popular Algorithms

- K-Means Clustering ⭐
- Hierarchical Clustering
- DBSCAN

---

## B. Association Rule Learning

This technique finds relationships between different items.

It answers questions like:

**"If a person buys A, what else is he likely to buy?"**

### Example

```text
Bread 🥖

↓

Butter 🧈
```

People who buy Bread often buy Butter.

### Popular Algorithms

- Apriori Algorithm ⭐
- FP-Growth

---

## C. Dimensionality Reduction

This technique removes unnecessary features while keeping the important information.

It makes the dataset smaller, faster, and easier to understand.

### Example

A dataset contains **100 Features**.

Many are unnecessary.

The algorithm reduces them to **20 Important Features**.

### Popular Algorithms

- PCA (Principal Component Analysis) ⭐
- t-SNE
- UMAP

---

# 6. Real-World Applications

Unsupervised Learning is used in many real-life applications, such as:

| Industry | Application |
|----------|-------------|
| 🛒 Amazon | Product Recommendation |
| 🎬 Netflix | Movie Recommendation |
| 📸 Google Photos | Face Grouping |
| 🎵 Spotify | Music Recommendation |
| 🏦 Banking | Customer Segmentation |
| 🛍️ Retail | Market Basket Analysis |

---

# 7. Advantages

- ✅ Does not require labeled data
- ✅ Finds hidden patterns automatically
- ✅ Useful for exploring unknown datasets
- ✅ Helps understand data better

---

# 8. Disadvantages

- ❌ Results are sometimes difficult to understand
- ❌ Accuracy is difficult to measure
- ❌ Different algorithms may produce different groups
- ❌ Incorrect patterns may sometimes be created

---

# 📊 Supervised vs Unsupervised Learning

| Supervised Learning | Unsupervised Learning |
|---------------------|----------------------|
| Uses Labeled Data | Uses Unlabeled Data |
| Correct Answers Available | No Correct Answers |
| Predicts Output | Finds Hidden Patterns |
| Teacher Available | No Teacher |
| Example: Loan Approval | Example: Customer Segmentation |

---

# 🎯 Summary

- **Unsupervised Learning** is a Machine Learning technique where the model learns from **unlabeled data**.
- The computer discovers **hidden patterns, similarities, and relationships** without any teacher.
- There are **three main types** of Unsupervised Learning:
  - **Clustering** → Groups similar data.
  - **Association Rule Learning** → Finds relationships between items.
  - **Dimensionality Reduction** → Reduces unnecessary features.
- It is widely used in applications like **customer segmentation, recommendation systems, face grouping, and market basket analysis**.

### Unsupervised Learning Workflow

```text
Unlabeled Dataset
        │
        ▼
Train the Model
        │
        ▼
Find Hidden Patterns
        │
        ▼
Create Groups / Relationships
        │
        ▼
Analyze Results
```
