# Discrete Probability Distributions

Source: GATE-DA Syllabus — Probability and Statistics

---

## Q401

[MCQ]

A coin is biased with $P(\text{Head}) = 0.3$. The coin is tossed 10 times. What are $E[X]$ and $\text{Var}(X)$ where $X \sim B(10, 0.3)$?

- **(A)** $E[X] = 3,\ \text{Var}(X) = 2.1$
- **(B)** $E[X] = 3,\ \text{Var}(X) = 3$
- **(C)** $E[X] = 7,\ \text{Var}(X) = 2.1$
- **(D)** $E[X] = 0.3,\ \text{Var}(X) = 0.21$

**Answer:** A

---

## Q402

[NAT]

$X \sim B(5, 0.4)$. What is $P(X = 2)$? Round to 4 decimal places.

$$P(X=2) = \binom{5}{2}(0.4)^2(0.6)^3 = 10 \times 0.16 \times 0.216 = 0.3456$$

**Answer:** 0.3456

---

## Q403

[MSQ]

Which of the following are properties of the Binomial distribution $B(n, p)$? (Select all that apply)

- **(A)** $E[X] = np$
- **(B)** $\text{Var}(X) = np(1-p)$
- **(C)** Each trial has exactly two outcomes
- **(D)** Trials are dependent on each other

**Answer:** A, B, C

---

## Q404

[MCQ]

$X \sim B(n, p)$. For which value of $n$ and $p$ is $\text{Var}(X) = 6$?

- **(A)** $n=10,\ p=0.4$
- **(B)** $n=20,\ p=0.3$
- **(C)** $n=24,\ p=0.25$
- **(D)** $n=8,\ p=0.5$

**Answer:** C

---

## Q405

[MCQ]

$X \sim \text{Poisson}(\lambda = 3)$. What is $P(X = 0)$? (Use $e^{-3} \approx 0.0498$)

- **(A)** 0.1494
- **(B)** 0.0498
- **(C)** 0.3
- **(D)** 0.0166

**Answer:** B

---

## Q406

[NAT]

For a Poisson distribution with $\lambda = 4$, what is $E[X] + \text{Var}(X)$?

**Answer:** 8

---

## Q407

[MCQ]

$X \sim \text{Poisson}(\lambda)$. The probability $P(X = 1) = P(X = 2)$. What is $\lambda$?

- **(A)** 1
- **(B)** 2
- **(C)** 3
- **(D)** 0.5

**Answer:** B

---

## Q408

[NAT]

$X \sim \text{Geometric}(p = 0.25)$. What is $E[X]$ (number of trials until first success)?

**Answer:** 4

---

## Q409

[MCQ]

A geometric random variable $X$ with parameter $p$ has the memoryless property. This means:

- **(A)** $P(X > m + n | X > m) = P(X > n)$ for all $m, n \geq 0$
- **(B)** $P(X > m + n) = P(X > m) + P(X > n)$
- **(C)** $E[X | X > m] = E[X] - m$
- **(D)** $P(X = k) = (1-p)^k$ for all $k \geq 1$

**Answer:** A

---

## Q410

[NAT]

$X \sim \text{Geometric}(p = 0.5)$. What is $P(X = 3)$? (Here $X$ counts trials until first success.)

$$P(X=3) = (1-0.5)^{3-1} \times 0.5 = 0.25 \times 0.5 = 0.125$$

**Answer:** 0.125

---
