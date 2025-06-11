# Subset-Selection-Problem # 📘 Subset Selection Problem

## 🧩 1. Problem Statement (Version 1)

- *Goal:* Find all subsets from a given set of numbers whose *sum is zero*.  
- *Constraint:* Subset size must be *exactly 5*.  
- *Input Set:*  
  {12, -3, -6, 7, 2, 2, 6, 3, 9, -7, -5, -8, 1, 11, -9, -4}

---

## 🧩 2. Problem Statement (Version 2)

- *Goal:* Find all subsets from a given set of numbers whose *sum is zero*.  
- *Constraint:* Subset size must be *between 3 and 6 (inclusive)*.  
- *Input Set:*  
  {12, -3, -6, 7, 2, 2, 6, 3, 9, -7, -5, -8, 1, 11, -9, -4}

---

## 💡 Solution Approach

### 🔄 Randomized Algorithm

A flowchart-based random approach is used:

1. Randomly select a subset of given size.
2. Calculate the sum of the subset.
3. If the sum is 0, save it.
4. Repeat until termination condition is met (e.g., max attempts or time limit).

<img width="523" alt="Screenshot 2025-06-11 at 9 52 41 PM" src="https://github.com/user-attachments/assets/0602894f-3d6c-431e-bf9d-8956457fcf5d" />

---

## 🛠 Technologies Used

- Python (Jupyter Notebook)
- Random module
- Combinatorics / Set theory

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/psrana/Mini-Project-Subset-Selection-Problem.git
   cd Mini-Project-Subset-Selection-Problem
