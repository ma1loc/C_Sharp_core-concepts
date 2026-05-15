# cs00_student_grade_calculator

---

## Summary

Write a C# console application that manages student grades and evaluates their academic performance.

---

## General Rules

- Your project must be written in C#
- Your project must compile without errors
- No external libraries — only `System` and `System.Collections.Generic`
- Handle all edge cases — empty input, invalid grades, and so on
- Your code must be clean and readable

---

## Mandatory Part

### The Student

Create a class `Student` with the following properties:

| Property | Type | Description |
|---|---|---|
| `Name` | string | The student's full name |
| `Grades` | List of integers | All grades for this student |
| `Average` | double | Calculated automatically from the grades list |
| `Status` | string | Either `"Passed"` or `"Failed"` based on the average |

> A student **passes** if their average is **10 or above** out of 20.

---

### The Program

Your program must:

**1 — Add at least 5 students manually in your code** with different names and different sets of grades. Each student must have at least 3 grades.

**2 — Display a full report** in this exact format:

```
===== STUDENT REPORT =====

Name            Average    Status
---------------------------------
Ahmed           15.33      Passed
Sara            9.00       Failed
Youssef         12.67      Passed
Fatima          7.33       Failed
Omar            18.00      Passed

---------------------------------
Class Average:  12.47
Highest Score:  Omar     (18.00)
Lowest Score:   Fatima   (7.33)
Total Passed:   3
Total Failed:   2

==========================
```

**3 — Sort students** from highest average to lowest before displaying.

---

## Bonus Part

> The bonus is only evaluated if the mandatory part is **perfect.**

- **Bonus 1** — Instead of hardcoded students, let the user add students and grades from the console input at runtime.
- **Bonus 2** — Add a method that returns the **top performer** per grade — meaning the student with the highest single grade across all subjects.
- **Bonus 3** — Export the report to a `.txt` file called `report.txt` in the same directory as the program.

---

## Submission

Push your solution inside the folder `cs00_student_grade_calculator` in your `C_Sharp_core-concepts` repo.

Your folder must contain:

```
cs00_student_grade_calculator/
├── Program.cs
├── Student.cs
└── README.md
```

> The `README.md` must explain in 3 lines what the program does and how to run it.

---

*You have no deadline but yourself. Come back when it runs.* 🚀