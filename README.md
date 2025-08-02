# 🧮 Discount Calculator

This is a simple Python function that calculates the final price after applying a discount. It's built as part of a basic assignment for learning Python conditionals and functions.

## 🔧 Functionality

The function `calculate_discount(price, discount_percent)`:

- Accepts two arguments: the original `price` and the `discount_percent`.
- Applies the discount **only** if it's 20% or higher.
- Returns the final price (after discount) or the original price if discount is too low.

## ✅ Example Usage

```python
print(calculate_discount(100, 25))  # Output: 75.0 (25% discount applied)
print(calculate_discount(80, 10))   # Output: 80 (No discount applied)
