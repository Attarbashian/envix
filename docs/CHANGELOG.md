# Changelog

## 2.2.0 — Discoverability, language consistency and private-repository UX

- Added a prominent homepage Quick Tool Finder with live search plus specialist-suite, domain and tool-type filters.
- Added route-level SEO titles/descriptions, canonical URLs and JSON-LD for public Envix pages.
- Added `sitemap.xml`, crawler-friendly `robots.txt`, OAI-SearchBot access and a concise `llms.txt` project summary.
- Added explicit locale-aware number/date formatting so English mode does not inherit Persian digits or date formatting from the browser.
- Fixed language-switch defaults in comparison/report workflows without overwriting user-edited content.
- Reworked the homepage support block into clearly labeled public actions that work while the source repository is private.
- Removed private-repository Issue links from the tool-suggestion flow and replaced them with email/public-site paths.
- Changed header/footer GitHub links to the creator profile instead of the private Envix repository.
- Disabled production source maps and kept Vite minification enabled for a cleaner public bundle.
- Updated the bilingual README to describe the private-source/public-site model and current search-discovery architecture.


## v2.1.0

- Redesigned Home and Collections around specialist suites, newest-first discovery and cleaner cards.
- AERMOD meteorology converter now supports unlimited user-selected variables after fixed year/month/day/hour columns.
- Added per-variable interpolation modes: linear, circular 0–360 and nearest/categorical.
- Updated Industrial Stack Emission & AERMOD Source Lab to avoid silent zero source parameters.
- Added explicit reference/screening assumptions and QC reporting.
- Added official AERMOD ambient-temperature release option (`Stktmp=0.0`) as an explicit user choice.
- Fixed AERMOD Tool Finder/Template discovery to include the newest stack-emission and meteorology labs.
- Fixed newest sorting in the main Tool Registry and recent-additions shelf.
- Expanded Home tool-type filter to include utility/reference tools.
- Rewrote README as a complete Persian section followed by a separate English section.

## 1.8.0

- Added FMEA with configurable RPN prioritization, residual risk and Excel export.
- Added EFMEA with environmental aspect/impact, life-cycle stage and compliance-priority logic.
- Added comprehensive industrial stack emission/AERMOD source lab using official EPA model units and user-supplied authoritative emission factors.
- Added population/demography indicators and projection lab based on UN definitions and transparent screening scenarios.
- Improved IRIMO → hourly meteorology UX with a three-step workflow and selectable long-gap/edge policy.
- Added explicit provenance policy to avoid copying third-party calculators, factor tables or UI/text.
- Registered tool count reached 107.

## 1.7.0
- Tailored the AERMOD meteorology converter to the supplied IRIMO source and target workbooks.
- Added support for IRIMO HTML-table files distributed with an `.xls` extension.
- Locked AERMOD-style output to `year, month, day, hour, cloud cover, t, RH, wind direction, wind speed`.
- Added automatic `data/n/t/u/dd/ff` mapping, 01–24 AERMET clock conversion, long-gap interpolation QC and edge-fill QC.

## 1.1.0
- Added 9 specialist MCDA/EIA tools: AHP, ANP, Fuzzy AHP, WLC, TOPSIS, RIAM/Pastakia, Leopold Matrix, Iranian EIA Matrix, and a weighted EIA screening checklist.
- Added per-tool Excel (.xls) export for visible inputs, results, metadata, methodology, formula, notes and source.
- Added detailed bilingual GUIDE content and result interpretation for all new MCDA/EIA methods.
- Added MCDA and EIA-method discovery goals and a dedicated homepage spotlight.
- Refined primary/secondary/action button styling with compact rounded UI-kit-inspired states, shadows and hover feedback.

## 0.9.0
- Rebuilt both language and Light/Dark controls as true compact iOS-style sliding toggle switches inspired by the referenced CodePen pattern.
- Fixed the header layout by direction: Persian places the Envix logo at the far right and switches at the far left; English places the logo at the far left and switches at the far right.
- Replaced the previously cropped logo and mark image assets with newly reconstructed full transparent versions, so no part of the logo is clipped in the header, About, footer, or mark placements.
- Reduced the visual footprint and background padding around site logos for a cleaner header and About section.
- Preserved the complete bilingual per-tool GUIDE library for all 75 tools from v0.8.

## 0.8.0
- Reduced header, About and footer Envix logos by ~50% from the previous revision.
- Rebuilt language and Light/Dark controls as compact segmented toggle switches.
- Direction-aware header: Persian keeps logo on the right and controls on the left; English reverses them.
- Creator / maintainer card changed to a high-contrast green treatment with white typography.
- Footer now begins with a small Envix logo, links the project credit to attarbashian.ir, removes the academic title from the footer credit, and keeps only the Envix GitHub icon opposite it.
- Added an explicit bilingual GUIDE for every one of the 75 current tools. Each guide explains what the tool/index is, how the result is derived, and how to interpret the output; established result bands are included where meaningful, while tools without universal classes say so explicitly.

## Envix v0.4.0

- Expanded the registry to 70 environmental tools.
- Added a dedicated Biomonitoring & Ecology domain with 16 tools, including Chao1, Bray–Curtis and Whittaker beta diversity.
- Added specialized water/hydrology tools such as alkalinity conversion, sedimentation overflow rate, Rational Method runoff and treatment removal efficiency.
- Added carbon-stock ↔ CO₂, solar-energy, dilution and first-order decay tools.
- Rebuilt the Tools catalog with full-text tag/alias search, category, subgroup, type, difficulty and status filters.
- Added goal-based Tool Finder, Popular and New shelves, favorites, recent history, sorting, grid/list display and related-tool suggestions.
- Added per-tool colorful minimalist micro-graphics.
- Preserved the approved original Envix transparent PNG logo and mark.
- Improved About and Suggest-a-Tool pages.
- Extended responsive and dark-mode styles for all new components.

## 1.5.0

- Added Data Wizard controls to structured data tables and decision matrices.
- Added example datasets, undo/redo, browser autosave and input-quality checking to professional data workflows.
- Added `.envix` project package export/import including projects, history, preferences and structured tool autosave state.
- Added explicit AHP, Chao1 and coordinate quality guidance.
- Reworked README to document the current 93-tool Workbench architecture and features.

## v1.9.0 — Downloadable analysis charts
- Added a compact download control directly on analytical/statistical charts.
- Charts export as high-resolution PNG with title and Envix attribution.
- Persian chart exports use RTL title alignment and Vazirmatn when available.
- The control applies to histogram, bar plot, Q–Q/scatter, boxplot, time-series, regression diagnostics, PCA, Monte Carlo and spatial scatter charts built on the shared analysis chart components.

## 2.0.0 — Workbench integrity, metadata and reproducibility

- Sort specialist Collection tool lists from newest to oldest.
- Add Data Dictionary / Variable Metadata to structured data-entry workflows.
- Add local Analysis Log / Audit Trail with CSV export.
- Add Reproducibility Bundle ZIP from Report Builder.
- Add direct cross-tool handoff: QA/QC → Statistics, Statistics → Report, MCDA → Comparison/Sensitivity.
- Add Validation Library and method maturity badges.
- Add accessibility improvements for keyboard, screen readers, contrast, reduced motion and print.
- Expand PWA offline caching to core workbench routes and example datasets.
- Add Project Dashboard with scenario/tool/warning/activity overview.
- Capture analytical charts in saved scenarios for report/reproducibility export.
- Rewrite README as a bilingual, current project reference.
