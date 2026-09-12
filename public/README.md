<p align="center">
  <img src="assets/envix-logo.png" alt="Envix" width="190" />
</p>

# Envix

**Envix** is a browser-based environmental analysis and scientific workbench created and maintained by **Vahid Attarbashian**, PhD in Environmental Science and Engineering.

- Website: https://envix.ir
- Creator: https://attarbashian.ir
- GitHub: https://github.com/Attarbashian
- Current public release: **v2.2**
- Registered tools: **107**

> This repository is the **public project showcase and documentation repository** for Envix. The production source code and deployment repository are maintained privately.

## What Envix includes

Envix combines environmental calculators, scientific analysis workflows, data-quality tools and decision-support methods in one interface. Major areas include:

- AERMOD preparation and industrial stack-emission workflows
- 3-hour meteorology → hourly preprocessing with fixed `year | month | day | hour` output columns and flexible additional variables
- FMEA / EFMEA and environmental impact assessment
- MCDA: AHP, ANP, Fuzzy AHP, TOPSIS, VIKOR, DEMATEL, PROMETHEE, SWARA, WASPAS, OWA and related methods
- Statistics Lab, R Lab & Code Builder, time-series, regression, PCA and multivariate analysis
- Environmental QA/QC, sampling and uncertainty analysis
- Biomonitoring and ecological indices
- Water, soil, climate/drought, carbon, waste, noise, GIS and general environmental utilities
- Project Workspace, Scenario management, Audit Trail and reproducibility features

## Workbench capabilities

- Smart Input and Data Wizard
- Dynamic rows and columns
- Excel/CSV import and direct spreadsheet paste
- Example datasets, Undo/Redo and local autosave
- Data Dictionary with unit, type, description and missing-value codes
- Pre-analysis Quality Checks
- Project Dashboard and portable `.envix` project packages
- Report Builder and Reproducibility Bundle
- Cross-tool data handoff
- Validation Library and Method Maturity badges
- Excel export and chart PNG download
- PWA/offline support for core pages and examples
- Favorites, recent tools and calculation history
- Bilingual Persian/English interface
- Homepage Quick Tool Finder for navigating the 100+ tools

## AERMOD & air-modelling focus

Envix includes a dedicated AERMOD collection. Key modules include:

- **Industrial Stack Emission & AERMOD Source Lab**
- **3-hour Meteorology → Hourly Converter**
- emission-rate and emission-factor utilities
- stack flow correction and concentration normalization
- stack exit velocity
- flare effective parameters
- gas concentration and ppb ↔ µg/m³ conversion

The meteorology converter keeps the first four output columns fixed as:

`year | month | day | hour`

Any number of additional meteorological variables can then be included. Per-variable interpolation can be configured as linear, circular 0–360, or nearest/categorical.

## Scientific integrity

Envix aims to keep calculations transparent and reference-based. Important tools expose methodology, formulas, assumptions, limitations, references and dedicated guides. Method maturity is shown separately as **Validated**, **Reference-checked**, or **Experimental**.

“Validated” means an internal Envix calculation check against known/reference examples; it does not imply third-party certification.

## Privacy

Most calculations are performed in the browser. Workspace data, autosave, favorites and history are local by default. Typical calculator use does not require an account.

## Documentation

- [Tool catalog](docs/TOOL_CATALOG.md)
- [Current feature summary](docs/FEATURES_v2.2.md)
- [Changelog](docs/CHANGELOG.md)
- [Branding policy](BRANDING.md)

## Source availability

The production application source is intentionally kept in a private deployment repository. This public repository is for project discovery, documentation, release notes, citation and community-facing information.

## Citation

If Envix supports your analysis, please cite the project website and the relevant release. A DOI-backed software release can be added here when a Zenodo release is published.

## Brand

The **Envix** name, logo, visual mark and brand identity are not granted for reuse by this documentation repository. See [BRANDING.md](BRANDING.md).

---

## نسخه فارسی

**Envix** یک محیط یکپارچه برای محاسبات و تحلیل‌های محیط‌زیستی، تصمیم‌گیری چندمعیاره، ارزیابی اثرات، آماده‌سازی ورودی AERMOD، آمار، R، پایش زیستی، GIS و بازتولیدپذیری علمی است که توسط **وحید عطارباشیان** توسعه و نگهداری می‌شود.

این مخزن، **مخزن عمومی معرفی و مستندات Envix** است. سورس اصلی نسخه production و مخزن مورد استفاده برای Build/Deploy به‌صورت خصوصی نگهداری می‌شوند.

- وب‌سایت: https://envix.ir
- وب‌سایت توسعه‌دهنده: https://attarbashian.ir
- نسخه فعلی: **v2.2**
- تعداد ابزارهای ثبت‌شده: **107**

برای مشاهده امکانات کامل، کاتالوگ ابزارها و تغییرات نسخه‌ها از فایل‌های بخش Documentation استفاده کنید.
