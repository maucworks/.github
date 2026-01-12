# maucworks

maucworks is where **MAUC** open-sources the tools we build and use in practice.

MAUC is an **open-data-first** architecture and design firm. We make our own tooling to stay out of walled gardens, keep workflows portable, and explore fresh ways of looking at the landscape, the built environment, and community. A lot of our work starts with public sources and ends with outputs you can trace, reproduce, and ship with confidence.

This GitHub org is our workshop shelf. You will find small utilities and larger building blocks that we actively use, refine, and share so others can learn from them, reuse them, and build on top of them.

---

## Focus areas

### Geodata engineering (core work)
We build practical pipelines that turn public sources into consistent datasets. The goal is simple: repeatable builds, clear provenance, and outputs that work across mapping, analysis, and downstream systems.

### Automated publishing and layout
We are building a modern publishing pipeline that replaces desktop-bound workflows. Layouts are defined in a structured way, generated deterministically, and designed to plug into API-driven systems.

### Developer tooling and automation
Good tools remove friction. We like CLIs, scripts, and small libraries that make workflows faster, more predictable, and easier to maintain.

---

## Main project: py-giskit

**py-giskit** is our recipe-based construction kit for building **GeoPackage (GPKG)** datasets from public sources.

It is aimed at teams who want:
- reproducible GPKG deliverables from defined recipes
- sourcing and transformation steps that are easy to inspect
- dataset builds that run locally and in CI

Repository: https://github.com/maucworks/py-giskit

---

## In-house publishing platform: typst-pagemaker

**typst-pagemaker** is our grid-based layout system built as an InDesign replacement for repeatable production workflows. Layout is described in structured text and converted to **Typst**, which makes the pipeline versionable and automation-friendly.

Typical use cases:
- consistent layouts from structured definitions
- document builds that can be scripted and tested
- a clear path to API-driven publishing

Repository: https://github.com/maucworks/typst-pagemaker

---

## Utility tooling

### google-font-downloader
A Python CLI (published on PyPI) to download Google Web Fonts. Useful for reproducible builds and keeping font assets local.

Repository: https://github.com/maucworks/google-font-downloader

---

## How we work

We like short feedback loops and clear deliverables:
1. Discovery and constraints
2. Prototype as a thin vertical slice
3. Hardening with tests, validation, CI, and docs
4. Handover with a runbook and a maintainable path forward

---

## Get in touch

Interested in:
- reproducible geodata packages,
- automated publishing pipelines,
- pragmatic Python tooling for your team

Open an issue in the relevant repository, or reach out via the contact details on the MAUC website.
