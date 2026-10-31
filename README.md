# Prasanna R — Full Stack Developer Portfolio

A responsive split-layout portfolio built with React 18, Vite, React Bootstrap, Font Awesome, Framer Motion and plain CSS.

## Run locally

```bash
npm i
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

The production output is generated in `dist/` and can be deployed to Vercel as a Vite project. Build command: `npm run build`; output directory: `dist`.

## Included

- Split layout with a dark profile sidebar and light dashboard-style content area
- Responsive mobile layout and compact navigation
- Dark/light theme toggle saved in `localStorage`
- Intro, About, Featured Projects, Skills, Software Experience, Education and Contact sections
- Project category filters and scroll reveal animations
- Resume download from `public/Prasanna-R-Resume.docx`
- External links, email and telephone links

## Content notes

Content is based on the supplied resume. Only software-development employment is shown; earlier electrical employment is intentionally excluded. The electrical engineering education qualifications remain in the Education section because they are academic credentials, not employment history. The profile visual is an initials-based graphic placeholder rather than an invented personal photograph; replace it with an approved portrait if desired. Verify external project links and permission before publishing client work publicly.

## Tech

React, Vite, React Bootstrap, Bootstrap 5, Font Awesome, Framer Motion, plain CSS.

### Profile photo
The sidebar uses a lightweight initials-based profile graphic; no personal profile photo is included.


## V6 responsive and scroll fixes

- Removed automatic `scrollIntoView()` when the active navigation section changes. The page now moves only when a user clicks a navigation item or the Back to top control.
- Tablet widths (681px–1100px), including 1024px, use a full-width profile header and stacked dashboard columns.
- Mobile widths (up to 680px), including 475px, use a fluid single-column layout and horizontally scrollable navigation/filter rows.
- Added document-level overflow and minimum-height safeguards to prevent nested scroll containers from pulling the page position unexpectedly.
