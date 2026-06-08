# Myer Wang Apps

This repository hosts public app information pages for apps created by Myer Wang.

It is intended for GitHub Pages publication and for app store metadata URLs,
including:

- App showcase pages
- Privacy Policy pages
- Support pages
- Terms pages

## Structure

Each app gets its own directory at the repository root:

```text
app-slug/
  index.html
  privacy/
    index.html
  support/
    index.html
  terms/
    index.html
```

The root `index.html` lists all published apps. Store submissions should use
the per-app URLs, for example:

```text
https://myerwang.github.io/apps/lazywords/privacy/
https://myerwang.github.io/apps/lazywords/support/
https://myerwang.github.io/apps/lazywords/terms/
```

## Adding A New App

1. Create a new lowercase app slug directory, for example `new-app/`.
2. Add `index.html`, `privacy/index.html`, `support/index.html`, and
   `terms/index.html`.
3. Add the app to the root `index.html`.
4. Keep each policy page specific to the actual app behavior at release time.

## Review Notes

- All pages must be public HTTPS pages.
- Pages must not require GitHub login.
- Privacy Policy content must match App Store Connect and Google Play data
  disclosure answers.
- Update the relevant app pages whenever analytics, crash reporting, payments,
  accounts, cloud sync, ads, or third-party SDKs are added.
