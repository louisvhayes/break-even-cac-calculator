# Subscription Economics Calculator

An interactive, single-file HTML dashboard for subscription economics, based on the supplied **Subscription Economics Calculator (soft dark)**.

## Features

- Constant and changing monthly churn models
- Churn-before-payment and payment-before-churn timing
- Initial users, subscription fraction, price, contribution margin, CAC, and one-off implementation cost
- Expected payers, payments, revenue, contribution, LTV, and net project value
- First-T-payment calculations and a payment-by-payment breakdown for variable churn
- Starred metrics, copyable results, and a custom on-screen numeric keyboard

## Run locally

Open `index.html` directly in any modern browser. No build step or dependencies are necessary.

## Publish using GitHub Pages

Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

Once GitHub Pages finishes deployment, the intended URL is:

https://louisvhayes.github.io/break-even-cac-calculator/

## Assumptions

Refer to the assumptions inside the calculator. It models undiscounted cash flows and differs by selected churn/payment timing. CAC is entered per initial user; the fixed one-off implementation cost is deducted once. For changing churn, a finite payment horizon is used.

The calculator is a learning aid for evaluating subscription economics.
