# System Dynamics Early Warning Signals — Innovation Summit 2025 (Group 8)

Welcome to the public home for Innovation Summit 2025 Group 8. We are exploring
system dynamics approaches that can highlight early warning signals in complex
ecological and social-ecological systems. This repository powers both our public
website and the shared code base that documents the analyses we run during the
three-day sprint.

## Quick links

- **Live site:** https://cyverse-learning-institute.github.io/system-dynamics-early-warning-signals-innovation-summit-2025__8/
- **GitHub repository:** https://github.com/cyverse-learning-institute/system-dynamics-early-warning-signals-innovation-summit-2025__8
- **CyVerse team storage:** https://de.cyverse.org/data/ds/iplant/home/shared/esiil/Innovation_summit/Group_8

## Repository overview

| Location | Purpose |
| --- | --- |
| `code/` | Reusable scripts, notebooks, and analysis utilities. Include a brief header comment so teammates know how to run each item. |
| `docs/` | Markdown pages that power the MkDocs website. Editing these files updates the public site once the deployment workflow runs. |
| `documentation/` | Longer-form notes, brainstorms, or references that are not part of the public narrative. |
| `data/` (optional) | Small reference datasets for examples or figures (< 50 MB). Larger assets should live in CyVerse. |
| `outputs/` (optional) | Generated figures or reports that you want to version alongside the code. |

## Updating the website

The website is built with MkDocs using the Material theme. Every time you change
a file in `docs/`, the "Deploy site (MkDocs)" GitHub Action publishes the
updates to GitHub Pages.

1. Open the `docs/` folder in GitHub and choose the page you want to edit (for
   example, `index.md`).
2. Click the pencil icon (✏️), make your changes, and describe them in a short
   commit message such as `update homepage summary`.
3. Select **Commit changes**. The deployment workflow will rebuild the site in a
   couple of minutes.
4. Visit the live site (link above) and confirm the changes look correct.

> Tip: Upload images to `docs/assets/` and reference them in Markdown as
> `![caption](assets/filename.png)`.

## Sharing code and results

1. Add scripts and notebooks to the `code/` folder. Use clear filenames and
   include instructions in the file or in `docs/code.md` so others can rerun
   your work.
2. Place supporting datasets in team storage on CyVerse. Link to them from
   `docs/data.md` or within your notebooks rather than committing large files to
   GitHub.
3. Document the outputs you generate on the website—screenshots, static plots,
   small GIFs, or embedded dashboards keep the story visual.

## Turning on deployments (one-time)

If the repository was just created from the template, make sure GitHub Pages is
using GitHub Actions:

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. On the **Actions** tab, open **Deploy site (MkDocs)** and click **Run
   workflow** → branch `main`. The job builds the website and publishes it to
   Pages.

## First things to try

1. Update `docs/index.md` with your project one-liner, questions, and early
   visuals.
2. Add everyone to the team table on the homepage or in `docs/team.md`.
3. Commit your first analysis notebook to `code/` and summarize it on
   `docs/code.md`.
4. Confirm the site rebuilds successfully after your edits.

Questions? Open an issue or start a discussion in the repository so the whole
team can track decisions.
