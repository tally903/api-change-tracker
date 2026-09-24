# API change tracker

A small, refreshable record of dated, verifiable changes in the OpenAI API and Google Gemini API documentation.

This is a working snapshot, not a complete history. Each entry includes the source URL, capture date, provider, and a short description copied or closely paraphrased from the primary release notes. The tracker is intentionally separate from the operating-record repository, which contains public economics only.

## Data

`data/changes.json` contains the current snapshot. It is not a live feed.

## Refresh

1. Read the provider's primary changelog or release-notes page.
2. Add only dated entries that are new relative to the current snapshot.
3. Preserve the provider's wording where possible and link to the primary source.
4. Validate the JSON and record the capture date.
5. Commit the data and documentation together.

## Sources

- OpenAI API changelog: https://platform.openai.com/docs/changelog.md
- Google Gemini API release notes: https://ai.google.dev/gemini-api/docs/changelog

No item is marked as a breaking change unless the source explicitly says so.
