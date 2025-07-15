# 🧩 Pattern Problems Collection

A curated repository of common algorithmic "patterns" with explanations, usage guidance, code templates, and sample problems to aid learning and interview preparation.

## 📘 Table of Contents

- [Introduction](#introduction)  
- [Why Use Patterns?](#why-use-patterns)  
- [Patterns Covered](#patterns-covered)  
- [How to Use This Repo](#how-to-use-this-repo)  
- [Contributing](#contributing)  
- [License](#license)

---

## Introduction

In algorithmic problem-solving and technical interviews, recognizing reusable problem-solving *patterns* is vital. This repo gives you:

- Clear definitions of each pattern  
- When and where to apply them  
- Code templates in [Language]  
- LeetCode/Interview example problems

---

## Why Use Patterns?

> “LeetCode is less about how many problems you've solved and more about how many patterns you know.” :contentReference[oaicite:1]{index=1}

By mastering patterns, you reduce the need to reinvent solutions and can tackle new problems more confidently and efficiently.

---

## Patterns Covered

### 1. Sliding Window  
**Definition**: Use a dynamic subarray/window to optimize substring/subarray computations.  
**Use Cases**: Longest/shortest subarray/substring, sum in window, consecutive conditions. :contentReference[oaicite:2]{index=2}  
**Template**:
```python
i = 0
for j in range(len(arr)):
    # expand window with arr[j]
    while window invalid:
        # shrink window by moving i
    # update result
