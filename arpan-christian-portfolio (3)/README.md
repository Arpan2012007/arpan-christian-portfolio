# Arpan Christian — Portfolio

A dark-themed, responsive personal portfolio built with plain HTML5, CSS3 and
vanilla JavaScript (no frameworks, no Google Fonts).

## Folder structure
```
/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── images/     ← put project screenshots here
    ├── icons/      ← optional extra icons
    └── resume.pdf  ← placeholder — replace with your real resume
```

## Before you publish, replace these placeholders

| Where | What to update |
|---|---|
| Hero section | Profile picture placeholder (`.profile-placeholder` in `index.html`) — swap the icon for an `<img>` |
| `assets/resume.pdf` | Your real resume (keep the filename, or update the `href` in the "Download Resume" button) |
| Social links | GitHub / LinkedIn `href="#"` links in the header, hero, and footer |
| Projects | GitHub & Live Demo links (`href="#"`) on each project card, plus real screenshots in `assets/images/` |
| Education | Institution names, years and coursework in the Education timeline |
| Certificates | Certificate titles, issuers and dates |
| Experience | Internship/training details once available |
| Contact form | Currently front-end only (shows a confirmation message but doesn't send email). Wire it up to a service like Formspree, EmailJS, or your own backend endpoint — see the comment in `script.js` (section 7) |

## Running it
No build step needed — just open `index.html` in a browser, or serve the
folder with any static file server.

## Features included
- Sticky glass navigation bar with active hover states
- Dark/light mode toggle (persisted via localStorage)
- Typing animation in the hero tagline
- Scroll progress bar, scroll-to-top button, smooth scrolling
- Scroll-triggered reveal animations, animated skill bars, animated stat counters
- Project filtering by category
- Fully responsive layout (down to small mobile widths)
- Respects `prefers-reduced-motion`
- Semantic, SEO-friendly HTML structure
