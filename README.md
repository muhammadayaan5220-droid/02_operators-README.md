# 02_operators-README.md
# ➕ 04: Operators

### 🧠 Learning Outcomes
* Understand different types of operators: **Arithmetic**, **Comparison**, **Logical**, and **Assignment**.
* Learn the concept of **Operator Precedence** (PEMDAS rule).
* Apply operators to manipulate data and make decisions.

---

### 🤔 Why This Matters for Agentic AI
Operators are the "logic gates" of your AI agent.
* **Comparison (`>`, `==`):** Helps an agent decide *when* to act (e.g., `if confidence_score > 0.9`).
* **Logical (`and`, `or`):** Helps handle complex conditions (e.g., `if user_is_verified and request_is_safe`).
* **Arithmetic:** Essential for calculating costs, token counts, or resource usage.

---

### 📚 Operator Types Reference

| Type | Symbol | Description | Example |
| :--- | :--- | :--- | :--- |
| **Arithmetic** | `+`, `-`, `*`, `/`, `//`, `%`, `**` | Math operations. `//` is floor division, `%` is remainder. | `10 % 3` -> `1` |
| **Comparison** | `==`, `!=`, `>`, `<`, `>=`, `<=` | Compares two values. Returns `True` or `False`. | `5 > 3` -> `True` |
| **Logical** | `and`, `or`, `not` | Combines boolean conditions. | `True and False` -> `False` |
| **Assignment** | `=`, `+=`, `-=` | Assigns or updates a value. | `x += 1` |

---

### ✨ Try It Now: Logic Check
Check if a number is within a specific range using comparison and logical operators.

```python
# Try it now
battery_level = 85
is_plugged_in = False

# Check if battery is healthy (between 20% and 80%) OR is currently charging
status_ok = (battery_level > 20 and battery_level < 80) or is_plugged_in
print(f"System Status OK: {status_ok}")

