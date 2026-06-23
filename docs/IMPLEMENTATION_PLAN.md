# Implementation Plan

## Phase 1: Static Hub

- Create hub folder.
- Add root index.
- Add root manifest.
- Add first project: `slidesite-pitch`.
- Add immutable `v1` and `latest` alias.

Acceptance: local file structure opens without a build step.

## Phase 2: GitHub Repository

- Create or choose a repository.
- Commit the hub contents.
- Protect `main` if collaborators will edit.

Acceptance: every change is versioned in Git.

## Phase 3: Hosting

- Connect the repository to Vercel or GitHub Pages.
- Set public or private access depending on audience.
- Share only hosted HTTPS URLs, never local `file://` URLs.

Acceptance: collaborators can open `/projects/slidesite-pitch/latest/`.

## Phase 4: Future Deck Workflow

- Add each deck under `projects/{project-slug}/v1/`.
- Update project and root manifests.
- Update `latest` only after review.

Acceptance: old version URLs never break.
