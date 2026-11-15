# Zalopay Underwriting Case

Working report for a synthetic CASHLOAN take-home case.

## Review

Download `index.html` and open it in Microsoft Edge or Google Chrome. The report works offline and includes an embedded A/B funnel explorer. GitHub displays HTML source; it does not render this file as a website.

The report covers data audit, normalization, input risk profile, acquisition cohort checks, complete submission reasons, converted turnaround times, pending approvals, H2/H3/H4, retrospective portfolio limits, and conditional actions.

Activity period: January-April 2026. Repayment-label snapshot: 15 June 2026. The HTML explorer contains only daily aggregate counts. Original synthetic CSVs are also included separately under `data/`; no credentials or notebook outputs are included.

H2 is the primary acquisition finding. Operational incidents and label maturity remain unconfirmed without the missing logs and eligibility definitions. This report does not claim causal effects or loan losses.

External research links require internet only when explicitly opened. No hosting/deployment or GitHub Pages is enabled by this repository.


## Original synthetic datasets

- [funnel_dod.csv](data/funnel_dod.csv): original funnel event log, 335,612 rows.
- [labels_dpd30_mob1.csv](data/labels_dpd30_mob1.csv): original repayment snapshot, 7,491 rows.

Both CSVs are preserved byte-for-byte. Identifiers and partners are synthetic, as described in the assignment brief. Label extraction date is 2026-06-15; activity ends in April 2026. Label coverage does not certify maturity.
