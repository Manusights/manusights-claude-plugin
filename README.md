# Manusights for Claude

Check a manuscript's references, look up a journal's AI-use rules, and preview a manuscript before
submission, from a conversation with Claude.

## Use it

- **Check references.** Paste a reference list or ask Claude to check the references in your draft.
  Manusights looks each one up in Crossref, the DOI registry and Retraction Watch, and, for references
  without a DOI, in Semantic Scholar, PubMed, arXiv, Open Library and CRAN. You see each status, the
  sources and the check time.
- **Journal AI rules.** Ask what a journal requires about AI use and disclosure. You get Manusights'
  dated record with a link to the official policy.
- **Manuscript preview.** With a free Manusights account, ask for a preview of your manuscript's full
  text: a readiness score, a verdict and the main risks a reviewer may raise. Figures are not reviewed
  from text.

Setup and example prompts: https://manusights.com/claude

## What this plugin contains

No code. It adds one skill (`skills/check-before-submission/SKILL.md`) and connects Claude to the
Manusights MCP server at `https://manusights.com/mcp` (`.mcp.json`). Reference checks and journal
lookups work without an account. Previews and earlier reviews ask you to sign in to Manusights.

## Data

Reference checks send only the references to manusights.com. A preview sends the manuscript text you
share and is saved to your Manusights account. Privacy policy: https://manusights.com/privacy.
Support: team@manusights.com.
