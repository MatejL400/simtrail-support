# SimTrail Support · GitHub Pages

Static English-language support website for SimTrail.

## Publishing

1. Create a **public** repository named `simtrail-support` under GitHub account `MatejL400`.
2. Upload **index.html**, **privacy.html**, **style.css**, and **.nojekyll** to the root of the `main` branch (not inside an extra folder).
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Once GitHub Pages has deployed, the two URLs should be:
   - Support: https://matejl400.github.io/simtrail-support/
   - Privacy: https://matejl400.github.io/simtrail-support/privacy.html

## Before submitting to Apple

**Important:** Verify privacy-policy claims against the production app implementation and App Store privacy answers. In particular, audit analytics/SDKs, location permissions, persistence, synchronization, account data, diagnostics, IP-address processing, and any server-side storage. Update `privacy.html` to precisely describe these before publication. The supplied policy is an initial draft, not a verified audit of the app.

The Contact Support action opens a **public GitHub issue** at the support repository. Ensure that Issues are enabled in the GitHub repository settings; if you prefer private assistance, replace the link with an active support email or private contact form.

Do not publish any sensitive data in repository files or public issue reports.
