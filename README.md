
# **AIM:**

To understand and implement decision-making in Python using if, elif and else statements through various real-life conditional programs.

---

# **THEORY :**

* **if Statement:** Executes a block only when the given condition is true.
* **elif Statement:** Used to check multiple conditions one after another.
* **else Statement:** Runs when none of the earlier conditions are true.
* **Modulo Operator `%`:** Helps check divisibility, used in even/odd and leap year logic.
* **Comparison Operators:** `>`, `<`, `>=`, `==` used to compare values.
* **Logical Operators:** `and` joins multiple conditions in a single decision.
* **input():** Takes input from the user (string type).
* **Typecasting:** `int()`, `float()` convert input to number for calculations.
* **Membership Operator `in`:** Used to check if a character exists inside a group of characters.

---

 
# ALGORITHMS FOR PROGRAMS:


## **6.1 — Check whether a number is positive, negative or zero**

**Uses:** `input()`, `int()`, comparison operators

1. Start the program.
2. Take a number from the user and convert it to integer.
3. If number > 0, print “positive”.
4. Elif number < 0, print “negative”.
5. Otherwise, print “zero”.
6. Stop.

---

## **6.2 — Check whether a number is even or odd**

**Uses:** `input()`, `int()`, modulo `%`

1. Start the program.
2. Take one integer input from the user.
3. Calculate remainder using `num % 2`.
4. If remainder is 0, print “even”.
5. Else print “odd”.
6. Stop.

---

## **6.3 — Find the largest among a, b and c**

**Uses:** `input()`, `int()`, logical operator `and`

1. Start the program.
2. Accept a, b, c as integers from the user.
3. If a > b and a > c, print “a is largest”.
4. Elif b > a and b > c, print “b is largest”.
5. Else print “c is largest”.
6. Stop.

---

## **6.5 — Calculate average of 3 subjects and assign grade**

**Uses:** `input()`, `int()`, arithmetic operators**

1. Start the program.
2. Take marks for three subjects from the user.
3. Calculate average = (m1+m2+m3)/3.
4. Use `if-elif ladder` to check grade boundaries.
5. Print the assigned grade.
6. Stop.

---

## **6.6 — Check whether a year is leap year or not**

**Uses:** `input()`, `int()`, modulo `%`, logical `and`**

1. Start the program.
2. Take year input from user.
3. If year divisible by 4 and not divisible by 100 → leap year.
4. Elif divisible by 400 → leap year.
5. Otherwise → not a leap year.
6. Stop.

---

## **6.7 — Validate a date and print incremented date**

**Uses:** `input()`, `split()`, `int()`**

1. Start the program.
2. Read date in `dd/mm/yyyy` format and split it into dd, mm, yyyy.
3. Convert all three parts into integers.
4. Set maximum days for the entered month (28/29/30/31).
5. If month or day is invalid → print invalid date.
6. If last day of month and month ≠ 12 → day = 1, month += 1.
7. If date is 31/12 → day=1, month=1, year+=1.
8. Otherwise → day = day + 1.
9. Print incremented date.
10. Stop.

---

## **6.8 — Check whether a character is vowel or consonant**

**Uses:** `input()`, membership operator `in`**

1. Start the program.
2. Take a single character as input.
3. Check if it exists in the string `'aeiouAEIOU'`.
4. If true → vowel.
5. Else → consonant.
6. Stop.

---

## **6.9 — Salary calculation with allowances**

**Uses:** `input()`, `float()`**

1. Start the program.
2. Take basic salary from the user.
3. Check the slab using `if-elif` conditions.
4. Compute HRA and DA as per slab percentage.
5. Compute gross salary = basic + HRA + DA.
6. Print all salary components.
7. Stop.

---

## **6.10 — Income tax calculation**

**Uses:** `input()`, `float()`**

1. Start the program.
2. Take annual income from the user.
3. If income ≤ 2.5 lakh → tax = 0.
4. Elif ≤ 5 lakh → 5% on amount above 2.5 lakh.
5. Elif ≤ 10 lakh → previous slab + 20% on amount above 5 lakh.
6. Else → previous slabs + 30% on amount above 10 lakh.
7. Print total tax to be paid.
8. Stop.

---

# **CONCLUSION (3–4 lines):**

In this experiment, various conditional problems were solved using if-elif-else statements. Logical, comparison, and arithmetic
operators were applied to make decisions such as grade checking, date validation, leap year identification, salary and tax calculation. 
These programs show how decision-making enables Python to behave intelligently based on user input.





