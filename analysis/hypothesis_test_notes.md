# Hypothesis Test Notes

## Business Objective

The objective of this A/B experiment is to determine whether the new onboarding campaign (Treatment) significantly improves the Paid Conversion Rate compared with the existing onboarding experience (Control).

---

## North Star Metric

**Paid Conversion Rate**

Formula:

Paid Conversion Rate = Paid Users ÷ Total Users

---

## Hypotheses

### Null Hypothesis (H₀)

There is no statistically significant difference in Paid Conversion Rate between the Control and Treatment groups.

H₀: pTreatment = pControl

### Alternative Hypothesis (H₁)

The Treatment group has a higher Paid Conversion Rate than the Control group.

H₁: pTreatment > pControl

---

## Test Type

One-tailed Chi-Square Test of Independence

Reason:

The business objective is specifically to determine whether the Treatment increases conversion.

---

## Significance Level

α = 0.05

---

## Test Inputs

| Group     | Paid | Not Paid | Total |
| --------- | ---: | -------: | ----: |
| Control   |   22 |      671 |   693 |
| Treatment |   50 |      665 |   715 |

Expected Frequencies

| Group     |    Paid | Not Paid |
| --------- | ------: | -------: |
| Control   | 35.4375 | 657.5625 |
| Treatment | 36.5625 | 678.4375 |

---

## Excel Result

P-value = **0.001146479**

Alpha = **0.05**

Decision:

Since 0.001146479 < 0.05,

**Reject the Null Hypothesis**

---

## Business Interpretation

The Treatment onboarding campaign significantly improves Paid Conversion Rate compared to the existing onboarding process.

The probability that this improvement occurred due to random chance is extremely small. Therefore, the Treatment campaign demonstrates a statistically significant positive business impact and is recommended for rollout, while continuing to monitor refund rate, support tickets, engagement score, and long-term retention.

