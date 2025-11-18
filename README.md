# 🎓 Student Grade Calculator (Python)

This project is a simple and interactive **Student Grade Calculator** built using Python.  
It allows users to enter their marks (0–100) and returns a grade (A, B, C, D, or F) along with an **encouraging message** based on their performance.

This is a perfect beginner-friendly project for learning:
- Input handling  
- Conditional statements (if-elif-else)  
- Basic validation  
- User interaction in Python  

---

## 📘 Features

- Accepts marks from the user  
- Validates input to ensure marks are between **0 and 100**  
- Categorizes marks into **grades (A–F)**  
- Displays a **motivational message** for each grade  
- Simple, clean, and easy to modify  

---

## 🧠 Grade Criteria

| Marks Range | Grade | Message |
|------------|--------|---------|
| 90–100     | A      | ⭐ Excellent work! Keep shining! |
| 80–89      | B      | 👍 Great job! You're doing very well! |
| 70–79      | C      | 🙂 Good effort! Keep improving! |
| 60–69      | D      | 💪 You passed! A little more effort will take you further! |
| 0–59       | F      | 🔄 Don’t give up! Learn from mistakes and try again! |

---

## 🛠️ How It Works

1. The user enters their marks.  
2. The program checks whether the input is valid.  
3. Based on the value, the program assigns a **grade**.  
4. A **friendly, motivational message** is displayed.  

---

## 💻 Code Example

```python
marks = float(input("Enter your marks (0–100): "))

if marks >= 90:
    grade = "A"
    message = "Excellent work! Keep shining! 🌟"
elif marks >= 80:
    grade = "B"
    message = "Great job! You're doing very well! 👍"
elif marks >= 70:
    grade = "C"
    message = "Good effort! Keep improving! 🙂"
elif marks >= 60:
    grade = "D"
    message = "You passed! A little more effort will take you further! 💪"
else:
    grade = "F"
    message = "Don't give up! Learn from mistakes and try again! 🔄"

print(f"\nYour Grade: {grade}")
print(message)
