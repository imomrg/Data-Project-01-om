# 📘 FP Growth Algorithm

## What is FP Growth Algorithm?

FP Growth (Frequent Pattern Growth) is an **Unsupervised Learning** algorithm used in **Association Rule Learning**.

It performs the **same task as Apriori** but **much faster**, especially for large datasets.

Instead of checking the dataset again and again, it stores important information in a special structure called an **FP Tree**.

---

## Why was FP Growth created?

Apriori scans the dataset many times, making it slow.

FP Growth solves this problem by creating an **FP Tree**, so it doesn't need to repeatedly scan the entire dataset.

This makes it faster and more efficient.

---

## How does it work?

### Step 1

Collect transaction data.

Example

```text
Bread, Butter, Milk

Bread, Butter

Bread, Eggs

Milk, Bread
```

---

### Step 2

Create an **FP Tree**.

The FP Tree stores only the important and frequent items in a compact form.

---

### Step 3

Search the FP Tree to find frequent item combinations.

Example

```text
Bread + Butter

appears frequently.
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

Amazon and Flipkart recommend products by analyzing millions of customer purchases.

Since they have huge datasets, they prefer faster algorithms like **FP Growth** instead of Apriori.

---

## Advantages

- ✅ Faster than Apriori
- ✅ Fewer database scans
- ✅ Efficient for large datasets
- ✅ Generates frequent patterns quickly

---

## Disadvantages

- ❌ More difficult to understand
- ❌ FP Tree construction requires extra memory

---

## Applications

- Product Recommendation
- Market Basket Analysis
- Shopping Websites
- Sales Analysis

---

## Quick Revision

- Unsupervised Learning
- Association Rule Learning
- Faster than Apriori
- Uses an FP Tree
- Suitable for large datasets