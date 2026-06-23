# Deployment

## Recommended

Use a GitHub repository connected to Vercel.

Why:

- Automatic preview deployments for branches.
- Stable production URL from `main`.
- Easy rollback through Git and Vercel deployment history.
- No server to maintain.

## Alternative

Use GitHub Pages if a simple public static site is enough.

## Publish Checklist

- Confirm no private/client-sensitive material is included.
- Confirm the target version folder is immutable.
- Update root and project manifests.
- Open the hosted URL and review every slide.
- Share the HTTPS URL.
