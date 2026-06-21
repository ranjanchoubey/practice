# Hypothesis Testing

Source: GATE-DA Syllabus — Probability and Statistics

---

## Q801

[MCQ]

In hypothesis testing, a Type I error is defined as:

- **(A)** Failing to reject $H_0$ when $H_0$ is false
- **(B)** Rejecting $H_0$ when $H_0$ is true
- **(C)** Accepting $H_1$ when $H_1$ is false
- **(D)** Failing to reject $H_1$ when $H_1$ is true

**Answer:** B

---

## Q802

[MCQ]

The significance level $\alpha$ in hypothesis testing corresponds to:

- **(A)** The probability of a Type II error
- **(B)** The power of the test
- **(C)** The probability of a Type I error
- **(D)** $1 - P(\text{Type II error})$

**Answer:** C

---

## Q803

[MSQ]

Which of the following are true about hypothesis testing? (Select all that apply)

- **(A)** Power of a test = $1 - \beta$ where $\beta$ is the Type II error probability
- **(B)** Increasing $\alpha$ generally decreases $\beta$
- **(C)** Type I and Type II errors can both be eliminated simultaneously by choosing $\alpha = 0.01$
- **(D)** The null hypothesis $H_0$ is the hypothesis of no effect or no difference

**Answer:** A, B, D

---

## Q804

[NAT]

A researcher is testing $H_0: \mu = 50$ vs $H_1: \mu \neq 50$ with known $\sigma = 10$ and $n = 25$. The sample mean is $\bar{x} = 54$. What is the $z$-test statistic?

$$z = \frac{\bar{x} - \mu_0}{\sigma/\sqrt{n}} = \frac{54 - 50}{10/5} = \frac{4}{2} = 2$$

**Answer:** 2

---

## Q805

[MCQ]

A $z$-test statistic is computed as $z = 2.5$ for a two-tailed test at $\alpha = 0.05$. The critical value is $z_{0.025} = 1.96$. What is the conclusion?

- **(A)** Fail to reject $H_0$ since $|z| < 1.96$
- **(B)** Reject $H_0$ since $|z| > 1.96$
- **(C)** Reject $H_0$ since $|z| < 2.5$
- **(D)** Cannot conclude anything without the $p$-value

**Answer:** B

---

## Q806

[NAT]

For a two-tailed $z$-test with $z = 2$, the $p$-value is $2 \times P(Z > 2)$. Given $P(Z > 2) = 0.0228$, what is the $p$-value?

**Answer:** 0.0456

---

## Q807

[MCQ]

When would a $t$-test be used instead of a $z$-test for a one-sample mean test?

- **(A)** When the sample size is large ($n > 30$) and $\sigma$ is known
- **(B)** When the population standard deviation $\sigma$ is unknown and is estimated by the sample standard deviation $s$
- **(C)** When the data is not normally distributed
- **(D)** When testing a proportion rather than a mean

**Answer:** B

---

## Q808

[MCQ]

A chi-square goodness-of-fit test is used with 5 categories. The degrees of freedom for the test statistic is:

- **(A)** 5
- **(B)** 4
- **(C)** 3
- **(D)** 6

**Answer:** B

---

## Q809

[NAT]

In a chi-square goodness-of-fit test, the test statistic is $\chi^2 = \sum \dfrac{(O_i - E_i)^2}{E_i}$. Observed and expected frequencies are:

| Category | O | E |
|----------|---|---|
| A | 20 | 25 |
| B | 30 | 25 |
| C | 25 | 25 |
| D | 25 | 25 |

What is the $\chi^2$ statistic?

$$\chi^2 = \frac{25}{25} + \frac{25}{25} + \frac{0}{25} + \frac{0}{25} = 1 + 1 + 0 + 0 = 2$$

**Answer:** 2

---

## Q810

[MCQ]

If the $p$-value of a test is 0.03 and the significance level is $\alpha = 0.05$, what is the correct decision?

- **(A)** Fail to reject $H_0$ because $p > 0.01$
- **(B)** Reject $H_0$ because $p < \alpha$
- **(C)** Fail to reject $H_0$ because $p < \alpha$
- **(D)** Cannot decide without the test statistic

**Answer:** B

---
