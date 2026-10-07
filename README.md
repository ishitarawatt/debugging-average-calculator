# 🐞 Debugging an Average Calculator (Java)

> **Question 2:** A program calculates an average incorrectly. Find and fix the bug.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

## Common causes checked

| Issue | Why it breaks the average |
|---|---|
| **Integer division** | `7 / 2` gives `3`, not `3.5` |
| **Loop logic errors** | Values skipped or counted twice |
| **Wrong divisor** | Dividing by the wrong count |

## Fix

Use the **correct data types** (floating point for the result) and make sure the loop and divisor match the number of values.

## Run

```bash
javac AverageCalculator.java
java AverageCalculator
```
