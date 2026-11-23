# CineLocal Support & Marketing Site

Public support repository for the [CineLocal](https://github.com/highscorejimmy/CineLocal) iOS app. Hosted on GitHub Pages from the `main` branch, site root.

## Live Site

**https://highscorejimmy.github.io/CineLocal-Support/**

A pull request does not change the live site. GitHub Pages rebuilds from `main` after the pull request is merged.

## App Store Connect URLs

| Field | URL |
|-------|-----|
| Marketing URL | `https://highscorejimmy.github.io/CineLocal-Support/` |
| Support URL | `https://highscorejimmy.github.io/CineLocal-Support/support.html` |
| Privacy Policy URL | `https://highscorejimmy.github.io/CineLocal-Support/privacy.html` |

## Pages

- `index.html` — Landing page
- `support.html` — FAQs and troubleshooting
- `privacy.html` — Privacy policy for CineLocal 2.8 (build 13)
- `app-privacy.html` — What that version sends, and what its privacy manifest says

Version 2.8 does not include an advertising SDK, an App Tracking Transparency prompt, or use of the advertising identifier.

## Local Preview

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Updating

Edit the HTML and CSS, commit, and merge to `main`. GitHub Pages republishes the root of `main`.
