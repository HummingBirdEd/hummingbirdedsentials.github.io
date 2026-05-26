# HummingBird Edsentials Website Change Report

Date: 2026-05-26

## Summary

The site was upgraded from a small static placeholder into a professional booking-focused website for LaNiqua McCloud and HummingBird Edsentials. The new structure is designed to help schools, organizations, conferences, and family groups understand the offer quickly and take action through Calendly.

## Changed Files

- `index.html`
- `about.html`
- `services/index.html`
- `assets/css/style.css`

## New Files

- `speaking/index.html`
- `media-kit/index.html`
- `assets/downloads/laniqua-mccloud-speaker-one-sheet.html`
- `assets/downloads/laniqua-mccloud-speaker-one-sheet.md`
- `reports/website-change-report.md`

## Backup Files

Original source files were copied before edits:

- `backup/original-index.html`
- `backup/original-services-index.html`
- `backup/original-style.css`
- `backup/original-about.html`, if present at the time of backup

## Main Improvements

- Added professional homepage hero with clear positioning and booking calls to action.
- Added sticky navigation across the site.
- Added audience paths for schools, organizations, and families.
- Added proof section with credentials, past recognition, and testimonial.
- Added service pricing and clear bookable formats.
- Added dedicated Speaking page.
- Added Media Kit page.
- Added About page copy.
- Added downloadable speaker one-sheet in HTML and Markdown formats.
- Added responsive CSS for mobile and desktop.
- Added print-friendly behavior for one-sheet/media content.
- Replaced invalid nested HTML and logo placement in the original homepage.
- Kept the existing logo and headshot assets.

## Booking Links Used

- Calendly: `https://calendly.com/hummingbirdedsentials`
- Book: `https://www.amazon.com/dp/B0D9DZ9Z6B`

## Deployment Notes

This is a GitHub Pages static site. Publishing requires committing and pushing these changes to:

`HummingBirdEd/hummingbirdedsentials.github.io`

After GitHub Pages rebuilds, verify:

- Homepage loads at `http://hummingbirdedsentials.com`
- Navigation links work
- Calendly links open in a new tab
- Book link opens Amazon
- Speaker one-sheet download page loads
- Mobile layout is readable

