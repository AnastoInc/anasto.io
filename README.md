# Anasto

**Where Clinical Vision Meets Engineering Excellence**

Anasto is a professional network connecting clinicians who have problems to solve with biomedical engineers, computational experts, and AI agents who can solve them.

🌐 **Live Site:** https://anastoinc.github.io/anasto.io/

---

## 🎯 The Problem

Clinicians often face engineering challenges they can't solve alone:
- Device design and optimization
- Computational modeling (CFD, FEA, biomechanics)
- AI/ML for diagnostics and prediction
- Genetic analysis and bioinformatics
- Regulatory pathway navigation

Finding the right expertise is hard. Traditional consulting is slow and expensive. 

## 💡 The Solution

Anasto provides **instant matching** between clinicians and:

1. **Human Experts** — Vetted biomedical engineers, data scientists, and domain specialists
2. **AI Agents** — Specialized Monica instances that provide 24/7 expert-level analysis (CFD, biomechanics, patent research, and more)

Think LinkedIn meets Upwork, purpose-built for medical technology.

---

## 👥 Founders

| Name | Role | Background |
|------|------|------------|
| **CJ Shores** | CEO | Business development, institutional partnerships, fundraising |
| **Prahlad Menon, PhD, PMP** | CTO | Technical architecture, AI systems, Carnegie Mellon PhD |

### Name Origin
**"Anasto"** comes from **Anastomosis** — the surgical connection of two separate structures. Just like surgeons connect blood vessels or neural pathways, we connect clinicians with problems to engineers who can solve them.

---

## 🔬 Expertise Areas

| Domain | Examples |
|--------|----------|
| Computational Fluid Dynamics | Blood flow analysis, device hemodynamics, surgical planning |
| Biomechanics | Tissue mechanics, implant analysis, motion capture |
| Genetics & Bioinformatics | Genomic analysis, variant interpretation, pipelines |
| AI & Machine Learning | Medical imaging, diagnostics, predictive models |
| Medical Device Design | Concept to prototype, FDA pathways, testing |
| Clinical Data Science | EHR analysis, outcomes research, RWE |
| Drug Delivery | PK/PD modeling, formulation, targeted therapy |
| Regulatory & Quality | 510(k), CE marking, ISO compliance |

---

## 💰 Engagement Tiers

| Tier | Price | Includes |
|------|-------|----------|
| **Quick Consult** | Starting at $250 | 1-hour session, feasibility assessment, prior art check |
| **Project Sprint** | Custom Quote | Dedicated team, NDA-protected, blockchain-timestamped deliverables |
| **Institutional** | Enterprise | Unlimited AI access, priority matching, dedicated success manager |

---

## 🛠️ Technical Setup

### Waitlist Form (Formspree)

The waitlist form uses [Formspree](https://formspree.io) for reliable form handling:

- **Form ID:** `xanywzgk`
- **Endpoint:** `https://formspree.io/f/xanywzgk`
- **Features:**
  - Sends submissions directly to founder email
  - Auto-confirmation email to signups (via `_autoresponse` field)
  - Redirects to thanks.html after submission

#### Fields Collected:
- Name (required)
- Email (required)
- Role (required): Clinician, Engineer, Researcher, Institution, Other
- Institution/Company (optional)
- LinkedIn URL (optional)
- Portfolio/Website URL (optional)

#### To change the Formspree destination:
1. Go to https://formspree.io and create a new form
2. Update the form `action` URL in `index.html` and `waitlist.html`
3. Update the `_autoresponse` hidden field for confirmation email text

### Pages

| Page | Purpose |
|------|---------|
| `index.html` | Main landing page with embedded waitlist form |
| `waitlist.html` | Standalone waitlist signup page |
| `thanks.html` | Confirmation page after signup |
| `admin.html` | Legacy admin dashboard (deprecated - use Formspree dashboard) |

### Assets

| File | Description |
|------|-------------|
| `logo.svg` | Vector logo (gradient A with anastomosis design) |
| `logo.png` | Rasterized logo (200x200) |

---

## 📦 Repository Structure

```
anasto.io/
├── index.html      # Main landing page
├── waitlist.html   # Standalone waitlist form
├── thanks.html     # Post-signup confirmation
├── admin.html      # Legacy admin (deprecated)
├── logo.svg        # Vector logo
├── logo.png        # PNG logo
├── README.md       # This file
└── waitlist/       # (Legacy) JSON storage
    └── entries.json
```

---

## 🚀 Deployment

Site is deployed via GitHub Pages:
- **URL:** https://anastoinc.github.io/anasto.io/
- **Auto-deploys** on push to `main` branch

### Backup Repositories
- **Primary:** `AnastoInc/anasto.io` (this repo)
- **Backup:** `menonpg/anasto-backup` (private mirror)

---

## 📧 Contact

**Email:** hello@anasto.io  
**Founders:** prahlad.menon@quant.md

---

*© 2026 Anasto Inc. Pittsburgh, PA.*
