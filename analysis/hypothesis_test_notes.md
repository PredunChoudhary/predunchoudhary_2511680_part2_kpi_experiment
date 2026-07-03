

## Objective

The purpose of this hypothesis test is to determine whether the new onboarding and activation campaign (Treatment group) resulted in a statistically significant improvement in the Paid Conversion Rate compared to the existing onboarding experience (Control group).

---

# Metric Being Tested

**Primary Metric:** Paid Conversion Rate

Formula:

Paid Conversion Rate = Number of Paid Users ÷ Total Users

This metric was selected because it directly measures the effectiveness of the onboarding campaign in converting users into paying customers. It is the project's North Star Metric and has the strongest connection to business growth.

---

# Null Hypothesis (H₀)

There is **no statistically significant difference** in the Paid Conversion Rate between the Control group and the Treatment group.

Mathematically:

H₀: p(Control) = p(Treatment)

---

# Alternative Hypothesis (H₁)

The Treatment group has a **higher Paid Conversion Rate** than the Control group.

Mathematically:

H₁: p(Treatment) > p(Control)

---

# Type of Test

**One-tailed hypothesis test**

The business objective is specifically to determine whether the new onboarding experience increases paid conversions. Therefore, only improvement is being tested rather than any difference in either direction.

---

# Significance Level

The significance level (α) selected for this analysis is:

**0.05 (5%)**

This means there is a 5% risk of concluding that the Treatment performs better when no true improvement exists.

---

# Decision Rule

- If **p-value < 0.05**, reject the Null Hypothesis.
- If **p-value ≥ 0.05**, fail to reject the Null Hypothesis.

---

# Business Interpretation Logic

If the hypothesis test shows a statistically significant improvement in Paid Conversion Rate, the Treatment onboarding experience provides evidence of better performance and may be recommended for launch, provided that guardrail metrics remain within acceptable limits.

If the result is not statistically significant, the observed improvement may have occurred due to random variation, and the existing onboarding experience should remain in place or additional experimentation should be conducted.

Regardless of the statistical outcome, the final recommendation will also consider guardrail metrics such as Refund Rate, Support Ticket Rate, Engagement Score, Revenue Quality, and Days to Convert before making a launch decision.

---

# Test Results

The hypothesis test compared the Paid Conversion Rate between the Control and Treatment groups.

The calculated one-tailed p-value was **[replace with your Excel result]**.

Since the p-value was **[less than / greater than]** the significance level of 0.05, the **Null Hypothesis was [rejected / not rejected]**.

The results indicate that the new onboarding campaign **[did / did not]** produce a statistically significant improvement in Paid Conversion Rate.

The Treatment group achieved a Paid Conversion Rate of **6.99%**, compared with **3.17%** for the Control group. This suggests that the Treatment experience improved user conversion.

However, the final recommendation should also consider guardrail metrics before deciding whether to launch the new onboarding experience.

-------

# Guardrail Metrics Evaluation

## Purpose

Although the Treatment group demonstrated an improvement in the Paid Conversion Rate, the final business decision should not rely solely on the North Star Metric. Guardrail metrics were evaluated to ensure that the new onboarding experience does not negatively impact customer satisfaction, operational performance, or revenue quality.

---

## Guardrail Metric 1 – Refund Rate

The Treatment group showed a slightly higher Refund Rate than the Control group.

**Interpretation:**

The increase is relatively small but indicates that a few additional users requested refunds after converting. This should be monitored after launch to ensure that increased conversions do not result in lower customer satisfaction.

---

## Guardrail Metric 2 – Support Ticket Rate

The Treatment group recorded a higher Support Ticket Rate compared to the Control group.

**Interpretation:**

This suggests that while the new onboarding process successfully converted more users, it may have introduced additional complexity or confusion that required customer support. The onboarding flow should be reviewed to reduce unnecessary support requests.

---

## Guardrail Metric 3 – Average Engagement Score

The Treatment group achieved a higher Average Engagement Score than the Control group.

**Interpretation:**

This is a positive outcome because users not only converted at a higher rate but also remained more engaged with the product after onboarding.

---

## Revenue Quality

Although Average Revenue per User increased slightly in the Treatment group, the Average Revenue per Converted User was lower than in the Control group.

**Interpretation:**

The Treatment campaign converted more users, but the average revenue generated by each paying customer was lower. This may indicate that lower-priced plans or promotional offers contributed to the increased conversion rate.

---

## Days to Convert

The Treatment group converted users more quickly than the Control group.

**Interpretation:**

A shorter conversion time is generally beneficial because it allows the business to generate revenue sooner and indicates a more effective onboarding experience.

---

## Overall Guardrail Assessment

The Treatment group achieved meaningful improvements in conversion and engagement while introducing moderate increases in refund requests and support tickets. These guardrail metrics do not outweigh the overall business benefits but should continue to be monitored after deployment.