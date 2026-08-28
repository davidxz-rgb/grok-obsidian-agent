# Privacy Policy — Grok Obsidian Personal Agent

**Last updated:** 2026-08-28

This application is a **personal desktop agent** used only by the developer.  
It is not offered to the general public.

## What data is accessed

With explicit OAuth consent, the app may access:

- **Google Calendar (readonly)** — event titles, times, and locations for personal briefing and planning
- **Gmail (readonly)** — message metadata and content only when the user asks the agent to search or open a specific email
- **Local Obsidian vault** — markdown notes stored on the user’s computer (not uploaded to Google)

## How data is used

- Data is used only to generate personal notes, briefings, and summaries on the user’s machine.
- Data is **not sold**, rented, or shared with advertisers or third parties.
- Data is **not** used to train public AI models by this app’s Google connection (Google APIs are used only as authorized).

## How data is stored

- Google OAuth tokens are stored **locally** on the user’s PC (e.g. `google_token.json`).
- API keys and secrets are stored in local environment files (e.g. `.env`), not in this repository’s public docs.
- Calendar/email content may be summarized into local Obsidian notes when the user requests it.

## Sharing

This app does not provide a multi-user cloud service.  
OAuth client secrets and tokens must not be shared.

## Retention and deletion

- Local tokens can be deleted by removing `google_token.json`.
- Access can be revoked anytime in [Google Account → Security → Third-party access](https://myaccount.google.com/permissions).
- Local Obsidian notes remain under the user’s control.

## Contact

Use the developer / support email configured on the Google Cloud OAuth consent screen for this project.
