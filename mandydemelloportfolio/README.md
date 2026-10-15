# Mandy De Mello portfolio site

A static site: plain HTML and one stylesheet, no build step. Open `index.html` in a browser to preview it.

## Structure

```
index.html          Home (public)
work.html           Use-case tiles with filters (public)
leadership.html     How I lead (public)
about.html          About (public)
assets/             CSS, photos, icons, and your images
  index.html        List of case studies, shown after sign-in
  notetaker-deal-progression.html, transcript-adoption.html, sales-workspace.html,
  veeva-engage.html, veeva-network.html, deal-intelligence.html, meeting-prep.html,
  forecasting.html
```

The full case studies are no longer pages on this site. Each "View the full case study" link opens a password-protected Figma prototype (file "Portfolio-Case-Studies"), one starting point per case study.

## Protecting the case studies in Figma

1. Open the Figma file, then Share → Share prototype.
2. Set link access to "Anyone with the link and password" and choose a password.
3. Make sure the file itself isn't shared publicly (only the prototype link with a password).
4. Test a case study link from the site in a private window: Figma should ask for the password.

## Images to add

Every grey box shows its file path. Save your image at that path (PNG, or change the extension in the HTML) and replace the grey `<div class="ph">` with:

```html
<img src="assets/img/FILE.png" alt="Describe the screen" width="1600" height="1000" loading="lazy">
```

Use `../assets/img/FILE.png` inside `case-studies/`. Covers and screenshots work best at 16:10, about 1600 × 1000.

### Public pages (keep these to public or redacted shots)

| File | What goes there |
|---|---|
| `assets/img/andi-rules-simulation.png` | Veeva Andi rules and simulation screen, as shipped (2019) |
| `assets/img/system-bedrock-quality-bar-weekly-ux-sync.png` | Bedrock quality bar + weekly UX sync thumbnail |
| `assets/img/system-experience-readiness-checklist.png` | Experience Readiness Checklist thumbnail |
| `assets/img/system-interview-cheat-sheet.png` | Interview Cheat Sheet thumbnail |
| `assets/img/system-success-criteria-2-0.png` | Success Criteria 2.0 thumbnail |
| `assets/img/system-ux-complete-outcomes.png` | UX Complete Outcomes thumbnail |
| `assets/img/system-veeva-s-first-design-library.png` | Veeva&#x27;s first design library thumbnail |
| `assets/img/tile-deal-intelligence.png` | Deal Intelligence cover · 16:10 |
| `assets/img/tile-forecasting.png` | Forecasting cover · 16:10 |
| `assets/img/tile-meeting-prep.png` | Meeting Prep &amp; Follow-up cover · 16:10 |
| `assets/img/tile-notetaker-deal-progression.png` | Notetaker + Smart Deal Progression cover · 16:10 |
| `assets/img/tile-sales-workspace.png` | Sales Workspace cover · 16:10 |
| `assets/img/tile-transcript-adoption.png` | Transcript Adoption cover · 16:10 |
| `assets/img/tile-veeva-engage.png` | Veeva Engage cover · 16:10 |
| `assets/img/tile-veeva-network.png` | Veeva Network cover · 16:10 |

### Case study pages (behind Access)

| File | What goes there |
|---|---|
| `assets/img/deal-intelligence-hero.png` | Deal score card with key factors and trend · hero |
| `assets/img/forecasting-hero.png` | Forecast view · hero |
| `assets/img/meeting-prep-hero.png` | Meeting prep with deal brief and pain points · hero |
| `assets/img/notetaker-deal-progression-decision-1.png` | CRM update suggestions with source |
| `assets/img/notetaker-deal-progression-decision-2.png` | Recap empty state, before and after |
| `assets/img/notetaker-deal-progression-decision-3.png` | Heuristic scorecard for AI-driven tasks |
| `assets/img/notetaker-deal-progression-hero.png` | Deal Progression deal page · hero |
| `assets/img/sales-workspace-decision-1.png` | Before and after: two workspaces into one |
| `assets/img/sales-workspace-decision-2.png` | Your tasks card |
| `assets/img/sales-workspace-decision-3.png` | Beta feedback themes |
| `assets/img/sales-workspace-hero.png` | Full Sales Workspace view · hero |
| `assets/img/transcript-adoption-hero.png` | Transcript settings redesign · hero |
| `assets/img/veeva-engage-decision-1.png` | Early Axure prototype |
| `assets/img/veeva-engage-decision-2.png` | Compliant messaging flow |
| `assets/img/veeva-engage-decision-3.png` | First release on iOS and Android |
| `assets/img/veeva-engage-hero.png` | MyVeeva for Doctors mobile and web screens · hero |
| `assets/img/veeva-network-decision-1.png` | HCP profile, before and after |
| `assets/img/veeva-network-decision-2.png` | Source Subscription Wizard Mode |
| `assets/img/veeva-network-decision-3.png` | Query Builder |
| `assets/img/veeva-network-hero.png` | Network customer master UI · hero |

## Still to confirm

Yellow highlights in the case studies mark details to confirm or remove before you publish:

- Notetaker + Smart Deal Progression: the research insight behind review-and-approve.
- Transcript Adoption: the hypothesis from your calls with non-adopters.
- Sales Workspace: team size.
- Veeva Engage: dates.
- Meeting Prep and Forecasting: a metric or business outcome, or delete the line.

Also check the LinkedIn link (currently linkedin.com/in/amandademello).
