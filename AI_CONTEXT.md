# Shared AI project context — The London Property Manager

Last updated: 2026-09-22

## Purpose
This repository is the shared source of truth for ChatGPT, Claude, Gemini and human collaborators working on the landlord-acquisition website for The London Property Manager.

## Primary business goal
Generate qualified enquiries from London landlords and property owners who may give the business their property to manage.

## Audience
- Prime and Central London landlords
- Overseas owners
- Property investors
- Letting agents / introducers

## Core offer
- Revenue-share / percentage property management
- Short and mid-term rental management
- Corporate and relocation demand strategy
- Property cleaning and presentation coordination
- Maintenance coordination
- Company-let or fixed-income discussions for suitable properties only

## Brand position
Premium, calm, credible and commercially competent. Avoid hype, get-rich-quick language and exaggerated earnings claims.

## Primary conversion
Free property assessment form on the homepage.

## Current technical architecture
- Domain registrar / DNS: GoDaddy
- Hosting: Netlify
- Source code: GitHub repository `consultagencypr-blip/cll`
- Production branch: `main`
- Static HTML/CSS/JS, no build step
- Form: Netlify Forms-compatible static form named `landlord-enquiry`

## SEO targets
Primary intent: London property management for landlords.
Secondary themes: short-let management London, Airbnb management London, corporate let management, mid-term rental management, serviced accommodation management and relevant London-area terms.

Do not create thin doorway pages. Location pages should contain genuinely useful, area-specific owner information before being published.

## Conversion principles
1. Clear outcome-led headline.
2. One primary CTA: free property assessment.
3. Property questions before contact details to build commitment.
4. Capture UTM attribution.
5. Avoid unverified numerical claims.
6. Use genuine testimonials and case studies only.
7. Mobile CTA should remain visible but not obstruct content.

## Known remaining tasks
- Connect this GitHub repo to the existing Netlify site for automatic deploys.
- Confirm Netlify detects the `landlord-enquiry` form.
- Configure form submission notifications and/or CRM delivery.
- Confirm legal company name, registered office, company number and privacy contact before adding statutory footer details.
- Add genuine landlord testimonials / case studies when approved.
- Add Search Console and analytics IDs when available.
- Add Meta/Google Ads tracking only with approved IDs and appropriate consent configuration.

## Change log
### 2026-09-22
- Created GitHub source of truth.
- Rebuilt homepage around landlord conversion intent.
- Added Netlify-compatible lead form, thank-you page and UTM capture.
- Added canonical metadata, Organization/Service structured data, robots.txt, sitemap.xml, favicon, manifest and security headers.
- Added shared AI context documentation.
