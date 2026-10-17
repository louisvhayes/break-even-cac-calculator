# Break-even CAC Calculator

A standalone, responsive calculator for subscription businesses. Enter price, contribution margin, monthly paid churn, CAC, and a one-off campaign setup cost to calculate the minimum **whole number of paying subscribers** required to break even.

## Run locally
Open `index.html` in your browser. No dependencies, API keys, tracking, or build step required.

## Publish with GitHub Pages
1. In repository **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
2. Once deployment finishes, the calculator will be available at https://louisvhayes.github.io/break-even-cac-calculator/

## Model
- Contribution LTV = monthly price × contribution margin / monthly paid churn.
- Incremental contribution per customer = contribution LTV − CAC.
- Break-even subscriber count = round up(fixed setup cost / incremental contribution per customer).

Assumptions: month-start payments; churn after payment; constant price, churn, and margin; undiscounted cash flows; fixed cost additional to per-subscriber CAC. If contribution LTV is at or below CAC, a campaign with positive fixed setup costs cannot break even within this model.

This tool is intended for education, not financial advice.
