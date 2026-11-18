# Asset360 Strategic Scorecard

A screen-share-ready, mobile-responsive demonstration of the six-pillar Asset360 hotel investment decision process.

## What's inside

- One-click executive summary linking a six-pillar diagnostic to an investment decision.
- Six pillar views: **Physical Asset & CapEx**, **Operations & Team**, **Commercial & Positioning**, **Market & External Environment**, **Contracts & Capital Structure**, and **Valuation & Strategy**.
- Simulated operational, real estate, market, contractual and valuation evidence for a **fictional 500-room urban hotel**.
- Editable **asset health** and **opportunity gap** sliders (1–5) by pillar.
- On/off initiative selections and **conservative / base / upside** scenarios.
- Ranked initiatives, action ownership, leading KPIs, and a risk-adjusted NOI-to-value bridge.
- Presenter mode for screen sharing; print/PDF and CSV export.
- Local-only browser persistence. No libraries, external APIs or build step.

## Publish with GitHub Pages

1. Extract the ZIP. The files `index.html` and `README.md` should be visible.
2. Create a **Public** repository on GitHub named `asset360-strategic-scorecard`.
3. Upload **both** `index.html` and `README.md` into the **root** of the repository and click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main`, choose `/(root)`, then save.
5. Your site will appear at `https://YOUR-USERNAME.github.io/asset360-strategic-scorecard/` once GitHub Pages publishes it.

To update it later, replace `index.html` in the same repository and commit the change. You do not need another repository.

## Demonstration guidance

Start with **Executive overview**. Select a high-gap pillar (e.g., Commercial or Operations); review the sample operating signals, findings and initiative economics. Turn an initiative off, then return to **Executive overview** to see how the annual NOI and valuation bridge changes. Go to **Opportunity ranking** to show the proposed action plan. Use **Presenter mode** when screen sharing.

## Economics and limitations

The financial data, legal and financing details, company and property name are entirely fictitious. They do **not** represent any real hotel. The hypothetical baseline is 500 rooms, $61.2M revenue, $21.1M GOP and $15.4M EBITDA, with a constant 8.5% cap rate. The model calculates probability-weighted incremental NOI for selected projects and divides it by the cap rate, then deducts one-time project CapEx. Financing capacity and avoided downside are shown separately and are **not added to property value**. This screening tool is not a five-year DCF, verified appraisal, or investment recommendation. Project impacts may overlap; model them independently before underwriting a live transaction.

Data settings are saved locally in each browser. **Public GitHub Pages is not suitable for confidential operating, contractual or investment data**. Sharing the website URL does not share data saved locally on another device.
