# Writers Association Concept

An original, 20-page literary association portfolio concept by Bklyn Custom Designs®. Black, African American, and Caribbean stories sit at the center of a wider, diverse writing community. All writers, books, history, events, grants, and membership opportunities are fictional.

## Publish on GitHub Pages

1. Download and extract the ZIP. Open the `writers-guild` folder.
2. On GitHub, select **New repository**. Suggested name: `writers-association-concept`. Choose **Public**, add a README if desired, and create the repository.
3. Choose **Add file → Upload files**. Upload the **contents** of `writers-guild`, keeping the complete `assets` folder. `index.html` must be at the repository root, beside `assets`, rather than inside an extra `writers-guild` folder. Uploading the ZIP itself does not publish the site.
4. Commit the upload to `main`.
5. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)`, then **Save**.
6. When deployment completes, visit `https://YOUR-USERNAME.github.io/writers-association-concept/`.

All navigation and image paths are relative so the project works at a GitHub Pages repository URL. No npm installation, build step, API key, or paid service is required. GitHub's upload interface may hide `.nojekyll`; this plain HTML project also works without it. The project has no custom-domain configuration.

## Local preview

Open `index.html` directly, or run `python3 -m http.server 8000` inside this folder and open `http://localhost:8000`. The latter more closely matches hosting behavior. No backend is required.

## Included experiences

- Responsive homepage with original editorial studio imagery and a timezone-aware anniversary countdown to November 16, 2026, 6:30 PM Eastern.
- Sixteen fictional authors, sixteen individual profile views through `author.html?id=…`, eleven regional circles, six book artworks and original reading excerpts.
- Events directory, category filters, invitation dialogs, and five downloadable `.ics` calendar invitations marked FICTIONAL DEMO and TENTATIVE.
- WRITE-OFF writing room: rotating prompts, short-story/poem choice, word count, ten-minute sprint with pause/reset, and one audience-applause selection per visit.
- New-writer and established-author workshops, webinars, fictional grant overviews, and institutional partnership content.
- Six original journal essays; association story and an explicitly fictional thirty-year timeline.
- Newsletter, membership-interest, partnership, and RSVP previews with required fields, consent, validation, and clear feedback. They do not send or store personal information.
- Member dashboard preview without credentials, authentication, or password collection.
- Keyboard navigation, visible focus, skip link, reduced-motion support, native dialogs, and mobile menu.

## Working name

The proposed “Top Writers Guild Association” has **not been legally cleared**. The public concept currently uses the neutral descriptive heading “Writers Association Concept.” See `NAME-REVIEW.md` for preliminary research, its limitations, and the remaining checks. This descriptive heading is also not presented as a cleared trademark. Replace the brand only after confirming a suitable name.

## Edit the site

- `assets/styles.css`: colors, typography, layouts and responsive behavior.
- `assets/app.js`: interactions, forms, countdown and writing-room behavior.
- `assets/data.js`: fictional author, book and event data.
- HTML files: page content and shared header/footer. They are deliberately plain HTML; shared elements must be edited across pages.
- Portrait sheet: a 4 × 4 grid; each portrait uses CSS position variables `--x` / `--y`.
- Cover sheet: a 3 × 2 grid; each cover uses `--bx` / `--by`.

The directory cards and book pages are pre-rendered for readability without JavaScript. If changing data, also update matching HTML cards, excerpts, event details and calendar files. The countdown target is in `index.html` as an ISO timestamp; preserve the correct timezone offset when editing it. When the target passes it shows zero and a date-arrival message.

## Live-service integration

GitHub Pages hosts static files. Before using this design for a real organization, connect forms to an appropriate consent-aware service, add actual member authentication through a secure provider, verify grants/events/claims, establish applicable policies, and clear the name. No functional mailing list, real RSVP database, membership system, stored writing, official voting system, payment system or grant application is included in this concept. Writing and selections disappear on reload. Do not paste irreplaceable work into the preview writing room.

## Originality and assets

The Center for Black Literature website was viewed only for broad inspiration around literary community, programming, archives, and public engagement. Its wording, people, photographs, logos, code, branded programs, and layout were not copied. Original concept copy and AI-generated editorial imagery were created for this project. See `CREDITS.md` and `LICENSE.txt`.

## Revised visual direction

Navy blue `#112448`, green `#246c49`, crimson `#a71938`, black `#0d0e10`, and yellow accent `#ffe05c`. The editorial hero and portrait grid were regenerated to strongly vary facial structure, ages, expressions and hairstyles. The first two featured women have long locs and a close-cropped natural cut, with visibly distinct facial identities. Original book-cover artworks retain their individual cover designs.
