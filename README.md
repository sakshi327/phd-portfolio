# PhD Portfolio — Sakshi Arora

This repository is a curated hub showcasing my doctoral work at the intersection of **artificial intelligence, cheminformatics, and experimental aging biology**.

My research philosophy centers on **closing the loop between computation and biology**: developing interpretable ML models, generating experimentally testable hypotheses, and validating predictions using in vitro and in vivo aging assays.

---

## 🧭 Research Overview

Aging is a pleiotropic, multi-pathway process that cannot be decoded through black-box prediction alone. During my PhD, I developed **mechanism-aware computational frameworks** that explicitly incorporate biological reasoning and are designed to interface directly with experimental validation.

Key experimental systems used:
- Yeast chronological lifespan (CLS)
- Mammalian cell-based senescence and toxicity assays
- *C. elegans* lifespan and healthspan models

---

## 📊 Project Overview

| Project | Scientific Question | Methods | Experimental Integration |
|------|------------------|---------|--------------------------|
| AgeXtend (fork) | Can geroprotectors be predicted mechanistically? | Bioactivity embeddings, explainable ML | Yeast CLS, fibroblast assays, *C. elegans* |
| AgeXtend::Mimetics (demo) | How to identify CR mimetics beyond structure? | Contrastive learning, dual similarity | Assay-aligned prioritization |
| Cheminformatics Toolkit | How to encode biological relevance? | RDKit, fingerprints | Descriptor–assay alignment |
| ML Pipeline Template | How to ensure reproducibility? | Config-driven ML | Experiment-ready outputs |

---

## 🚀 Runnable Demonstration

A minimal, reproducible example illustrating my computational → biological reasoning workflow:

```bash
git clone https://github.com/sakshi327/agextend-mimetics-demo
cd agextend-mimetics-demo
conda env create -f environment.yml
conda activate agextend
python demo.py
```
This demo mirrors how computational prioritization was translated into experimentally testable hypotheses during my PhD.

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
## 📄 Notes
Some repositories contain simplified or anonymized code to respect publication and collaboration constraints. Each project clearly documents scope and limitations.

---
## 📫 Contact
For postdoctoral opportunities or collaborative research, please reach out via GitHub or [email](sakshia@iiitd.ac.in).

---
