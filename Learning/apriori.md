# 📘 Apriori Algorithm

## What is Apriori Algorithm?

Apriori is an **Unsupervised Learning** algorithm used in **Association Rule Learning**.

It finds **items that are frequently bought or used together** by analyzing past transaction data.

### Simple Example

Imagine a supermarket.

After checking thousands of bills, the computer notices:

```text
People who buy Bread 🥖
also buy Butter 🧈
```

or

```text
People who buy Laptop 💻
also buy Mouse 🖱️
```

The algorithm finds these hidden relationships automatically.

---

## How does it work?

### Step 1

Collect transaction data.

Example

```text
Customer 1 → Bread, Butter, Milk

Customer 2 → Bread, Butter

Customer 3 → Bread, Milk

Customer 4 → Bread, Butter, Eggs
```

---

### Step 2

Count how many times each item appears.

Example

```text
Bread → 4 Times

Butter → 3 Times

Milk → 2 Times
```

---

### Step 3

Find items that appear together frequently.

Example

```text
Bread + Butter

appears 3 times
```

---

### Step 4

Generate Association Rules.

Example

```text
IF Bread is purchased

THEN Butter is also likely to be purchased.
```

---

## Real-Life Example

Amazon recommends products based on previous customer purchases.

If many customers buy

```text
Mobile Phone

↓

Phone Cover
```

Amazon recommends a phone cover.

---

## Advantages

- ✅ Easy to understand
- ✅ Finds useful buying patterns
- ✅ Useful for recommendation systems

---

## Disadvantages

- ❌ Slow for very large datasets
- ❌ Generates many unnecessary rules
- ❌ Scans the dataset multiple times

---

## Applications

- Product Recommendation
- Market Basket Analysis
- Online Shopping
- Customer Purchase Analysis

---

## Quick Revision

- Unsupervised Learning
- Association Rule Learning
- Finds items bought together
- Uses frequent itemsets to generate rules