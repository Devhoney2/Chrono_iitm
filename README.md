# ChronoAlpha

An interactive, point-in-time macro backtesting prototype created for a design-thinking course. The experience demonstrates how a quantitative researcher moves from a hypothesis to auditable evidence while preventing look-ahead bias.

## Prototype flow

1. Frame a falsifiable research question.
2. Define the data contract and release-time rules.
3. Align macro observations to their first tradable market bar.
4. Compose transparent strategy blocks.
5. Detect and repair look-ahead leakage.
6. Review performance and robustness before making a decision.

## Run locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Deploy to Vercel

### Import from GitHub

1. Create a GitHub repository and upload this folder.
2. In Vercel, select **Add New → Project**.
3. Import the GitHub repository.
4. Keep **Framework Preset: Next.js** and the default build settings.
5. Select **Deploy**.

### Using Vercel CLI

```bash
npm install
npx vercel
```

No environment variables, database or external API keys are required.

## What is interactive

- Research question and market selections
- Readiness and workflow progress
- Dataset validation and feedback
- Time-alignment animation
- Strategy-block selection
- Backtest loading state
- Bias detection and corrective action
- Results and robustness decision
- First-use guide, draft save and reset

## Important

This is a usability prototype. Backtest figures are illustrative and the application does not place real trades.
