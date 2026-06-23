# Publishing, Plain English

This folder is ready to become a small website.

## What You Will Get

Once connected to hosting, you will have URLs like:

- `https://your-site.com/`
- `https://your-site.com/projects/slidesite-pitch/latest/`
- `https://your-site.com/projects/slidesite-pitch/v1/`

## What I Need From You To Finish The Internet Part

Choose one:

1. Give me a GitHub repository that Codex can access.
2. Connect/install the Codex GitHub app to a repository you want to use.
3. Give me Vercel access/token in this environment.

After that, I can publish the hub and give you the shareable HTTPS link.

## Recommended Setup

Use one GitHub repository called something like:

`presentation-hub`

Connect that repository to Vercel.

Then every future presentation gets added as:

`projects/{project-name}/v1/index.html`

When a deck changes, create:

`projects/{project-name}/v2/index.html`

The `latest` folder always contains the approved current version.
