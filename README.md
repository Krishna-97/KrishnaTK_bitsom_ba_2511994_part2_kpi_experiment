# Krishna-T-K_bitsom_ba_2511994-_part2_kpi_experiment
# KPI Framework, Business Experiment Analysis & Decision Recommendation

## Business Context

A subscription-based digital product company conducted an A/B experiment to evaluate a redesigned onboarding campaign.

Users were randomly assigned to either:

* Control Group
* Treatment Group

The objective was to determine whether the Treatment onboarding experience should replace the current onboarding process.

---

## Dataset Summary

Total Users: **1,408**

Control Group: **693**

Treatment Group: **715**

The dataset contains:

* User information
* Experiment group
* Region
* Device Type
* Traffic Source
* Plan Type
* Landing Page Visit
* Trial Start
* Onboarding Completion
* Paid Conversion
* Revenue
* Refund Request
* Support Tickets
* Days to Convert
* Engagement Score

---

## North Star Metric

Paid Conversion Rate

Control

3.18%

Treatment

6.99%

---

## KPI Tree Summary

North Star Metric

Paid Conversion Rate

Primary Drivers

* Landing Page Visits
* Trial Starts
* Onboarding Completion

Supporting Drivers

* Region
* Device Type
* Traffic Source
* Plan Type

Guardrail Metrics

* Refund Rate
* Support Ticket Rate
* Revenue per User
* Engagement Score
* Days to Convert

---

## Data Quality Checks

Completed:

* Missing Value Analysis
* Duplicate User IDs
* Binary Value Validation
* Revenue Outlier Detection
* Group Count Validation
* Segment Distribution Analysis

---

## Hypothesis Test Summary

Method

Chi-Square Test of Independence

P-value

0.001146479

Decision

Reject the Null Hypothesis

Interpretation

The Treatment significantly improves Paid Conversion Rate.

---

## Guardrail Metrics

Revenue per User

52.83

Support Tickets

Reviewed

Refund Requests

Reviewed

Engagement Score

Reviewed

---

## Final Recommendation

Launch the new onboarding campaign.

The Treatment achieved significantly higher Paid Conversion while maintaining acceptable business performance.

---

## Assumptions and Limitations

* Short-term experiment only.
* Long-term retention unavailable.
* Revenue limited to the first 30 days.

---

## Screenshots Included

* summary_metrics.png
* hypothesis_test_output.png
* kpi_tree_preview.png
