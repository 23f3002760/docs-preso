---
marp: true
theme: gaia
paginate: true
backgroundColor: #fff
header: 'Product Documentation v2.0'
footer: '23f3002760@ds.study.iitm.ac.in'
math: mathjax
style: |
  section {
    font-family: 'Helvetica', sans-serif;
  }
  code {
    background-color: #f4f4f4;
    border-radius: 4px;
  }
  .highlight {
    color: #d32f2f;
    font-weight: bold;
  }
---

# Product Documentation
## API & System Architecture

**Technical Writer:** 23f3002760
**Contact:** 23f3002760@ds.study.iitm.ac.in

---

## 1. Algorithmic Complexity

We utilize an optimized sorting mechanism to ensure low latency. The average case time complexity is defined mathematically as:

$$
T(n) = O(n \log n) + \frac{1}{\epsilon} \sum_{i=0}^{k} \alpha^i
$$

Where:
- $n$ is the number of records
- $\epsilon$ is the efficiency constant

---

## 2. Installation Guide

To install the core package, run the following command in your terminal:

```bash
npm install @company/core-sdk --save
