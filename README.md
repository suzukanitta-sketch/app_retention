# app_retention

Feature Impact Analysis: Retention &amp; Experimentation in a Health-Tech Context

Decision:
Roll out to new users only; hold full rollout pending causal validation.


Problem

Evaluate the impact of a new feature on 30-day user retention and determine whether it should be rolled out, accounting for potential tradeoffs across user segments.


Summary

Recommended a segmented rollout targeting new users, where the feature increased 30-day retention by ~10 percentage points (p < 0.05).

No statistically significant improvement was observed for returning users, suggesting potential heterogeneity in feature impact and the need for controlled rollout.

Approach

Defined primary metric (30-day retention) and guardrails (engagement)

Simulated A/B test framework with treatment/control groups

Estimated effect size, confidence intervals, and statistical significance

Performed segmentation analysis (new vs returning, activity levels)

Evaluated tradeoffs and made product recommendation

Limitations & Causal Considerations

This analysis assumes randomized assignment between treatment and control groups. In real-world settings, feature exposure is often non-random and may introduce selection bias if certain users are more likely to receive the feature.

Additionally, user behavior may be influenced by confounding factors such as geography, device type, or baseline engagement.

In such cases, causal inference techniques (e.g., propensity score weighting) would be required to obtain unbiased estimates of feature impact.
