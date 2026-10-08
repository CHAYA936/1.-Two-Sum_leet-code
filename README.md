# 🧩 TWO SUM

### One Target. Two Numbers. One Efficient Search.

A simple problem with an important lesson:

> **Don't always search harder. Search smarter.**

Two Sum asks us to find two numbers in an array whose values add up to a given target.

---

## 🎯 THE CHALLENGE

Given an array of integers and a target value:

```text
Find two different elements
whose sum equals the target.
```

Example:

```text
Numbers → [2, 7, 11, 15]
Target  → 9

2 + 7 = 9

Answer → [0, 1]
```

---

## 🧠 THE IDEA

Instead of repeatedly checking every possible pair, we can keep track of values we've already encountered.

For each number:

```text
Current Number
      ↓
Required Number = Target - Current
      ↓
Already Seen?
   ↙       ↘
 YES        NO
  ↓          ↓
FOUND     STORE IT
```

This turns the problem into a search for a **complement**.

---

## ⚡ WHY THIS MATTERS

The interesting part isn't just getting the correct answer.

It's understanding how an inefficient brute-force approach can be improved by choosing the right data structure and algorithm.

```text
BRUTE FORCE
Check every pair
      ↓
More comparisons

HASH-BASED APPROACH
Remember what we've seen
      ↓
Faster lookup
```

---

## ⏱️ COMPLEXITY

**Time:** `O(n)`

**Space:** `O(n)`

The array is scanned once while previously encountered values are stored for quick lookup.

---

## 🛠️ SKILL FOCUS

`Python` · `Arrays` · `Hash Maps` · `Algorithmic Thinking`

---

## 💡 KEY TAKEAWAY

Two Sum looks small.

But it teaches a much bigger programming principle:

> **The right data structure can completely change the way a problem is solved.**

---

### 🧩 CATEGORY

**LeetCode • Arrays • Hashing • Problem Solving**

### 🚀 STATUS
