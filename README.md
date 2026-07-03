# KPI Experiment Analysis

## Business Context

A subscription-based digital product company launched a new onboarding and activation campaign to improve user conversion and early engagement. Users were randomly assigned to one of two groups:

- **Control Group:** Existing onboarding experience
- **Treatment Group:** New onboarding and activation campaign

The objective of this analysis was to determine whether the new onboarding campaign should be launched to all users based on experimental evidence while ensuring that customer experience and business performance were not negatively affected.

---

# Dataset Description

The dataset contains user-level experiment data for both Control and Treatment groups.

The data includes:

- User ID
- Experiment Group
- Region
- Device Type
- Traffic Source
- Plan Type
- Landing Page Visit
- Trial Start
- Onboarding Completion
- Paid Conversion
- Revenue
- Refund Request
- Support Tickets
- Engagement Score
- Days to Convert

The dataset was cleaned and validated before analysis.

---

# Business Problem

The leadership team wants to determine whether the new onboarding experience produces a meaningful improvement in user conversion while maintaining acceptable customer experience.

The decision impacts:

- Product Team
- Marketing Team
- Revenue Team
- Customer Success Team

The primary objective is to increase the number of users who become paying subscribers without increasing customer dissatisfaction or reducing revenue quality.

---

# North Star Metric

**Paid Conversion Rate**

Formula:

Paid Conversion Rate = Paid Users ÷ Total Users

This metric was selected because it directly measures business growth by tracking the percentage of users who become paying customers.

---

# Supporting Metrics

The following supporting metrics were also analyzed:

- Landing Page Visit Rate
- Trial Start Rate
- Onboarding Completion Rate
- Average Revenue per User
- Average Revenue per Converted User
- Refund Rate
- Support Ticket Rate
- Average Engagement Score
- Average Days to Convert

---

# KPI Tree Summary

The KPI Tree identifies **Paid Conversion Rate** as the North Star Metric.

Primary KPI Drivers:

### User Acquisition

- Landing Page Visit Rate
- Trial Start Rate

### Onboarding Success

- Onboarding Completion Rate
- Engagement Score

### Revenue Quality

- Average Revenue per User
- Average Revenue per Converted User

Guardrail Metrics:

- Refund Rate
- Support Ticket Rate
- Average Engagement Score
- Days to Convert

---

# Data Cleaning and Preparation

Before analysis, the dataset was reviewed for data quality.

The following checks were completed:

- Missing values
- Duplicate User IDs
- Control vs Treatment group counts
- Binary value validation
- Revenue outlier review
- Region distribution
- Device Type distribution
- Traffic Source distribution
- Plan Type distribution

Missing categorical values were replaced with **"Unknown"** where appropriate. Missing Engagement Scores were filled using the column average. The Days to Convert field was reviewed and handled according to the available dataset values.

---

# Experiment Analysis Approach

The experiment was analyzed by comparing Control and Treatment groups across multiple business metrics.

The following KPIs were calculated:

- User Count
- Landing Page Visit Rate
- Trial Start Rate
- Onboarding Completion Rate
- Paid Conversion Rate
- Average Revenue per User
- Average Revenue per Converted User
- Refund Rate
- Support Ticket Rate
- Average Engagement Score
- Average Days to Convert

Additional segment analysis was performed using:

- Region
- Device Type
- Traffic Source

---

# Hypothesis Test Summary

A one-tailed hypothesis test was performed using Paid Conversion Rate as the primary metric.

### Null Hypothesis (H₀)

There is no significant difference in Paid Conversion Rate between the Control and Treatment groups.

### Alternative Hypothesis (H₁)

The Treatment group has a higher Paid Conversion Rate than the Control group.

### Significance Level

α = 0.05

The hypothesis test was used to determine whether the observed improvement was statistically significant.

---

# Guardrail Metrics Considered

To avoid making a decision based only on conversion improvement, the following guardrail metrics were evaluated:

- Refund Rate
- Support Ticket Rate
- Average Engagement Score
- Average Revenue per Converted User
- Days to Convert

These metrics helped ensure that improved conversion did not negatively impact customer satisfaction or revenue quality.

---

# Model / Experiment Findings

The Treatment group demonstrated improvements in several key business metrics, including:

- Higher Landing Page Visit Rate
- Higher Trial Start Rate
- Higher Onboarding Completion Rate
- Higher Paid Conversion Rate
- Higher Engagement Score
- Faster user conversion

The analysis also identified moderate increases in Support Ticket Rate and Refund Rate, which should continue to be monitored after deployment.

---

# Final Recommendation

**Recommendation: Launch the Treatment onboarding experience.**

The Treatment group demonstrated stronger business performance across the majority of key performance indicators.

Although some guardrail metrics increased slightly, the overall improvement in user conversion and engagement supports launching the new onboarding campaign.

Leadership should continue monitoring customer support requests, refund behavior, and long-term customer retention after rollout.

---

# Assumptions and Limitations

- The analysis is based on the provided experiment dataset.
- External business factors such as seasonality, competitor actions, and pricing changes were not considered.
- Statistical significance supports decision-making but does not eliminate all business risk.
- The experiment measures association within the experimental design and should be validated with ongoing monitoring after launch.
```

# Conclusion

The experiment indicates that the new onboarding experience improves user conversion and overall engagement while maintaining acceptable business performance across key guardrail metrics. Based on the analysis, the Treatment onboarding campaign is recommended for deployment with continued post-launch monitoring.
