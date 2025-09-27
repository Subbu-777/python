# Python Arithmetic Operators Cheat Sheet

A quick reference for all common arithmetic operators in Python, with examples.

---

## 1️⃣ Addition (`+`)

Adds two numbers.

```python
x = 5
y = 3
print(x + y)  # 8
```

---

## 2️⃣ Subtraction (`-`)

Subtracts second number from first.

```python
x = 5
y = 3
print(x - y)  # 2
```

---

## 3️⃣ Multiplication (`*`)

Multiplies two numbers.

```python
x = 5
y = 3
print(x * y)  # 15
```

---

## 4️⃣ Division (`/`)

True division; returns a float.

```python
x = 7
y = 3
print(x / y)  # 2.3333333333333335
```

---

## 5️⃣ Floor Division (`//`)

Returns the quotient, floored to nearest integer.

```python
x = 7
y = 3
print(x // y)  # 2

x = -7
print(x // y)  # -3
```

---

## 6️⃣ Modulo (`%`)

Returns the remainder of division.

```python
x = 7
y = 3
print(x % y)  # 1

x = -7
print(x % y)  # 2
```

**Formula:** `a = (a // b) * b + (a % b)` ✅

---

## 7️⃣ Exponentiation (`**`)

Raises first number to the power of the second.

```python
x = 2
y = 3
print(x ** y)  # 8
```

---

## 8️⃣ Summary Table

| Operator | Description        | Example                      |
| -------- | ------------------ | ---------------------------- |
| `+`      | Addition           | `5 + 3 = 8`                  |
| `-`      | Subtraction        | `5 - 3 = 2`                  |
| `*`      | Multiplication     | `5 * 3 = 15`                 |
| `/`      | True division      | `7 / 3 = 2.333...`           |
| `//`     | Floor division     | `7 // 3 = 2`, `-7 // 3 = -3` |
| `%`      | Modulo (remainder) | `7 % 3 = 1`, `-7 % 3 = 2`    |
| `**`     | Exponentiation     | `2 ** 3 = 8`                 |

---

### Notes

* Floor division (`//`) always rounds **toward negative infinity**.
* Modulo (`%`) ensures **remainder >= 0** when divisor is positive.
* True division (`/`) always returns a **float**.
