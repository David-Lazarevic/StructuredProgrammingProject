# Agent System Instructions

This document provides guidelines and instructions for AI agents (or human developers) assisting in building, testing, or maintaining *The Mindful Kitchen* Java console application.

---

## 🎯 Architecture & Guidelines

### 1. Scope & Complexity Constraints
- **Target Level:** First-semester Computer Science student.
- **Allowed Mechanics:** Standard Console I/O (`Scanner`, `System.out.println`), loops (`while`, `for`), conditionals (`if`, `else`, `switch`), arithmetic calculations, basic array/ArrayList manipulation.
- **Design Rule:** Keep the code procedural or use simple clean methods/classes. Avoid over-engineering, external frameworks, database integrations, or advanced design patterns.

---

## 📋 Core Parameters & Rules

| Parameter | Value / Limit |
| :--- | :--- |
| **Customers Pool Size** | 6 unique customer profiles |
| **Customers per Shift** | 2 random customers |
| **Total Ingredients Pool** | 12 ingredients |
| **Inventory per Shift** | 6 random ingredients |
| **Ingredients per Dish** | Exactly 3 ingredients |
| **Score Scale** | 0 to 100 points per customer |

---

## 🤖 Instructions for AI Coding Assistants

1. **Language & Tools:**
   - Write clean, standard **Java** code.
   - Use `java.util.Scanner` for handling inputs.
   - Use `java.util.Random` for randomizing customers and ingredients.

2. **Error Prevention:**
   - Always wrap input prompts in validation loops (`while` loop) to ensure user inputs are valid integers/commands.

3. **Code Readability:**
   - Include brief inline comments explaining where `INPUT`, `CALCULATE`, `OUTPUT`, `SELECTIONS`, and `LOOPS` occur in the code.
  
