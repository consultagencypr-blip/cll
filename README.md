# The London Property Manager website

Production domain: https://thelondonpropertymanager.com

This repository is the **single source of truth** for the landlord-facing website.

## Deployment
The intended production workflow is:

1. Changes are committed to the `main` branch.
2. Netlify is connected to this repository.
3. Netlify automatically deploys every successful commit to `main`.
4. The custom domain stays managed in GoDaddy DNS and points to Netlify.

Netlify settings should use:
- Repository: `consultagencypr-blip/cll`
- Production branch: `main`
- Build command: leave blank
- Publish directory: `.`

## Lead form
The homepage contains a Netlify-compatible form named `landlord-enquiry`.
Submissions redirect to `/thank-you.html` and capture UTM attribution fields.

After Git-based deployment is connected, confirm in Netlify > Forms that `landlord-enquiry` is detected, then configure an email notification or CRM integration.

## AI collaboration
Read `AI_CONTEXT.md` before making changes. Claude, Gemini, ChatGPT or any coding agent should update that file when a material business, architecture, analytics or conversion decision changes.

## Safety
Never commit passwords, API keys, DNS credentials, booking data, guest data or landlord personal data to this repository.
