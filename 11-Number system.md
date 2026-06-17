# Number Systems

## Introduction

A Number System is a method of representing numbers using a set of digits or symbols.

Computers understand and process data using the **Binary Number System (0 and 1)**, while humans commonly use the **Decimal Number System (0–9)**.

Understanding number systems is important for programming, computer architecture, data representation, and digital electronics.

---

# What is a Number System?

## Definition

A Number System is a way of representing numbers using a specific set of digits and rules.

Every number system has:

* Digits
* Base (Radix)

### Base (Radix)

The number of unique digits used in a number system.

Example:

* Decimal → Base 10
* Binary → Base 2

---

# Types of Number Systems

```text
Number Systems
│
├── Decimal (Base 10)
├── Binary (Base 2)
├── Octal (Base 8)
└── Hexadecimal (Base 16)
```

---

# 1. Decimal Number System

## Definition

The Decimal Number System is the standard number system used in daily life.

## Base

```text
Base = 10
```

## Digits Used

```text
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```

## Example

```text
357
```

### Place Values

```text
357 = (3 × 10²) + (5 × 10¹) + (7 × 10⁰)

    = 300 + 50 + 7

    = 357
```

---

# 2. Binary Number System

## Definition

The Binary Number System is the number system used internally by computers.

## Base

```text
Base = 2
```

## Digits Used

```text
0 and 1
```

## Example

```text
1011₂
```

### Conversion to Decimal

```text
1011₂

= (1 × 2³)
+ (0 × 2²)
+ (1 × 2¹)
+ (1 × 2⁰)

= 8 + 0 + 2 + 1

= 11₁₀
```

### Why Computers Use Binary?

Electronic circuits have two states:

```text
ON  = 1
OFF = 0
```

Therefore computers use binary numbers.

---

# 3. Octal Number System

## Definition

The Octal Number System uses eight digits.

## Base

```text
Base = 8
```

## Digits Used

```text
0, 1, 2, 3, 4, 5, 6, 7
```

## Example

```text
725₈
```

### Conversion to Decimal

```text
725₈

= (7 × 8²)
+ (2 × 8¹)
+ (5 × 8⁰)

= 448 + 16 + 5

= 469₁₀
```

---

# 4. Hexadecimal Number System

## Definition

The Hexadecimal Number System uses sixteen symbols.

## Base

```text
Base = 16
```

## Digits Used

```text
0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F
```

### Values

```text
A = 10
B = 11
C = 12
D = 13
E = 14
F = 15
```

## Example

```text
2A₁₆
```

### Conversion to Decimal

```text
2A₁₆

= (2 × 16¹)
+ (10 × 16⁰)

= 32 + 10

= 42₁₀
```

---

# Number System Comparison

| Number System | Base | Digits Used |
| ------------- | ---- | ----------- |
| Decimal       | 10   | 0–9         |
| Binary        | 2    | 0,1         |
| Octal         | 8    | 0–7         |
| Hexadecimal   | 16   | 0–9, A–F    |

---

# Number Conversions

## Decimal to Binary

### Method

Repeatedly divide by 2 and note remainders.

### Example

Convert 13₁₀ to Binary

```text
13 ÷ 2 = 6 R1
6 ÷ 2 = 3 R0
3 ÷ 2 = 1 R1
1 ÷ 2 = 0 R1
```

Read from bottom to top:

```text
13₁₀ = 1101₂
```

---

## Binary to Decimal

### Example

Convert 1010₂ to Decimal

```text
(1 × 2³)
+ (0 × 2²)
+ (1 × 2¹)
+ (0 × 2⁰)

= 8 + 0 + 2 + 0

= 10₁₀
```

---

## Binary to Octal

### Rule

Group binary digits into sets of 3 from right.

### Example

```text
101101₂

101 101

= 5 5

= 55₈
```

---

## Binary to Hexadecimal

### Rule

Group binary digits into sets of 4 from right.

### Example

```text
10101111₂

1010 1111

A    F

= AF₁₆
```

---

# Applications of Number Systems

## Decimal

* Daily calculations
* Banking
* Education

## Binary

* Computer processing
* Digital circuits

## Octal

* Computer systems
* Digital electronics

## Hexadecimal

* Memory addresses
* Web color codes
* Programming

---

# Summary

* Number systems represent numerical values.
* Decimal uses base 10.
* Binary uses base 2.
* Octal uses base 8.
* Hexadecimal uses base 16.
* Computers use binary because electronic circuits work with ON/OFF states.
* Number conversions are important in programming and computer science.

---

# Interview Questions

### Q1. What is a Number System?

A method of representing numbers using specific digits and rules.

### Q2. Which number system is used by computers?

Binary Number System.

### Q3. What is the base of Decimal?

10.

### Q4. What is the base of Binary?

2.

### Q5. What digits are used in Binary?

0 and 1.

### Q6. What is the base of Octal?

8.

### Q7. What is the base of Hexadecimal?

16.

### Q8. What does A represent in Hexadecimal?

10.

### Q9. Convert Binary 1010₂ to Decimal.

10₁₀.

### Q10. Why do computers use Binary?

Because electronic circuits operate using ON (1) and OFF (0) states.

---

# Quick Revision

```text
DECIMAL      → Base 10 → 0-9
BINARY       → Base 2  → 0,1
OCTAL        → Base 8  → 0-7
HEXADECIMAL  → Base 16 → 0-9, A-F

A = 10
B = 11
C = 12
D = 13
E = 14
F = 15

Computers Use → Binary
```

## Memory Trick

```text
D → Decimal → 10
B → Binary → 2
O → Octal → 8
H → Hex → 16

DBOH
10 → 2 → 8 → 16
```
