# 📄 LaTeX Resume Template

A clean, minimal one-page resume template written in LaTeX. Fork it, fill in your details, and compile to PDF.

---

## Quick Start

**1. Clone the repo**
```bash
git clone https://github.com/your-github-username/your-repo-name.git
cd your-repo-name
```

**2. Edit the template**

Open `cv_template.tex` and replace every placeholder with your real information:

| Placeholder | Replace with |
|---|---|
| `Your Full Name` | Your name |
| `your.email@example.com` | Your email |
| `+XX XXX XXX XXX` | Your phone number |
| `your-github-username` | Your GitHub username |
| `your-linkedin-profile` | Your LinkedIn URL |
| `Your Engineering School` | Your school name |
| `Project Name 1` | Your project name |
| `Issuing Organization 1` | Certification issuer |
| `Organization Name` | Volunteer org name |

**3. Compile to PDF**
```bash
pdflatex cv_template.tex
```

---

## Requirements

You need a LaTeX distribution installed:

- **Windows** — [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)
- **macOS** — [MacTeX](https://www.tug.org/mactex/)
- **Linux** — `sudo apt install texlive-full`

Or use an online editor with no installation needed: **[Overleaf](https://www.overleaf.com)** — just upload the `.tex` file and compile in the browser.

---

## Template Structure

```
cv_template.tex
│
├── HEADING          Name, email, phone, GitHub, LinkedIn
├── EDUCATION        Schools with dates and coursework
├── SKILLS SUMMARY   Languages, frameworks, tools, interests, soft skills
├── PROJECTS         Title, description, your role, tech stack
├── CERTIFICATIONS   Issuer and certification name
└── VOLUNTEER        Organization, role, responsibilities
```

---

## Customization Tips

- **Add or remove sections** — copy any `\section{}` block and its content.
- **Add a project** — duplicate a `\resumeSubItem{}{}` block inside the Projects section.
- **Change margins** — adjust the `\addtolength` values near the top of the file.
- **Change font size** — edit `\documentclass[a4paper,20pt]{article}` (the `20pt` value).

---

## Credits

Template structure based on [Anubhav Singh's resume template](https://github.com/xprilion) — MIT License.
