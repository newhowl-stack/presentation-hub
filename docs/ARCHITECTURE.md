# Presentation Hub Architecture

## Objective

Host many HTML presentations in a stable, organized, shareable structure with project names, immutable versions, and a `latest` alias.

## Users

- Owner/editor: adds new decks and publishes versions.
- Collaborator/viewer: opens shared presentation URLs.

## System Boundaries

This is a static site. There is no application server, database, login system, or runtime API.

## Structure

```text
/
  index.html
  manifest.json
  projects/
    {project-slug}/
      manifest.json
      latest/
        index.html
      v1/
        index.html
```

## URL Pattern

- Hub: `/`
- Project latest: `/projects/{project-slug}/latest/`
- Project version: `/projects/{project-slug}/v1/`

## Versioning Rules

- Version folders are immutable after sharing.
- New edits should create `v2`, `v3`, etc.
- `latest` may be updated to match the current approved version.

## Integrations

- GitHub stores source and version history.
- Vercel or GitHub Pages serves the static site.

## Observability

For now, use host deployment logs only. Add analytics later only if needed and privacy-reviewed.
