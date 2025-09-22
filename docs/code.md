# Code & Workflows

Document the analyses, simulations, and visualizations you run during the
Innovation Summit. Link directly to files in the `code/` directory and describe
any required inputs or outputs so future contributors can reproduce the work.

## Quick reminders

- Keep runnable scripts and notebooks in [`code/`](https://github.com/cyverse-learning-institute/system-dynamics-early-warning-signals-innovation-summit-2025__8/tree/main/code).
- Store large datasets in the [CyVerse Group 8 folder](https://de.cyverse.org/data/ds/iplant/home/shared/esiil/Innovation_summit/Group_8) and reference paths here.
- Save generated figures or dashboards to `docs/assets/` (for small images) or
  upload to shared storage and embed screenshots.

## Workflows in progress

### System dynamics prototype
- **Location:** `code/system_dynamics_prototype.ipynb`
- **What it does:** Sketches stocks, flows, and feedbacks for a selected
  ecosystem and exports early warning indicators.
- **Inputs:** _Add dataset or parameter file references._
- **How to run:** `jupyter lab code/system_dynamics_prototype.ipynb`
- **Outputs:** _Link to figure or asset once available._

### Indicator sensitivity explorer
- **Location:** `code/indicator_sensitivity.py`
- **What it does:** Tests how candidate indicators respond to simulated shocks.
- **Inputs:** _Add file path or API reference._
- **How to run:** `python code/indicator_sensitivity.py`
- **Outputs:** _Add link to resulting plot or table._

Add new subsections as you create additional workflows. Keeping this page up to
date helps reviewers and future collaborators understand what’s ready to reuse.
