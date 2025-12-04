# AI Decision Dependence & Cognitive Caution 2025 (Dataset n = 201)

Survey dataset examining how AI use influences decision-making confidence, reliance patterns, self-doubt, and cognitive caution in everyday choices.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17772518.svg)](https://doi.org/10.5281/zenodo.17772518)

**Latest version:** v1.2 — 2025-12-05  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/ai-decision-dependence-cognitive-caution-2025/

**Data summary page:**  
https://humanclarityinstitute.com/data/ai-decision-dependence-cognitive-caution-data-summary/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features
- Measures AI-assisted decision-making, reliance, and confidence shifts  
- Captures cognitive caution, second-guessing, and persuasion effects  
- Includes multi-select values, open-text reflections, and demographic profiles  
- Clean, standardised, machine-readable dataset prepared using HCI protocol  
- Part of the **Human–AI Experience 2025** dataset series

---

## Files Included

| Filename | Description |
|---------|-------------|
| **AI_decision_dependence_cognitive_caution_raw20251201.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **AI_decision_dependence_cognitive_caution_clean20251201.csv** | Clean, machine-ready dataset. Canonical tokens, standardised multi-selects, minimal text cleaning. |
| **AI_decision_dependence_cognitive_caution_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowable values. |
| **sha256.txt** | SHA-256 checksums for all files in this release. |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

## Provenance & Data Collection

The dataset was collected on **29 Nov 2025** via **Prolific** as part of the Human–AI Experience research programme.  
All participants provided **explicit consent** for anonymised open publication.

**Sampling & Quality Controls**
- **Final n:** 201  
- **Countries:** UK, US, Australia, Canada, New Zealand, Ireland  
- **Eligibility:** Adults aged 18+ from six English-speaking countries  
- **Compensation:** Average £8.04/hr  
- **Approval-rate filter:** Not available  
- **Attention checks:** None  
- **AI-deception traps:** None  
- **Anonymisation:** Prolific IDs and timestamps removed before publication  

---

## Data Structure (Summary)

Below are representative variables included in the dataset.  
The full variable list is provided in the accompanying data dictionary.

| Variable | Type | Description |
|----------|------|-------------|
| ai_decision_help_often | numeric | Likert 1–7: frequency of using AI tools for everyday decision-making. |
| ai_influence_second_guessing | numeric | Likert 1–7: extent of increased second-guessing due to AI. |
| ai_influence_persuasive_effect | numeric | Likert 1–7: perceived persuasiveness of AI suggestions. |
| open_text_ai_decision_example | string | Open-text description of a recent AI-assisted decision; minimal cleaning applied. |
| ai_values_multi | multi_select | Semicolon-delimited canonical tokens describing values participants believe AI systems should reflect. |
| emotional_wellbeing | numeric | Likert 1–7: self-rated emotional wellbeing. |

**Multi-select formatting:**  
Stored as semicolon-delimited canonical tokens, e.g.:

empathy;fairness;human_wellbeing

**Open-text fields:**  
Minimal cleaning applied (trim + newline removal).  
Raw participant meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI |
|--------|------|
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **AI Media & Online Authenticity 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17744452.svg)](https://doi.org/10.5281/zenodo.17744452) |
| **Cognitive Load, Fatigue & Decision Offloading 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17636370.svg)](https://doi.org/10.5281/zenodo.17636370) |
| **Emotion, Identity & Creativity in the Age of AI 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |

**Explore the full HCI Dataset Library:**  
https://humanclarityinstitute.com/datasets/
---

## Related Reports

- **Digital Trust — Full Report**  
  https://humanclarityinstitute.com/reports/digital-trust-full-report/

- **Values vs Noise — Full Report**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

- **Digital Fatigue & Energy — Full Report**  
  https://humanclarityinstitute.com/reports/digital-fatigue-and-energy-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## Recommended Citation

    @dataset{hci_ai_decision_dependence_cognitive_caution_2025,
      author       = {Human Clarity Institute},
      title        = {AI Decision Dependence & Cognitive Caution 2025},
      year         = {2025},
      publisher    = {Zenodo},
      version      = {v2.2},
      doi          = {10.5281/zenodo.17772518},
      url          = {https://doi.org/10.5281/zenodo.17772518}
    }

---

## Version History

| Version | Date       | Change                                                           |
|---------|------------|------------------------------------------------------------------|
| v2.2    | 2025-12-05 | Structural improvements to README layout; improved machine readability |
| v2.1    | 2025-12-04 | Removed Prolific IDs; file replacements                          |
| v2.0    | 2025-12-01 | Updated with DOI number added to README                          |
| v1.0    | 2025-11-30 | Initial release                                                  |
---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.
