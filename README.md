# HealthOps Intelligence Suite
**by Ryan Cox · coxcontent.com**

A practitioner-built library of free diagnostic tools and calculators for specialty care operators. Each tool is a standalone HTML file — no dependencies, no build step, no backend. Drop them in a GitHub Pages repo and they're live.

---

## Tools (21 files)

### Hub
| File | Description |
|------|-------------|
| `methodology.html` | Main hub page — six-phase framework, tool index, roadmap |

### Phase 1–2: Listen & Diagnose
| File | Description |
|------|-------------|
| `intakeiq.html` | Full ops diagnostic — 6 questions, 5 domains, 0–100 score |
| `noshow-calculator.html` | True cost of no-shows including staff time and opportunity cost |
| `dar-benchmarker.html` | Days in A/R vs. specialty benchmarks |
| `auth-denial-scorer.html` | Prior auth denial rate analysis and cost quantification |
| `referral-leakage.html` | Referral funnel visualization and leakage cost |
| `utilization-calculator.html` | Billable vs. available hours and revenue gap |
| `turnover-calculator.html` | Full cost breakdown per staff departure |
| `patient-ltv-calculator.html` | Patient lifetime value with specialty defaults and use cases |

### Phase 3: Recommend
| File | Description |
|------|-------------|
| `backfill-scorer.html` | How well your practice recovers cancelled slots |
| `payer-mix-analyzer.html` | Payer concentration risk and revenue diversification |
| `appeal-roi-calculator.html` | Should you appeal this denial? Expected value vs. cost |
| `build-vs-buy.html` | Build vs. buy decision framework for ops technology |

### Phase 4: Decide
| File | Description |
|------|-------------|
| `automation-roi-builder.html` | Business case builder for workflow automation investment |
| `staffing-ratio-analyzer.html` | Staffing ratios vs. benchmarks |

### Phase 5: Execute
| File | Description |
|------|-------------|
| `golive-checklist.html` | Pre-launch readiness checklist for new system deployments |
| `hipaa-gap-tracker.html` | Administrative safeguard self-assessment (20 items) |
| `implementation-complexity.html` | How hard will this implementation actually be? |

### Phase 6: Operationalize
| File | Description |
|------|-------------|
| `kpi-maturity-scorer.html` | How sophisticated is your operational reporting? |
| `care-coordination-gaps.html` | Cross-specialty handoff breakdown |
| `interoperability-readiness.html` | Data and integration maturity vs. 2028 CMS mandate |

---

## GitHub Pages Setup

1. Create a new GitHub repo (e.g. `healthops`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your hub will be live at `https://yourusername.github.io/healthops/methodology.html`

All internal links between tools use relative paths and will work automatically.

---

## Design System

All tools share the same CSS design system:
- **Fonts:** DM Serif Display (headings) + DM Sans (body) + DM Mono (labels/data)
- **Colors:** Teal `#0d7070` · Amber `#b87020` · Green `#1a7a45` · Red `#c0392b` · Purple `#6655aa`
- **Background:** `#f5f4f0` (warm off-white, forced light mode)
- **Cards:** White surfaces, `#e0ddd5` borders, 6px radius

Each tool is fully self-contained — one HTML file with embedded CSS and JS. No external dependencies except Google Fonts.

---

## Attribution

Built by Ryan Cox. Free to use and share. If you find these useful, visit [coxcontent.com](https://coxcontent.com).
