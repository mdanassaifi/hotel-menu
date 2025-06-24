
# 🧾 Simple Restaurant Ordering System (Python Script)

This is a basic **Python-based console restaurant menu system** where users can place an order, add additional items, and even apply a coupon for a discount.

---

## 🍽️ Features

- View a predefined menu with prices.
- Place an order by item name.
- Option to order more than one item.
- Special condition: Only coffee cannot be ordered alone.
- Apply a 20% discount using a coupon code (`Anas`).

---

## 📜 Menu

```
Pizza   : ₹120  
Burger  : ₹80  
Salad   : ₹40  
Coffe   : ₹25  
```

---

## 💡 How It Works

1. The program shows the menu.
2. You enter your first order item.
3. You're asked if you'd like to order more:
   - If **No** and the item is not `Coffe`, your bill is shown.
   - If **No** and the item is `Coffe`, it's rejected (rule: can't order only coffee).
   - If **Yes**, you're prompted for a second item.
4. If you have a coupon code (`Anas`), you get a **20% discount** on your total bill.
5. Final bill is shown with or without discount.

---

## ▶️ How to Run

1. Copy the code into a Python file, e.g. `restaurant.py`.
2. Open a terminal or command prompt.
3. Run using:

```bash
python restaurant.py
```

---

## 📝 Sample Coupon Code

Use `Anas` to get **20% OFF**.

---

## 💻 Code Sample

```python
menu = {
    'Pizza': 120,
    'Burger': 80,
    'Salad': 40,
    'Coffe': 25,
    'Anas': 0.2,
}
...
```

---

## 📌 Notes

- Ensure correct spelling when entering items.
- Coupon code is case-sensitive.

---

## 🙏 Thank You


