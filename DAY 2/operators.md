# Python Operators

Python operators are special symbols that perform operations on variables and values. Here's a breakdown of the major categories of operators in Python:

## 1. Arithmetic Operators
Used to perform mathematical operations:

| Operator | Description         | Example        |
|----------|---------------------|----------------|
| `+`      | Addition             | `a + b`        |
| `-`      | Subtraction          | `a - b`        |
| `*`      | Multiplication       | `a * b`        |
| `/`      | Division             | `a / b`        |
| `//`     | Floor Division       | `a // b`       |
| `%`      | Modulus              | `a % b`        |
| `**`     | Exponentiation       | `a ** b`       |

## 2. Comparison Operators
Used to compare two values:

| Operator | Description         | Example        |
|----------|---------------------|----------------|
| `==`     | Equal to             | `a == b`       |
| `!=`     | Not equal to         | `a != b`       |
| `>`      | Greater than         | `a > b`        |
| `<`      | Less than            | `a < b`        |
| `>=`     | Greater or equal     | `a >= b`       |
| `<=`     | Less or equal        | `a <= b`       |

## 3. Logical Operators
Used to combine conditional statements:

| Operator | Description         | Example            |
|----------|---------------------|--------------------|
| `and`    | Logical AND          | `a and b`          |
| `or`     | Logical OR           | `a or b`           |
| `not`    | Logical NOT          | `not a`            |

## 4. Assignment Operators
Used to assign values to variables:

| Operator | Description                  | Example       |
|----------|------------------------------|---------------|
| `=`      | Assign                       | `a = 5`        |
| `+=`     | Add and assign               | `a += 3`       |
| `-=`     | Subtract and assign          | `a -= 2`       |
| `*=`     | Multiply and assign          | `a *= 4`       |
| `/=`     | Divide and assign            | `a /= 2`       |
| `//=`    | Floor divide and assign      | `a //= 3`      |
| `%=`     | Modulus and assign           | `a %= 2`       |
| `**=`    | Exponentiate and assign      | `a **= 2`      |

## 5. Bitwise Operators
Operate on binary numbers:

| Operator | Description         | Example        |
|----------|---------------------|----------------|
| `&`      | Bitwise AND          | `a & b`        |
| `|`      | Bitwise OR           | `a | b`        |
| `^`      | Bitwise XOR          | `a ^ b`        |
| `~`      | Bitwise NOT          | `~a`           |
| `<<`     | Left Shift           | `a << 2`       |
| `>>`     | Right Shift          | `a >> 2`       |

## 6. Membership Operators
Test for membership in a sequence:

| Operator | Description         | Example        |
|----------|---------------------|----------------|
| `in`     | Present in sequence  | `'a' in 'apple'`|
| `not in` | Not present          | `'b' not in 'apple'`|

## 7. Identity Operators
Compare memory locations:

| Operator | Description         | Example        |
|----------|---------------------|----------------|
| `is`     | Same object          | `a is b`       |
| `is not` | Not the same object  | `a is not b`   |

---

# Truthy and Falsy Values in Python

In Python, every value has an inherent truth value (either **truthy** or **falsy**) when evaluated in a boolean context like an `if` statement.

## ✅ Truthy Values
Evaluate to `True`:

- **Non-zero numbers**: `1`, `-1`, `3.14`, etc.
- **Non-empty sequences/collections**:
  - Strings: `'hello'`, `'0'`
  - Lists: `[0]`, `[None]`
  - Tuples: `(0,)`, `('a',)`
  - Sets/Dictionaries: `{1}`, `{'a': 1}`
- **Boolean**: `True`
- **Custom objects** (unless `__bool__` or `__len__` returns `False`)

## ❌ Falsy Values
Evaluate to `False`:

- `None`
- `False`
- Zero of any numeric type: `0`, `0.0`, `0j`
- Empty sequences/collections:
  - `''`, `[]`, `()`, `{}`, `set()`
- Custom objects where `__bool__()` or `__len__()` returns `False`

These values are essential when using conditions in control flow, comprehensions, and logical expressions.

