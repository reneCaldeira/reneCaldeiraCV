# System Memory: reneCaldeiraCV

## Model Performance Metrics & Error Tracking
- GPT-5.6 Luna Errors: 1 (MCP timeout during initial redesign)
- GPT-5.6 Terra Errors: 2 (Initial timeouts in earlier session; Terra Low succeeded on mobile responsiveness task with 0 errors)
- GPT-5.6 Sol Errors: 1 (Timeout > 180s on PoYo gateway during high-effort prompt)
- Gemini Fallback Fixes: 1 (Final Fallback triggered per Escalation Ladder)
- Recent Delegation: GPT-5.6 Terra Low (`poyo_terra_low`) successfully generated responsive media query recommendations. Verified and enhanced by Gemini.

## Resolved Bugs & System State
- Bug Resolved (Mobile Stacking & Overflow):
  - Fixed 800px desktop sidebar stacking above hero on mobile viewports (<860px). Transformed into a compact 72px avatar + identity header and a horizontal scrollable chip nav bar.
  - Fixed hero action buttons and role pills wrapping / horizontal overflow on screens 360px–430px.
  - Fixed `.data-matrix` table squeezing on mobile: converted to architectural card ledger rows with cadmium copper accents.
  - Fixed `.contact-table` email overflow by stacking labels and values with `word-break: break-all`.
  - Fixed top classification bar text collision on narrow screens (<520px) by hiding the third column.
- Live Deployment: Synced and deployed to `https://renecaldeira.com.br/` via `ROC-namecheap` FTPS.
- Repository: Clean and pushed to `https://github.com/reneCaldeira/reneCaldeiraCV.git` on branch `main`.
