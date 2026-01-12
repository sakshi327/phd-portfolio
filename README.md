# PhD Portfolio — Sakshi Arora

This repository is the **canonical, curated representation of my PhD work**, showcasing end-to-end research at the intersection of **artificial intelligence, cheminformatics, and experimental aging biology**.

The portfolio is intentionally organized to reflect the **full discovery loop**: from data curation and molecular representation learning, through modeling and validation, to experimental alignment and statistical interpretation.

My research philosophy centers on **closing the loop between computation and biology**—developing interpretable, mechanism-aware ML models and translating their predictions into experimentally testable hypotheses.

---

## 🧭 Research Overview

Aging is a pleiotropic, multi-pathway process that cannot be decoded through black-box prediction alone. During my PhD, I developed **mechanism-aware computational frameworks** that explicitly incorporate biological reasoning and are designed to interface directly with experimental validation.

Key experimental systems used:
- Yeast chronological lifespan (CLS)
- Mammalian cell-based senescence and toxicity assays
- *C. elegans* lifespan and healthspan models

---

## 📂 Repository Structure & Scientific Scope

Each top-level directory corresponds to a distinct scientific stage of the PhD pipeline.


| Directory                                     | Scientific Role                     | What It Demonstrates                                                                  |
| --------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------- |
| `01_data_curation`                            | Data hygiene & biological filtering | Dataset construction, QC, label harmonization, assay-aware preprocessing              |
| `02_feature_engineering`                      | Molecular representation            | RDKit descriptors, fingerprints, bioactivity embeddings, representation sanity checks |
| `03_modeling_and_learning`                    | Learning paradigms                  | Classical ML, boosted models, graph-based DeepChem models, contrastive learning       |
| `04_validation_evaluation`                    | Model robustness                    | Cross-validation, LOOCV, external testing, ROC/AUC analysis, error diagnostics        |
| `05_experimental_alignment`                   | Computation → experiment            | Hit selection logic, toxicity filtering, shortlist generation for wet-lab assays      |
| `06_statistical_analysis_and_visualization`   | Result interpretation               | Survival analysis, non-parametric tests, publication-grade figures                    |
| `07_reproducibility_and_research_engineering` | Research engineering                | Script–notebook separation, environment control, reproducibility checks               |

---

## 🔗 Flagship & Companion Projects

While this repository contains the **complete PhD pipeline**, two external repositories serve as anchors:
- **AgeXtend (flagship project)**
Mechanism-aware AI platform for geroprotector discovery integrating computational prediction with experimental validation

→ Yeast CLS, fibroblast senescence & toxicity assays, C. elegans lifespan
- **AgeXtend::Mimetics (demo)**
Minimal, reproducible demonstration of identifying caloric restriction mimetics beyond structural similarity

→ Assay-aligned prioritization logic for downstream aging experiments

---

## 🧪 Experimental Competencies Demonstrated
- Designing computational screens with downstream assay constraints
- Selecting biologically meaningful hit thresholds
- Interpreting lifespan, senescence, and toxicity readouts
- Iteratively refining models based on experimental feedback

---

## 🧠 Transferable Skills
- End-to-end scientific pipeline design
- Cross-disciplinary communication (AI ↔ wet lab)
- Reproducible, collaborative research engineering
- Mechanistic interpretation of ML outputs

---

## 🧭 How to Navigate This Repository (For New Readers)

If you are exploring this repository for the first time:

1. Start with `01_data_curation/` and `02_feature_engineering/`
→ For dataset construction and molecular representations
2. Then visit `03_modeling_and_learning/` and `04_validation_evaluation/`
→ Understand modeling choices and robustness checks
3. Refer to `05_experimental_alignment/`
→ See how computational predictions are translated into testable biological hypotheses
4. Use `06_statistical_analysis_and_visualization/` for result interpretation

Each notebook/script is documented to emphasize *scientific intent, assumptions, and limitations*.

---

## 📄 Notes
- Code is curated for clarity and defensibility, not completeness
- Some data and components are anonymized to respect publication and collaboration constraints
- Notebooks are intended for conceptual transparency, with heavy computation delegated to scripts where appropriate

---
## 📫 Contact
For postdoctoral opportunities or collaborative research, please reach out via GitHub or via 📧 [email](iamsakshia@gmail.com).

---


