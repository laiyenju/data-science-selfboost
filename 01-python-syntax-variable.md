# 01 [Python] Syntax, Variables and Numbers

## Basics

- assign an variable: `spam_amount = 4`
- print: `print(spam_amount)`
- operator with string
```python
viking_song = "Spam " * spam_amount
print(viking_song)

# Spam Spam Spam Spam
```

### Numbers and arithmetic in Python

```python
type(spam_amount) #int
type(19.95) #float
```

| Operator | Name | Description |
| :--- | :--- | :--- |
| a + b	| Addition	| Sum of a and b |
| a - b	| Subtraction | Difference of a and b |
| a * b	| Multiplication | Product of a and b |
| a / b	| True division | Quotient of a and b |
| a // b | Floor division | Quotient of a and b, removing fractional parts |
| a % b	| Modulus | Integer remainder after division of a by b |
| a ** b | Exponentiation | a raised to the power of b |
| -a | Negation | The negative of a |

### Builtin functions for working with numbers

```python
print(min(1, 2, 3))  #1
print(max(1, 2, 3))  #3
print(abs(-32))  #32
print(float(10))  #10.0
print(int(3.33))  #3
# They can even be called on strings!
print(int('807') + 1)  #808
```

## Reference

- [Python for Non-Programmers](https://wiki.python.org/moin/BeginnersGuide/NonProgrammers)

