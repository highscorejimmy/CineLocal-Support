# CineLocal Support & Marketing Site

Public support repository for the [CineLocal](https://github.com/highscorejimmy/CineLocal) iOS app. Hosted on GitHub Pages.

## Live Site

**https://highscorejimmy.github.io/CineLocal-Support/**

## App Store Connect URLs

Use these when submitting to Apple:

| Field | URL |
|-------|-----|
| Marketing URL | `https://highscorejimmy.github.io/CineLocal-Support/` |
| Support URL | `https://highscorejimmy.github.io/CineLocal-Support/support.html` |
| Privacy Policy URL | `https://highscorejimmy.github.io/CineLocal-Support/privacy.html` |

## Pages

- `index.html` — Marketing landing page
- `support.html` — FAQs, troubleshooting, contact
- `privacy.html` — Privacy policy (required by App Store)
- `app-privacy.html` — **App Store Connect App Privacy guide** (tracking / AdMob / ATT compliance)

## App Review — NSUserTrackingUsageDescription

If App Review rejects the build because `NSUserTrackingUsageDescription` is present:

1. Open [app-privacy.html](app-privacy.html) on the live site
2. Follow **Option A** to update App Privacy in App Store Connect (no new build required), or **Option B** to remove tracking from the app binary
3. Resubmit for review

The free version uses Google AdMob and may request Apple's App Tracking Transparency permission for personalized ads. CineLocal+ removes ads.

## Local Preview

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Updating

Edit the HTML/CSS files, commit, and push to `main`. GitHub Pages will redeploy automatically.