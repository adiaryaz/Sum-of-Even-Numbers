# Sum of Even Numbers

A program to calculate the sum of all even numbers from a user-defined series of inputs.

## 📝 Description

This program first prompts the user for a number, `n`, which specifies how many integers will be entered subsequently. It then reads `n` numbers one by one. The program identifies all the even numbers (both positive and negative) from the list and calculates their total sum.

-----

## 🎯 Problem Statement

### Input:

  * The first input is a single positive integer (`n`).
  * The next `n` inputs are the integers to be evaluated.

### Output:

  * The total sum of all even numbers entered.
  * "NotProceed" if the first input `n` is not a positive integer.

### Rules:

1.  The first input **n** (the count of numbers to follow) must be a **positive integer**.
2.  If `n` is zero or negative, the program should output the message **"NotProceed"**.
3.  The program will then read `n` integers, which can be positive, negative, or zero.
4.  The program must determine which of these numbers are even (a number `x` is even if `x % 2 == 0`).
5.  The final output should be the sum of only these even numbers.

-----

## 💡 Examples

### Example 1 (n = 2)

**Input:**

```
2
1
2
```

**Output:**

```
2
```

**Explanation:** Out of the numbers `1` and `2`, only `2` is even. The sum is **2**.

### Example 2 (n = 3)

**Input:**

```
3
1
2
2
```

**Output:**

```
4
```

**Explanation:** Out of `1`, `2`, `2`, the even numbers are `2` and `2`. The sum is **4**.

### Example 3 (n = 4)

**Input:**

```
4
2
3
2
-2
```

**Output:**

```
2
```

**Explanation:** The even numbers are `2`, `2`, and `-2`. The sum is `2 + 2 + (-2) = 2`.

### Example 4 (n = -5)

**Input:**

```
-5
```

**Output:**

```
NotProceed
```

**Explanation:** The first input `n` is negative, which is not a valid count.

-----

## 🚀 How to Use

1.  **Clone this repository**

    ```bash
    git clone https://github.com/adiaryaz/Sum-of-Even-Numbers.git
    cd sum-of-evens
    ```

2.  **Run the program** (assuming the file is `main.py`):

    ```bash
    python main.py
    ```

    Enter the count `n` first, then enter `n` integers to see the result.
