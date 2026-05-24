# katchit-landing

Marketing landing page for Katch, deployed at https://getkatchapp.com.

## Stack

Plain static HTML + CSS. No build step. Netlify Forms for email capture.

## Files

- `index.html` — the landing page
- `thanks.html` — post-submit confirmation
- `styles.css` — all visual styling (paper / ink / honey / seal palette)
- `netlify.toml` — publish dir + security headers

## Deploys

Auto-deploy from `main` to the `katchit-landing-1779629258` Netlify site
(serves `getkatchapp.com`). Push and Netlify rebuilds.

## Form submissions

`name="early-access"` form, submissions visible at:
https://app.netlify.com/projects/katchit-landing-1779629258/forms

Add an email notification in the form settings to forward new signups.

## Related

- App (Next.js): https://github.com/NeoMeOfficial/catchit → https://app.getkatchapp.com
