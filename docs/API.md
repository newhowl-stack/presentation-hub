# API

No runtime API exists.

Static JSON files act as read-only data contracts:

## Root Manifest

Path: `/manifest.json`

Fields:

- `generatedAt`
- `projects[]`
- `projects[].slug`
- `projects[].name`
- `projects[].latestVersion`
- `projects[].latestUrl`
- `projects[].versions[]`

## Project Manifest

Path: `/projects/{project-slug}/manifest.json`

Fields:

- `slug`
- `name`
- `latestVersion`
- `versions[]`
- `versions[].version`
- `versions[].url`
- `versions[].status`
- `versions[].createdAt`
