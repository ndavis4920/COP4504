# Faculty Web Presence — Lakeside University

A two-page HTML/CSS prototype for a faculty web presence system designed to be sold to multiple educational institutions. The CSS stylesheet is the only file that needs to be swapped to rebrand the site for any client school.

## Contents

```
/
├── index.html      Faculty profile display page (public-facing)
├── edit.html       Faculty information entry/edit form
├── css/
│   └── style.css   Lakeside University theme (navy + gold)
└── README.md
```

## How to View Locally

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Click **Edit Profile** to navigate to `edit.html`
4. No server or build tools required — pure HTML and CSS

## Pages

**index.html** — Displays a faculty member's profile including photo, name, title, contact info, biography, office hours, and courses taught with syllabus links.

**edit.html** — Form page for faculty to enter or update their profile information, manage office hours, and manage course listings.

## Design Notes

- School colors: Navy `#1a3a5c` + Gold `#c9a227`
- To rebrand for a different institution, replace `css/style.css` with a new stylesheet using the same class names
