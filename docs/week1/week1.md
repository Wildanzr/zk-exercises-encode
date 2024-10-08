# Maths Introduction

## Some modular arithmetic

1.  Working with the following set of Integers S = {0,1,2,3,4,5,6}. What is

    a) 4 + 4

    ```
    4 + 4 = 8
    8 % 7 = 1
    4 + 4 ≡ 1 in S
    ```

    b) 3 x 5

    ```
    3 x 5 = 15
    15 % 7 = 1
    3 x 5 ≡ 1 in S
    ```

    c) what is the inverse of 3 ?

    ```
    3 + 4 = 7
    7 % 7 = 0
    3 + 4 ≡ 0 in
    So, the inverse of 3 is 4
    ```

2.  For S = {0,1,2,3,4,5,6}. Can we consider 'S' and the operation '+' to be a group ?

    ```
    For S to be a group, it must satisfy the following properties:
    1. Closure
    2. Associativity
    3. Identity
    4. Inverse

    1. Closure: For all a, b in S, a + b must be in S
    2. Associativity: For all a, b, c in S, (a + b) + c = a + (b + c)
    3. Identity: There exists an element e in S such that for all a in S, a + e = e + a = a
    4. Inverse: For all a in S, there exists an element b in S such that a + b = b + a = e

    Let's check if S satisfies these properties:
    1. Closure: For all a, b in S, a + b = a + b is in S
    2. Associativity: For all a, b, c in S, (a + b) + c = a + (b + c) is in S
    3. Identity: There exists an element e in S such that for all a in S, a + e = e + a = a
    4. Inverse: For all a in S, there exists an element b in S such that a + b = b + a = e

    Therefore, S is a group
    ```

3.  What is -13 mod 5 ?

    ```
    -13 % 5 = -3
    -13 = 5(-3)
    -13 % -15 = 2
    Since the result can't be negative, we move 5 to the right and multiply by -3. The result is 2
    ```

4.  Polynomials For the polynomial. Find the positive root ? What is the degree of this polynomial ?
    ![polynomial](/docs/images/1.png)

## Use case

In your teams discuss any systems you have used that involved zero knowledge proofs. Have you seen any applications of zero knowledge proofs other than with a blockchain ? What is to you, the most important feature of zkp technology ? Think of some use cases of zero knowledge proofs that you would like to see developed.

```
I think a system to verify if the person's income threshold is within a certain range to apply for a loan or credit card would be a good use case for zero knowledge proofs. The person's income would be verified without revealing the actual amount to the bank or financial institution. This would help to protect the person's privacy while still allowing the bank to verify the person's income.
```
