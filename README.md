# Biomarker Dashboard

An interactive public dashboard for exploring how familiar blood biomarkers shift across adulthood.

Live site:
[https://benshen94.github.io/biomarker_dashboard/](https://benshen94.github.io/biomarker_dashboard/)

## What this is

This project lets you explore population-level patterns in blood biomarkers across age using NHANES data. It is built for a broad audience interested in aging biology, longevity, medicine, and health data.

The dashboard focuses on questions people actually care about:
- Which markers rise with age?
- Which markers fall?
- Which become more variable?
- Where do female and male patterns diverge?
- How do selected disease groups differ from a healthy reference group?
- What does a published blood-based aging model estimate from routine lab values?

## What you can do in the dashboard

- Browse featured biomarker collections such as inflammation, metabolism, kidney function, blood and oxygen, and cardiovascular stress.
- Open a single biomarker and view its typical level, spread, tail shape, or female versus male pattern across age bins.
- Compare selected disease groups against the healthy reference population.
- Rank biomarkers by which ones change most with age.
- Explore a blood-age calculator based on a published model.
- Jump into a “What’s surprising?” view for patterns that are especially counterintuitive or shareable.

## How to read it

- The charts are cross-sectional. They compare different people at different ages, not the same people followed over time.
- Most age-trend views focus on adults from ages 20 to 84.
- Depending on the selected view, the dashboard may show raw summaries or trimmed summaries such as `5-95 trimmed` and `10-90 trimmed` to reduce the influence of extreme values.
- In `Both` mode, female and male trajectories are shown separately.

## What data this uses

The dashboard is based on public NHANES data and a curated blood biomarker subset prepared for this audience-facing explorer.

The main exploration is designed around a healthier reference cohort. In the dashboard, disease-specific views are separated into their own section so users can compare those groups against the healthy baseline more directly.

## Important caveats

- This is for education and research exploration.
- It is not medical advice.
- It is not a diagnostic tool.
- A biomarker trend in a population does not tell you what any one individual should do medically.
- Disease comparisons shown here are observational and cross-sectional.

## Blood age

The dashboard includes a blood-age calculator based on a published model often called PhenoAge. It is best understood as a way to compare a blood-marker pattern with the mortality-risk profile seen in the model’s reference population.

That result should be treated as an educational estimate, not a clinical diagnosis or a complete measure of aging.

## Repository note

This repository contains the built public site that is published with GitHub Pages. The source code and build pipeline live in a separate working repository.
