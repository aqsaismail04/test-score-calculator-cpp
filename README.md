<h1 align="center">📊 Test Score Calculator</h1>
<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Course-Programming%20Fundamentals-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IDE-Visual%20Studio-purple?style=for-the-badge&logo=visualstudio&logoColor=white"/>
</p>

---

## 📌 Overview

A C++ program that takes test scores as input, validates them,
sorts them using Bubble Sort, and calculates the average.
Uses dynamic memory allocation with pointers.

---

## ⚙️ Features

| Feature | Description |
|---------|-------------|
| ✅ Input Validation | Rejects negative numbers |
| 🔃 Sorting | Sorts scores using Bubble Sort |
| 🧮 Average | Calculates average of all scores |
| 🖥️ Display | Shows sorted scores and average |
| 🧠 Dynamic Memory | Uses dynamic arrays with pointers |

---

## 🧠 Concepts Used

![Pointers](https://img.shields.io/badge/Pointers-blueviolet?style=for-the-badge)
![Dynamic Memory](https://img.shields.io/badge/Dynamic%20Memory-orange?style=for-the-badge)
![Functions](https://img.shields.io/badge/Functions-blue?style=for-the-badge)
![Bubble Sort](https://img.shields.io/badge/Bubble%20Sort-red?style=for-the-badge)
![Loops](https://img.shields.io/badge/Loops-yellow?style=for-the-badge)

---

## 🔧 Functions Used

| Function | Type | Description |
|----------|------|-------------|
| `inputvalidation()` | double | Validates score is not negative |
| `getelementsofarray()` | void | Takes scores as input |
| `sorting()` | void | Sorts scores using Bubble Sort |
| `average()` | double | Calculates average of scores |
| `display()` | void | Displays sorted scores and average |

---

## 📤 Sample Output

```
Enter the number of test scores: 3
Enter test 1 Score: 85
Enter test 2 Score: 92
Enter test 3 Score: 78

Sorted Array
Test 1 Score: 78
Test 2 Score: 85
Test 3 Score: 92
Average of All Test Scores: 85
```

---

## ▶️ How to Run

### 🖥️ Visual Studio
1. Create new **Empty Project** → C++
2. Add `main.cpp` to project
3. Press **Ctrl + F5** to Run
4. Enter number of scores when prompted

### 💻 VS Code
```bash
g++ main.cpp -o output
./output
```

### 🖱️ Dev C++
1. Open `main.cpp`
2. Press **F11** to Compile & Run

---

## 📁 Project Files

```
test-score-calculator-cpp/
├── main.cpp        → main source code
└── README.md       → project documentation
```

---

## ⚠️ Important Notes

- Negative scores are not accepted
- Dynamic memory freed using `delete[]`
- No file handling needed — console based

---

## 👩‍💻 Author

**Aqsa Ismail** | [GitHub](https://github.com/aqsaismail04) | [LinkedIn](https://www.linkedin.com/in/aqsaismail04/)
