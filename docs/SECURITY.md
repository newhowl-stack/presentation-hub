# Security

## Privacy

The default `vercel.json` sends `X-Robots-Tag: noindex` to discourage indexing. This is not access control.

For confidential decks, use one of:

- Vercel password protection or team-only access.
- A private repo with authenticated preview links.
- A separate access-controlled app if sensitive data is involved.

## Secrets

Do not put API keys, client credentials, or private tokens in HTML files, manifests, or deployment config.

## Stability

Do not overwrite shared version folders. Create a new version instead.

## Review

Before publishing:

- Search the deck for secrets or private notes.
- Open every slide in a browser.
- Confirm links and embedded assets work.
