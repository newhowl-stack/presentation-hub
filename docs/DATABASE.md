# Database

No database is used.

The source of truth is the Git repository plus static JSON manifests:

- `manifest.json` lists all projects.
- `projects/{project-slug}/manifest.json` lists versions for one project.

This keeps hosting simple, portable, cheap, and safe.
