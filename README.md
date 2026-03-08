<!-- ═══════════════════════════════════════════════════════════
     KinSushi/OpenClassroomsProject — Web Development Portfolio
     Parcours Developpeur WordPress · RNCP38145
     Part of the SOVRALYS 9-year trajectory: Web Dev > ML Engineer > Quant
     ═══════════════════════════════════════════════════════════ -->

# Web Development Portfolio
## OpenClassrooms — Parcours Developpeur WordPress · RNCP38145

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-coming_soon-F7DF1E?style=flat-square&logo=javascript&logoColor=black&labelColor=555)
![WordPress](https://img.shields.io/badge/WordPress-coming_soon-21759B?style=flat-square&logo=wordpress&logoColor=white&labelColor=555)
![GitHub Pages](https://img.shields.io/badge/Demo-GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)
![OpenClassrooms](https://img.shields.io/badge/OpenClassrooms-RNCP38145-blueviolet?style=flat-square)

This repository documents the complete **OpenClassrooms Web Developer WordPress path** (RNCP38145), built as Phase 1 of the [SOVRALYS](https://github.com/KinSushi) 9-year trajectory toward ML Engineering and Quantitative Finance.
Each project is a production-ready deliverable — semantic HTML5, pure CSS, and eventually JavaScript and WordPress — with no frameworks until they become the point.

---

## Projects

| # | Project | Description | Stack | Status | Demo |
|---|---|---|---|---|---|
| 03 | Reservia | Travel agency showcase — responsive mobile-first | HTML5 · CSS3 · CSS Variables | Done | [Live](https://kinsushi.github.io/OpenClassroomsProject/) |
| 04 | Ohmyfood | Animations CSS — restaurant ordering UI | HTML5 · CSS3 · SASS | Next | — |
| 05 | Print It | JS DOM manipulation — print shop carousel | HTML5 · CSS3 · JS | Planned | — |
| 06 | Sophie Bluel | JS + API — portfolio architect | HTML5 · CSS3 · JS · REST API | Planned | — |
| 07 | Nina Carducci | Optimization — SEO · a11y · perf | HTML5 · CSS3 · Lighthouse | Planned | — |
| 08 | Kasa | React SPA — rental platform | React · React Router · SASS | Planned | — |
| 09 | Mon Vieux Grimoire | Node.js backend — book rating API | Node.js · Express · MongoDB | Planned | — |
| 10 | Shiny Agency | TDD — React testing | React · Jest · RTL | Planned | — |
| 11 | ArgentBank | Redux — bank auth SPA | React · Redux Toolkit | Planned | — |
| 12 | SportSee | Data dashboards — charts | React · Recharts | Planned | — |
| 13 | WordPress Theme | Custom WP theme — RNCP38145 final | WordPress · PHP · ACF | Planned | — |

---

## Project 03 — Reservia (Active)

**Live demo** : [https://kinsushi.github.io/OpenClassroomsProject/](https://kinsushi.github.io/OpenClassroomsProject/)

Key technical decisions:
- 12 CSS custom properties (colors, spacing) in `:root` — single source of truth
- Mobile-first: base styles for 320px, breakpoints at 768px · 1024px · 1200px
- Semantic HTML5: header, nav, main, section, article, footer
- Filter buttons with `aria-pressed` for screen reader accessibility
- 4-column footer with responsive column stacking

```
OpenClassroomsProject/
├── index.html         # Reservia — full semantic structure
├── styles.css         # CSS Variables + mobile-first responsive
├── images/            # Visual assets (to be added)
└── README.md          # This file
```

---

## Workflow

This repository uses **Conventional Commits** and **feature branches**.

```bash
# Branch naming
feature/project-name-description
fix/description
docs/description

# Commit format
feat(projet03): add filter buttons with aria-pressed
fix(projet03): correct card overflow at 768px breakpoint
docs: update README with project 04 status
```

Full workflow reference: [KinSushi/git-workflow-demo](https://github.com/KinSushi/git-workflow-demo)

---

## Certification Target

| Certification | Program | Timeline |
|---|---|---|
| **RNCP38145** — Developpeur Web WordPress | OpenClassrooms | 2025–2026 |
| **RNCP7 + RNCP6** — Data Science & AI | Jedha Bootcamp Paris | From April 13, 2026 |

> This portfolio is **Phase 1** of the SOVRALYS trajectory.
> Phase 2 starts April 2026 — Jedha Bootcamp Paris — Python · ML · MLOps · AWS.

---

## Author

**Enzo · KinSushi** · Founder @ SOVRALYS LLC · Panama City
[GitHub Profile](https://github.com/KinSushi) · [LinkedIn](https://www.linkedin.com/in/enzo-c-di-bacco-074842226)
