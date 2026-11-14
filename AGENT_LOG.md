# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```
## 2026-11-14: Add college-town and individual-sale browsing

- **Asked:** "For the website, can you allow the user to select a specific college town and look at individual entries and data?"
- **Agent produced:** Replaced the city summary table with a town selector, search field, paginated sale list, and full individual-record detail panel in `index.html`.
- **Checked or changed:** Read the data description before editing, kept `listing_id` as the record key, preserved identifier fields as text, and added HTML escaping for CSV values.
