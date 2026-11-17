# MINTFORGE AI — prototype

Premium static front-end prototype for a US-first financial opportunity discovery and portfolio intelligence platform.

## Included
- Responsive dark/emerald landing page and dashboard preview
- Opportunity discovery categories and portfolio layout
- Pricing: $19.99 monthly, $191.90 annual (20% off), $179.91/year equivalent for multi-year (25% off)
- Clear prototype labels and financial/legal disclaimers
- No real authentication, bank connections, live market data, payments, trading, or account-opening actions

## Deploy to Render
This is a static site. Publish the contents of this repository root with:
- Build command: `echo "Static site — no build required"`
- Publish directory: `.`

## Production work still required
1. Deploy the static frontend to a new Render service in the existing Calibration workspace.
2. Add backend API, Postgres, background worker and scheduled source checks.
3. Implement secure email/Google authentication, MFA and account isolation.
4. Integrate a regulated bank-account provider and read-only exchange connections first.
5. Add provider-specific consent, compliance, eligibility and jurisdiction checks.
6. Add Stripe subscriptions after account setup and review.
7. Do not enable trading or money movement until legal, security and risk controls are approved.

Never collect users' bank/exchange passwords or bypass CAPTCHA, KYC, MFA, or platform safeguards.
