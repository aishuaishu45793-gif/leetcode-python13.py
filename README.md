# LeetCode Python Practice 14 🐍

## 📌 About This Project

This repository contains my **Python programming and LeetCode practice solutions**. The project is focused on building strong programming fundamentals, improving logical thinking, and learning Data Structures and Algorithms (DSA).

## 🎯 Objectives

* Learn Python programming step by step
* Practice coding problems regularly
* Improve problem-solving and logical thinking
* Learn Data Structures and Algorithms
* Practice LeetCode-style problems
* Track my coding progress using GitHub

## 🛠️ Technologies Used

* **Python 3**
* **LeetCode**
* **Visual Studio Code**
* **Git**
* **GitHub**

## 📚 Topics Covered

### Python Fundamentals

* Variables
* Data Types
* Input and Output
* Operators
* Conditional Statements
* `for` Loops
* `while` Loops
* Functions

### Python Data Structures

* Strings
* Lists
* Tuples
* Sets
* Dictionaries

### Problem Solving

* Number Problems
* String Problems
* Array Problems
* Searching
* Sorting
* Hashing
* Two Pointers
* Sliding Window

### Data Structures & Algorithms

* Stack
* Queue
* Linked List
* Binary Tree
* Binary Search Tree
* Heap
* Graph
* Recursion
* Backtracking
* Dynamic Programming

## 💻 Example Problem

### Two Sum

```python
class Solution:
    def twoSum(self, nums, target):
        for i in range(len(nums)):
            for j in range(i + 1, len(nums)):
                if nums[i] + nums[j] == target:
                    return [i, j]


solution = Solution()

nums = [2, 7, 11, 15]
target = 9

print(solution.twoSum(nums, target))
```

### Output

```text
[0, 1]
```

## ▶️ How to Run

### 1. Check Python

Open the terminal and run:

```bash
python --version
```

### 2. Clone the Repository

```bash
git clone https://github.com/aishuaishu45793-gif/leetcode-python14.py.git
```

### 3. Open the Project

Open the downloaded folder in **Visual Studio Code**.

### 4. Run a Python File

```bash
python filename.py
```

## 📁 Project Structure

```text
leetcode-python14.py/
│
├── README.md
├── hello_world.py
├── variables.py
├── conditions.py
├── loops.py
├── functions.py
├── strings.py
├── lists.py
├── two_sum.py
├── palindrome.py
├── fizz_buzz.py
├── searching.py
└── sorting.py
```

## 🧠 Problem-Solving Approach

For each problem, I follow these steps:

1. Understand the problem
2. Identify the inputs and outputs
3. Think about a simple solution
4. Write the Python code
5. Test with different examples
6. Check edge cases
7. Improve the solution
8. Analyze time and space complexity
9. Save the solution to GitHub

## 📈 Learning Progress

* [x] Python Basics
* [x] Variables and Data Types
* [x] Conditions
* [x] Loops
* [x] Functions
* [x] Strings
* [x] Lists
* [x] Dictionaries
* [ ] Stack and Queue
* [ ] Linked List
* [ ] Trees
* [ ] Graphs
* [ ] Dynamic Programming

## 🔄 GitHub Workflow

After adding new practice programs:

```bash
git add .
git commit -m "Add new LeetCode problems"
git push
```

## 🎓 Learning Outcomes

This project helps me improve:

* Python programming
* Logical thinking
* Problem-solving skills
* Data Structures and Algorithms
* Debugging
* Algorithmic thinking
* Git and GitHub
* Consistent coding practice

## 🚀 Future Goals

* Solve more LeetCode problems
* Practice Easy, Medium, and Hard problems
* Improve time and space complexity
* Learn advanced DSA
* Build real-world Python projects
* Prepare for technical interviews

## 👩‍💻 Author

**Aishwarya**

This repository is part of my continuous learning journey in **Python, LeetCode, and Data Structures & Algorithms**.

---

⭐ **Keep practicing. Keep coding. Keep improving!**
