# 📘 Linear Regression

## 1. What is Linear Regression?

**Linear Regression** is a **Supervised Machine Learning** algorithm.

It is used to **predict numerical values**.

### Examples
- 🏠 House Price
- 💰 Salary
- 📝 Marks
- 🌡️ Temperature

---

# 2. Imagine This...

Suppose your teacher notices a pattern:

- More Study Hours → More Marks
- Less Study Hours → Less Marks

The teacher understands this relationship.

Now, if a new student studies for **5 hours**, the teacher can estimate:

> "This student might score around **80 marks**."

This type of prediction based on previous examples is called **Linear Regression**.

---

# 3. Important Terms

## 🤖 Machine Learning

Teaching a computer using **examples** instead of writing every rule manually.

---

## 📊 Data

Data means **information**.

### Example

- Study Hours = **5**
- Marks = **80**

These values are called **Data**.

---

## 📂 Dataset

A **Dataset** is a collection of many data points.

### Example

Information of **1000 students**.

---

## 📥 Feature (Input)

A **Feature** is the information given to the computer.

### Examples

- Study Hours
- Attendance
- House Size
- Years of Experience

---

## 📤 Target (Output)

The **Target** is the value that the computer has to predict.

### Examples

- Marks
- House Price
- Salary

---

## 🎯 Prediction

Prediction is the computer's **guess**.

### Example

**Input**

```
Study Hours = 5
```

**Prediction**

```
Marks = 82
```

This is called a **Prediction**.

---

## 📈 Regression

Regression means **predicting a numerical value**.

### Examples

- House Price
- Salary
- Temperature
- Marks

---

# 4. How Linear Regression Works

```text
Collect Data
      │
      ▼
Find Patterns
      │
      ▼
Draw the Best Fit Line
      │
      ▼
Receive New Input
      │
      ▼
Predict the Output
```

---

# 5. What is the Best Fit Line?

Imagine many dots on a graph.

Each dot represents one student.

The computer draws **one straight line** that passes **closest to most of the dots**.

This line is called the **Best Fit Line**.

The Best Fit Line helps the computer make predictions for new data.

---

# 6. Formula

## Linear Regression Equation

```text
y = mx + c
```

### Where

| Symbol | Meaning |
|---------|----------|
| **y** | Predicted Output |
| **x** | Input |
| **m** | Slope (Shows how much **y** changes when **x** changes.) |
| **c** | Intercept (Value of **y** when **x = 0**) |

> **Note:** Don't worry about the mathematics right now. Just remember that this formula helps the computer draw the **Best Fit Line**.

---

# 7. Example

### Training Data

| House Size | Price |
|------------|-------|
| 1000 sq.ft | ₹30 Lakhs |
| 1500 sq.ft | ₹45 Lakhs |
| 2000 sq.ft | ₹60 Lakhs |

### New Input

```
House Size = 1700 sq.ft
```

### Prediction

```
₹50 Lakhs
```

---

# 8. Advantages

- ✅ Easy to understand
- ✅ Fast
- ✅ Beginner-friendly
- ✅ Good for predicting numerical values

---

# 9. Disadvantages

- ❌ Works well only when the data follows a **straight-line relationship**.
- ❌ Not suitable for very complex relationships.

---

# 10. Applications

- 🏠 House Price Prediction
- 💰 Salary Prediction
- 📝 Marks Prediction
- 📈 Sales Prediction
- 🌦️ Weather Prediction

---

# 🎯 Summary

**Linear Regression** is a supervised machine learning algorithm that predicts **numerical values** by finding the **Best Fit Line** through existing data.

### Formula

```text
y = mx + c
```

It is simple, fast, beginner-friendly, and widely used for prediction tasks.