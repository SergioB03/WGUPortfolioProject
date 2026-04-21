# Sergio Banuelos — WGU Portfolio Project
> This file gives Claude Code full context on the project. Read this before making any changes.

---

## What This Is
A personal portfolio website for **Sergio Banuelos** built for a WGU Web Development course (Competencies 4073.1.1–4073.1.3). The project demonstrates HTML, CSS, and JavaScript skills. **No frameworks allowed** — vanilla HTML/CSS/JS only.

## File Structure
```
portfolio/
├── CLAUDE.md               ← You are here
├── master.css              ← Single external stylesheet for ALL pages
├── resume.html             ← Page A
├── cover-letter.html       ← Page B
├── career-goals.html       ← Page C
└── media/
    ├── profile.png         ← NEEDS REPLACING with real photo
    ├── intro.wav           ← NEEDS REPLACING with real audio recording
    └── intro.mp4           ← NEEDS REPLACING with real video recording
```

---

## Owner Info
- **Name:** Sergio Banuelos
- **Email:** sergiobanuelos03@gmail.com
- **Phone:** (678) 555-0147
- **Location:** Atlanta, GA
- **LinkedIn:** linkedin.com/in/sergio-banuelos-atl
- **School:** Western Governors University — B.S. Computer Science (In Progress)
- **Target employer:** Google (Software Engineer)

---

## WGU Rubric Checklist

### A — resume.html ✅
- [x] Basic structure: html, head, title, body
- [x] header, nav (links to all 3 pages), main, section, footer, article
- [x] h1–h6 (at least 3 different heading levels used)
- [x] span, paragraph, line break, horizontal rule
- [x] div#current-date populated via inline JavaScript
- [x] Inline JS writes message to console
- [x] hyperlink, ordered list, unordered list
- [x] Table with caption, 4+ columns, 3+ rows
- [x] strong, em

### B — cover-letter.html ✅
- [x] Basic structure: html, head, title, body
- [x] header, nav, main, section, footer, article
- [x] span, paragraph, horizontal rule
- [x] strong, em, mark

### C — career-goals.html ✅
- [x] Basic structure: html, head, title, body
- [x] header, nav, main, footer
- [x] Locally sourced image (media/profile.png)
- [x] Locally sourced audio (media/intro.wav)
- [x] Locally sourced video (media/intro.mp4)
- [x] Form with action="https://wp.zybooks.com/form-viewer.php"
  - [x] first name, last name, company name
  - [x] email (type=email), phone (type=tel)
  - [x] message (textarea)
  - [x] best contact time (radio: a.m., p.m., anytime)
  - [x] select list (phone, email, text)
  - [x] submit button

### D — master.css ✅
- [x] element selector
- [x] class selector
- [x] id selector
- [x] descendant selector
- [x] pseudo-class selector
- [x] universal selector (*)
- [x] font property
- [x] color property
- [x] font-style property
- [x] background-color property
- [x] margin property
- [x] padding property
- [x] border property
- [x] list-style property

---

## Design System
- **Theme:** Dark tech aesthetic
- **Colors (CSS vars):**
  - `--bg-primary: #0d1117`
  - `--bg-secondary: #161b22`
  - `--bg-card: #1c2333`
  - `--accent-cyan: #00b4d8`
  - `--accent-light: #90e0ef`
  - `--text-primary: #e6edf3`
  - `--text-muted: #8b949e`
  - `--border-color: #30363d`
- **Fonts (Google Fonts):**
  - Headings: `Raleway`
  - Body: `Lato`
  - Monospace: `Source Code Pro`

---

## Rules (Don't Break These)
1. **No CSS/JS frameworks** — no Bootstrap, Tailwind, jQuery, React, etc.
2. **No external media links** — all images, audio, video must be in `/media/` folder
3. **One CSS file only** — `master.css` must be linked to all 3 HTML pages
4. **Submission format:** ZIP file named `portfolio_sergio_banuelos.zip`
5. **File size:** Under 200MB total, under 16MB per file

---

## TODO / Known Issues
- [ ] Replace `media/profile.png` with a real photo of Sergio
- [ ] Replace `media/intro.wav` with a real personal audio intro
- [ ] Replace `media/intro.mp4` with a real personal video intro
- [ ] Add sources/citations section if quoting any external content (Rubric E)
- [ ] Run through Grammarly before final submission (Rubric F)
- [ ] Test all nav links work correctly when opened in browser
- [ ] Validate HTML at validator.w3.org before submitting
