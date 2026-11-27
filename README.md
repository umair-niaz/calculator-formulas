# Calculator Formulas

Plain-language formulas for common everyday calculators, each with a worked example you can check by hand. No dependencies, no sign-up, just the math.

Contents: [Percentage](#percentage) · [Loan payment (EMI)](#loan-payment-emi) · [Compound interest](#compound-interest) · [BMI](#bmi) · [GCF and LCM](#gcf-and-lcm) · [Temperature](#temperature) · [Average](#average) · [Tip](#tip)

---

## Percentage

**Percent of a number**

```
result = (percent / 100) * number
```

Example: 15% of 80 → (15 / 100) * 80 = **12**

**Percent change**

```
change = (new - old) / |old| * 100
```

Example: from 50 to 65 → (65 - 50) / 50 * 100 = **+30%**

---

## Loan payment (EMI)

Monthly payment for a fixed-rate loan:

```
M = P * r * (1 + r)^n / ((1 + r)^n - 1)
```

- `P` = loan amount
- `r` = monthly interest rate = annual rate / 12 / 100
- `n` = number of monthly payments

Example: P = 200,000, annual rate 6%, 30 years
r = 0.06 / 12 = 0.005, n = 360 → **M ≈ 1,199.10 per month**

Total paid = M * n = 431,676 (approx), so total interest ≈ 231,676.

---

## Compound interest

```
A = P * (1 + r / n)^(n * t)
```

- `P` = starting amount
- `r` = annual rate as a decimal (5% = 0.05)
- `n` = times compounded per year
- `t` = years

Example: P = 1,000, r = 5%, compounded yearly, 10 years
A = 1000 * 1.05^10 ≈ **1,628.89**

---

## BMI

```
BMI = weight_kg / height_m^2
```

Example: 70 kg, 1.75 m → 70 / 3.0625 ≈ **22.9**

WHO adult categories:

| BMI | Category |
|---|---|
| below 18.5 | Underweight |
| 18.5 to 24.9 | Normal range |
| 25.0 to 29.9 | Overweight |
| 30.0 and above | Obesity |

BMI is a screening number, not a diagnosis. It does not separate muscle from fat.

---

## GCF and LCM

- **GCF** (greatest common factor): the largest number that divides both numbers.
- **LCM** (least common multiple): the smallest number both numbers divide into.

```
LCM(a, b) = a * b / GCF(a, b)
```

Example: 12 and 18
Factors of 12: 1, 2, 3, 4, 6, 12 · Factors of 18: 1, 2, 3, 6, 9, 18 → GCF = **6**
LCM = 12 * 18 / 6 = **36**

---

## Temperature

```
F = C * 9/5 + 32
C = (F - 32) * 5/9
K = C + 273.15
```

Example: 100 °C → 100 * 9/5 + 32 = **212 °F**, and 100 + 273.15 = **373.15 K**

---

## Average

```
mean = sum of values / number of values
```

Example: 4, 8, 15, 16, 23, 42 → 108 / 6 = **18**

---

## Tip

```
tip = bill * (tip_percent / 100)
each_pays = (bill + tip) / people
```

Example: bill 84, tip 18%, 3 people → tip = 15.12, each pays (84 + 15.12) / 3 = **33.04**

---

## Notes

- Rounding differs between calculators; compare to a few decimals when checking.
- Corrections welcome: open an issue if you spot a mistake.

License: MIT
