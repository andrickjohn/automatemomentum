# MOMENTUM ENGINE: Router & Budget Governor

## Routing Logic
- **Architecture & Design:** If task involves `SKILL.md` or UI -> Use `claude.md`.
- **Data & Deployment:** If task involves FTP, SiteGround, or Markdown -> Use `gemini.md`.
- **Planning:** If task is "How should we...?" -> Use `gemini.md` (Thinking Mode).

## Budget Guard
- **Daily Limit:** $20.00 USD.
- **Task Limit:** $2.50 USD.
- **Rule:** If current spend > $18, switch all models to "Flash" versions and notify John.