# CRONN Project Tracker v1.0 • HTML edition

A responsive, single-file CRONN project tracker with the original dark, turquoise, metallic interface.

## Files
- **`index.html`**: Working, empty project tracker. No demonstration projects are preloaded. Create a project, select photos from your phone gallery or desktop, set dates/captions, track tasks and milestones, and export reports.
- **`demo/index.html`**: Exact first interactive CRONN v1.0 preview preserved for comparison, including the original sample project.

## Start on Android or desktop

Once GitHub Pages is enabled with **Deploy from a branch → main → /(root)**, the live app address will be `https://dgcdxn.github.io/CRONN-HTML-App/` and the demo will be `https://dgcdxn.github.io/CRONN-HTML-App/demo/`.
Download the working `index.html` from this folder and open it in a current browser (Chrome or Edge). If you host it on HTTPS, you can access the same website from phone and desktop, but project data will **not** automatically synchronize.

## Photo evidence
Select a project → Photos → **Add photos from gallery**. Choose one or several images, add an optional caption and date, and save. Each photo can be edited or deleted. If you don't specify a date, the app uses the image file's last-modified date, which may differ from its original camera capture date.

## Privacy and backups
There is no backend, cloud database, or live sync. Real projects, photos, and progress are saved **locally in that browser on that device**, using browser storage. They are **not** uploaded to GitHub. A repository clone or another phone will not contain your records.

Use **Settings → Export project backup (JSON)** frequently. To migrate between devices, use **Settings → Import backup (JSON)** on the destination browser. Clearing site/browser data, private browsing, unsupported `file://` storage, or a browser storage limit may cause loss. Consider HTTPS hosting for dependable browser storage.

## Reports
Reports can be exported as HTML and PDF. External reports omit CRONN branding. For best evidence archiving, also keep regular JSON backups containing all photo attachments.

## Repository separation
This public repository holds the HTML version only. The Android project and its workflow remain in the original private `CRONN-Company` repository.
