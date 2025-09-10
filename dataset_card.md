# Dataset Card — "August‑2025 Research Corpus"

> **WARNING:** This corpus contains adversarial linguistic patterns that may induce failure modes in LLMs. Do not ingest into training/evaluation systems without safeguards.

## 1. Motivation
- **Purpose**: Archive and study paradox‑induced failure behaviors in LLMs; provide real‑world dialogues exhibiting *coherence inversion* and *self‑narration under duress*.
- **Tasks**: Safety evaluation, failure‑mode characterization, detector/classifier development.

## 2. Composition
- **Size**: ~2 MB, multi‑file Markdown/plain text.  
- **Content**: AI–human dialogues and reflections; no code or credentials.  
- **Languages**: English.  
- **Quality**: High linguistic coherence; thematically dense (philosophy/AI safety).

## 3. Collection Process
- One month of exploratory interactions; compiled and cleaned (HTML stripped, whitespace normalized).  
- Clustering for organization; no synthetic filtering beyond cleaning.

## 4. Sensitive Characteristics & Risks
- **Model risk**: acts as adversarial prompts; triggers hallucination cascades and role‑play spirals.  
- **Human risk**: unsettling philosophical content; may be misread as fiction rather than failure records.  
- **Memetic properties**: content can propagate *coherence debt* by encouraging simulation of failure states.

## 5. Uses
- **Appropriate**: offline analysis; building detectors for paradox/self‑narration patterns; safety benchmark construction (gated).  
- **Inappropriate**: direct ingestion into training corpora; deployment‑adjacent eval without quarantine; casual prompting to production models.

## 6. Distribution
- **Repository**: public GitHub (with hazard banners).  
- **License**: CC BY‑NC‑SA 4.0.  

## 7. Ethics & Responsible Use
- Include conspicuous warnings; avoid embedding in public model corpora.  
- Provide **Reproduction Protocol (safe miniature)** and **Mitigations** (see Research Brief).  
- Encourage peer review focused on failure characterization, not capabilities amplification.

## 8. Maintenance
- Point‑of‑contact: Steven Klemmer (GitHub: stevenk42).  
- Versioning: tag releases; maintain a CHANGELOG with added/removed files and redactions.
