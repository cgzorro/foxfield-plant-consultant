# Foxfield Plant Consultant — MVP v2.2 Release Candidate

Static GitHub Pages-ready prototype for the Foxfield Plant Consultant workflow.

## What is included

- Dark mode default + light mode
- English / Spanish UI toggle
- Homeowner / Consultant entry screen
- 8-step planning workflow
- ZIP + Project Address only for property lookup context
- Google Maps satellite reference iframe
- Google Maps directions link
- Front-door orientation selector, defaulting to Not selected
- Site intelligence summary
- 5-photo client-side preview limit
- Consultant Field Notes mode
- Separate Observed Conditions and Client Requests fields
- Dictation buttons for consultant notes fields using browser SpeechRecognition when supported
- Visit Checklist on the right side of Consultant Mode
- Copyable Discovery Brief text

## Current MVP limitations

This is a static prototype. GitHub Pages alone cannot save submissions, store uploaded photos, or generate PDFs server-side.

Planned next wiring:

1. Google Apps Script submission endpoint
2. Google Sheet lead log
3. PDF landscape discovery brief
4. USDA/geocode lookup
5. Stored photo links via Google Drive or Cloudinary

## Local test

Open `index.html` directly in Chrome or Edge.

Recommended quick QA before sharing:

- Choose Homeowner and confirm the 8-step flow progresses.
- Refresh and choose Consultant; open Consultant Notes.
- Confirm Visit Checklist appears on the right.
- Confirm dictation buttons are visible on Observed Conditions and Client Requests.
- Confirm Front Orientation starts as Not selected.
- Confirm Light/Dark toggle works.
- Confirm EN/ES toggle works.
- Confirm ZIP and Project Address are present; no City field.

## GitHub Pages setup

1. Create a new GitHub repository.
2. Upload `index.html` and this `README.md` to the root of the repository.
3. Commit the files.
4. Go to Settings → Pages.
5. Under Build and deployment, choose:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait 1–3 minutes for GitHub Pages to publish.
8. Open the Pages URL and run the QA list above.

