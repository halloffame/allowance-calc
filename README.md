# Allowance Calculator

A fast, mobile-first web app for tracking kids' monthly allowance and savings interest. Optimized for iPhone.

## Live App

**[halloffame.github.io/allowance-calc](https://halloffame.github.io/allowance-calc)**

## How It Works

Enter three values, hit **Calculate**:

| Input | Description |
|-------|-------------|
| Current Balance | The child's current savings balance |
| Age | Their age in years |
| Amount to Keep | How much of the allowance they're holding on to (not depositing) |

The app returns a two-line ledger:

| | Deposit | Withdrawal | Balance |
|---|---|---|---|
| Starting Balance | — | — | $X.XX |
| Interest (5%/yr) | balance × 5% ÷ 12 | — | running total |
| Allowance | $1 × age | amount kept | **new balance** |

Hit **Clear for Next Kid** to reset for the next child.

## Adding to iPhone Home Screen

1. Open the app in **Safari**
2. Tap the **Share** button (box with arrow pointing up)
3. Tap **Add to Home Screen**
4. Tap **Add**

The app opens full-screen with no browser chrome, just like a native app. It also works offline after the first visit.

## Deployment

Hosted via **GitHub Pages** from the `main` branch. Any push to `main` automatically updates the live site.

## Interest Rate

Fixed at **5% annual**, applied monthly: `balance × 0.05 ÷ 12`
