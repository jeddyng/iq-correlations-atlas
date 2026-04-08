# IQ Correlations Atlas

**A comprehensive, interactive reference document cataloging 780+ empirical correlations, associations, and causal relationships with intelligence (IQ / g-factor).**

[**→ View the Live Atlas**](https://jeddyng.github.io/iq-correlations-atlas/)

---

## ⚠️ Important Disclaimers

**This project was built with AI assistance (Claude, Anthropic) and may contain hallucinated citations, inaccurate effect sizes, or misrepresented findings.** I built this as a personal research tool — not as a peer-reviewed academic resource. If you spot an error, please reach out.

**Correlation ≠ causation** unless explicitly noted. Effect sizes are approximate. Many findings are contested, have small samples, or have failed replication. The atlas includes contested and fringe findings alongside robust ones — tags and tooltips distinguish evidence quality.

**This document does not endorse any political, racial, or eugenic interpretation of intelligence research.** It is a catalog of what researchers have found, not a prescription for what those findings mean.

---

## What Is This?

I'm personally fascinated by data, psychometrics, and the question of what intelligence actually predicts in real life. I love seeing whether correlations, associations, and causal claims hold up when you look at the evidence — and whether they match lived experience.

This atlas started as a personal reference and grew into something much larger. It covers:

- **57 substantive sections** spanning cognitive style, personality, physical correlates, lifestyle, health, social behavior, politics, music, crime, financial behavior, romance, military, consumer behavior, management, food/drink, social dynamics, emotional intelligence, games, sports, university majors, childhood development, aging, creativity, humor, morality, fertility, occupational sorting, and more
- **780+ unique row entries** — each a documented correlation with intelligence
- **777 hover tooltips** — hover over any dotted-underline entry to see the source study, sample size, mechanism, and implications
- **Dark theme, responsive design** — built for reading and exploration
- **Pure HTML/CSS** — no JavaScript dependencies, no build tools, opens in any browser

## Data Sources

The atlas synthesizes findings from:

- **Academic journals**: PubMed, PMC, PsycINFO, PNAS, JPSP, Intelligence, Psychological Bulletin
- **Meta-analyses**: Stanek & Ones (2023, 60,690 relations), Onraet (2015, N>84K), Burgoyne (2016), Poropat (2009)
- **Longitudinal studies**: Dunedin Study (N=1,037, birth→age 52), Harvard Grant Study (85+ years), SMPY, Terman, NLSY
- **Military datasets**: ASVAB/AFQT, Scandinavian conscript data (Norway, Sweden, Finland, Denmark)
- **Large-scale surveys**: ClearerThinking.org (N=3,691, 40 claims tested), UK Biobank, GRE/SAT data
- **Cross-cultural sources**: German-language research (BIS model, DIW/SOEP), Japanese cognitive science, Brazilian university data
- **Public intellectuals**: Rob Henderson, Steve Stewart-Williams, Satoshi Kanazawa (Savanna-IQ hypothesis)
- **Informal/crowd-sourced**: Reddit, Twitter/X, Substack discussions

## How to Read It

| Element | Meaning |
|---------|---------|
| 🟢 Green bar (+) | Higher IQ associated with **more** of this trait |
| 🔴 Red bar (−) | Higher IQ associated with **less** of this trait |
| 🟡 Gold bar (~) | Mixed, nonlinear, or context-dependent |
| 🔵 Blue bar | Causal evidence (not just correlation) |
| 🟣 Purple bar | Qualitative / anecdotal |
| `STRONG` tag | Robust, well-replicated finding |
| `CONTESTED` tag | Debated or mixed evidence |
| `WEAK` tag | Anecdotal or small-sample |
| `CAUSAL` tag | Causal evidence (RCT, natural experiment, within-family design) |
| Dotted underline | **Hover for tooltip** with source citation and explanation |

## Highlighted Findings

Some of the most interesting entries:

- **IQ ↔ actively open-minded thinking: r=.43** — the strongest non-task personality correlate (ClearerThinking, N=3,691)
- **Walking speed at 45 predicted by IQ at age 3** — 12 IQ point gap between slowest and fastest walkers (Dunedin Study)
- **Spousal IQ correlation: r≈.40-.45** — you marry someone roughly as smart as your sibling
- **Harvard Grant Study (85 years): warm relationships > IQ for health at 80** — defense mechanisms mattered more than intelligence
- **Swearing fluency correlates with vocabulary size** — profanity is a verbal skill (Jay & Jay, 2015)
- **IQ ↔ perfectionism: r≈.00** — myth busted by ClearerThinking
- **Compassion correlates positively with IQ; politeness correlates negatively** — being kind ≠ being polite (Stanek & Ones, PNAS)

## Technical Details

- **Single HTML file** — ~350KB, no external dependencies
- **Pure CSS tooltips** — no JavaScript required
- **CSS custom properties** for theming (dark mode)
- **Fonts**: DM Sans + DM Mono (loaded from Google Fonts)
- **Responsive**: works on desktop, tablet, and mobile

For GitHub Pages, enable Pages in your repo settings pointing to the root directory. The HTML file should be named `index.html`.

## Version History

| Version | Lines | Sections | Tooltips | Key Additions |
|---------|-------|----------|----------|---------------|
| v3 | 1,725 | 21 | 0 | Original atlas |
| v4 | 3,403 | 57 | 777 | +36 sections, tooltip system, university majors, military, consumer, management, policy views, food/drink, social dynamics, emotional intelligence, romance, economics, games expansion, Dunedin Study, Harvard Grant Study, public intellectuals, crowd-sourced findings, Japanese cognitive science, PsyPost 2024-2025, Kaufman 45-dimension personality analysis |

## Contact

I'm Jedidiah — an SMU student interested in data, psychometrics, and systems thinking.

If you want the HTML file, have corrections, or want to discuss any of the findings:

## License

This is a personal research compilation. The underlying research belongs to its respective authors and publishers. This document is shared for educational purposes. If you are a researcher whose work is cited here and want a correction or removal, please contact me.
