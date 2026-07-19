# NexoCargo AI Operations Copilot — Public Demo

This repository hosts the public, static judge demo for OpenAI Build Week 2026.

- Read-only
- Fictional data only
- Deterministic local fallback
- No API key
- No production connection
- No customer information

The private code repository supplied to the judges contains the PHP implementation, automated tests, privacy safeguards, and optional server-side GPT-5.6 Responses API integration.


## Product context shown in the demo

The public demo now includes a clear ecosystem section:

- **Pre-existing product:** NexoCargo Office
- **Pre-existing product:** NexoCargo Driver
- **Built during Build Week:** NexoCargo AI Operations Copilot

This distinction is intentional. Judges can interact with the Build Week extension on GitHub Pages, while the submitted video demonstrates the complete Office-to-Driver product workflow.

To enable the optional **Watch the full product demo** button, replace `href="#"` on the `fullDemoLink` anchor in `index.html` with the final YouTube URL.

## GitHub Pages

In repository **Settings → Pages**, choose **Deploy from a branch**, select `main`, choose `/(root)`, and save.

Expected demo URL:

`https://YOUR-GITHUB-USERNAME.github.io/nexocargo-ai-copilot-demo/`

## Interactive product workflow simulation

The public judge demo also includes a browser-only simulation of the pre-existing NexoCargo product workflow:

1. NexoCargo Office creates a fictional shipment.
2. The shipment is assigned to a fictional driver route.
3. NexoCargo Driver records a partial payment, demo signature, and pickup completion.
4. The simulated result synchronizes back to Office.

This guided mockup uses only in-memory JavaScript state. It has no login, backend, database, API, production connection, or personal information. The page clearly labels this workflow as pre-existing product context; the AI Operations Copilot remains the Build Week extension.
