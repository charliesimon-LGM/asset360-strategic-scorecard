# Asset360 Strategic Scorecard — Investment Decision Dashboard (v2)

A standalone mobile-friendly, screen-share-ready site for a **fully synthetic** 500-key hotel. This version starts with owner investment economics: **capital required, stabilized incremental NOI, terminal asset-value uplift and five-year incremental unlevered IRR**.

## What changed in v2

- Executive overview now opens with an investment recommendation and a four-number underwriting summary.
- Removed the average 1–5 opportunity-gap rating from the executive overview. Pillar scoring remains available in the diagnostic pages but does not determine dollars or IRR.
- Removed the two-floor renovation pilot. The sample now evaluates a unified 500-room guestroom renovation with capital, rate benefit, displacement and procurement underwritten on a whole-property basis.
- Capital/NOI contribution by all six pillars is visible on the executive screen; non-NOI financing and defensive items are excluded from incremental value.
- The Opportunity Ranking section now shows annual NOI, CapEx, five-year cash flow and IRR.

## Investment math (USD millions)

Selected recurring NOI initiatives have assumptions for full-potential NOI, a realization factor, and up-front CapEx. In each scenario, the underwritten stabilized NOI is the sum of `(potential NOI × realization factor × scenario multiplier)`. All selected program CapEx is included at Year 0 as a conservative timing simplification. NOI ramps 30% / 70% / 100% / 100% / 100% in Years 1–5. At the end of Year 5, the model adds terminal value equal to stabilized incremental NOI divided by an 8.50% assumed exit capitalization rate. The incremental unlevered IRR is the discount rate that sets the NPV of these six net cash flows to zero. Terminal value is *not* counted twice in IRR.

`Indicative net value creation = terminal value uplift – selected CapEx` is displayed separately from IRR and does not include interim cash flow. Underwriting excludes financing, taxes, transaction costs and changes in the base property's valuation. Actual development timing, return thresholds, displacement, execution overlap, management/franchise fees and valuation sensitivities require further diligence.

## Publishing on GitHub Pages

1. Create a public GitHub repository `asset360-strategic-scorecard`.
2. Upload **both** `index.html` and `README.md` into the repository's top-level folder.
3. Go to **Settings → Pages** and choose **Deploy from a branch**, `main`, `/(root)`, then **Save**.
4. Open `https://YOUR-USERNAME.github.io/asset360-strategic-scorecard/`.

GitHub Pages is public. Do not enter proprietary financial information. Browser selections are saved locally on the device and do not sync between devices.
