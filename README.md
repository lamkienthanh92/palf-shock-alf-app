# Pediatric acute liver failure during shock: companion tool

Interactive companion to the article *"Circulatory and excretory failure, not necrosis, are linked to death in shock-associated pediatric acute liver failure"* ([AUTHORS], [JOURNAL], [YEAR]).

**Live version:** https://[NETLIFY-SITE-NAME].netlify.app/
**Archived version (cite this):** https://doi.org/[ZENODO-DOI]

## What it does
- Calculates standard scores (pSOFA, PELOD-2, VIS, PELD/MELD, LIU, King's College criteria).
- Places a patient on the four pathophysiological axes derived in the cohort.
- Shows the in silico bilirubin production–clearance model, the within-patient temporal sequence and transaminase kinetics.

## Data
The tool contains only aggregated statistics from 112 children (medians, quartiles, model coefficients, axis loadings and bootstrap parameter sets). It contains no individual patient data. Values entered by users are processed in the browser and are not stored or transmitted.

## Intended use
For research and teaching only. Not a medical device, not externally validated, and not intended for clinical decision-making.

## Technical
A single self-contained HTML file. React 18 is loaded from the jsDelivr CDN at pinned versions; no build step or server is needed. Hosted on Netlify (`netlify.toml` publishes the repository root) and archived on Zenodo through GitHub releases (`.zenodo.json`).

## How to cite
See `CITATION.cff`, or use the Zenodo DOI above.

## License
Code: MIT (see `LICENSE`). Text and aggregated data: CC BY 4.0.
