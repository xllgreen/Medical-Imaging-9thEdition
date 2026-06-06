# Medical Imaging — 9th Edition
<div align="center">

> *"21st Century Medical Imaging Guide"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> A clinical skills manual based on the 9th Edition of *Medical Imaging* by People's Medical Publishing House — 136 key clinical skills
<br>
<br>
<img src="/assets/Medical Imaging-9thEdition.jpg" width="260px">
<br>

Why struggle through a whole book?<br>
Just ask a question, and get the answer from the textbook automatically.

<br>

**Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## Project Overview

This project systematically integrates core areas of medical imaging diagnostics, interventional radiology, AI-assisted analysis, and multimodal imaging technology selection, covering **136 key clinical skills** organized into **13 major categories**.

**Target Audience**: Radiologists, clinicians across all specialties, medical students, interventional radiology teams, medical educators

**Reference Textbook**: *Medical Imaging*, 9th Edition, People's Medical Publishing House (National Health Commission "14th Five-Year Plan" textbook)

**⚠️ Risk ⚠️**: This skill provides guidance on high-risk medical diagnosis, treatment, emergency care, and invasive procedures, which could be misused as independent clinical advice.

**Mitigation**: Use all outputs solely as educational or clinician-reviewed reference materials. Qualified clinical supervision, current official guidelines, local protocols, and expert review are required prior to diagnosis, treatment, emergency triage, or procedures.

**⚠️ Risk ⚠️**: Medical imaging prompts or examples may involve patient information or image metadata.

**Mitigation**: Unless permitted by your organization and the data has been properly de-identified, avoid entering identifiable patient information or image metadata.

## Project Structure

```
Medical-Imaging-9thEdition/
├── SKILL.md              # Core configuration — 136-skill registry
├── README.md             # This document — project description and usage guide
├── <skill-name>/         # Detailed definitions for each skill
│   └── SKILL.md          #   Skill details (indications, steps, precautions)
├── scripts/              # Executable tool scripts
├── config/               # Configuration files
├── tests/                # Validation and testing
└── assets/               # Static resources (images, etc.)
```

## Skill Categories Overview

| Category | Skills | Description |
|----------|--------|-------------|
| 🏗️ Imaging Fundamentals & Technology | 9 | X-ray, CT, MRI, ultrasound principles, post-processing, and safety parameters |
| 🤖 AI & Digital Resources | 5 | AI-assisted imaging analysis, intelligent workflows, digital textbook resources |
| 📚 Textbook & Curriculum Development | 3 | Textbook review, revision principles, and clinical curriculum reform strategies |
| 🧠 Central Nervous System | 7 | CT/MRI strategies for head trauma, spinal cord MRI interpretation, demyelinating diseases, and degenerative changes |
| 👁️ Head & Neck | 4 | CT/MRI diagnosis and differentiation of orbital, parotid, and jaw lesions |
| 🫁 Chest & Cardiovascular | 18 | Imaging assessment of lung, pleural, mediastinal lesions, and cardiac/vascular conditions |
| 🫄 Breast & Gynecology | 8 | Mammography/ultrasound, ovarian tumors, placenta previa classification, and uterine artery embolization |
| 🫃 Digestive System | 19 | Multimodal imaging diagnosis and differentiation of GI, hepatobiliary, pancreatic, and splenic disorders |
| 🫘 Urinary & Adrenal | 8 | Renal tumors, cystic lesion classification, urinary tract stones, and adrenal lesion diagnosis |
| 🦴 Musculoskeletal System | 10 | Fracture classification and healing assessment, bone tumors, osteomyelitis, and joint disorders |
| 👶 Pediatrics & Congenital Diseases | 4 | NRDS grading, DDH measurement, intussusception reduction, and rickets staging |
| 💉 Interventional Radiology | 19 | Vascular access, embolization, stenting, ablation, TIPS, and complication management |
| 📋 Comprehensive Diagnostic Principles & Workflow | 14 | Imaging diagnostic reasoning, report interpretation, examination requisition, and multimodal fusion |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install medical-imaging-9th-edition
```

Prompt:
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Medical Imaging 9th Edition" (xllgreen/medical-imaging-9th-edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/medical-imaging-9th-edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### Usage

Each skill consists of four parts:
1. **When to Use** — Indications for triggering the skill
2. **Steps** — Standardized operating procedures
3. **Precautions** — Contraindications and warnings
4. **References** — Detailed supplementary materials

### Query Strategies

#### 1. **Concept Query**

Question:
```bash
Bosniak renal cyst classification 2019 criteria
```

Answer:
```bash
## Bosniak Renal Cyst Classification (2019 Update)

Bosniak classification assesses the malignant risk of renal cystic lesions to guide clinical decisions (follow-up vs. surgery).

### Classification Criteria

| Class | Imaging Features | Malignancy Risk | Management |
|-------|-----------------|-----------------|------------|
| **I** | Simple cyst, thin smooth wall, no septa, calcifications, or solid components; water density on CT, hyperintense on T₂WI MRI, no enhancement | <1% | Benign, no treatment |
| **II** | Few (≤3) thin (≤2 mm) septa; may have fine calcifications or short segment mild thickening | <5% | Benign, no treatment |
| **IIF** | Multiple (≥4) thin septa; mild smooth wall/septal thickening; smooth thick calcifications; no enhancing soft tissue | ~10% | Surveillance |
| **III** | One or more solid components with definite enhancement; irregular wall/septal thickening (≥4 mm) | ~55% | Surgical resection |
| **IV** | Enhancing soft tissue components (≥25% of cystic lesion is solid) | >90% | Surgical resection |

### Key Updates in 2019
1. **More precise septa counting**: ≤3 = few, ≥4 = multiple
2. **Wall/septal thickness quantified**: ≤2 mm = thin, ≥4 mm = definitively thickened
3. **Clearer criteria for "enhancing soft tissue components"**
4. **IIF follow-up recommendation**: initial 6–12 month CT/MRI, then extend to every 2 years if stable

> **Bottom line**: Class I/II are benign — no treatment; Class IIF requires regular surveillance; Class III/IV require surgical resection. Malignancy risk correlates strongly with the extent of solid components.
```

#### 2. **Differential Diagnosis**

Question:
```bash
60-year-old male, long-term smoking history, CT shows a right upper lobe lobulated mass with spiculation and ipsilateral hilar lymphadenopathy
```

Answer:
```bash
## Case Analysis

| Feature | Presentation |
|---------|-------------|
| Age | 60 years (peak incidence for lung cancer) |
| Smoking history | Long-term (high-risk factor) |
| Lesion location | Right upper lobe |
| Morphology | Lobulated (suggesting malignant growth pattern) |
| Margin | Spiculation (malignant sign) |
| Associated findings | Ipsilateral hilar lymphadenopathy |

### Most Likely Diagnosis

**Peripheral lung cancer (consider squamous cell carcinoma or adenocarcinoma)**

### Diagnostic Basis
1. **Clinical risk factors**: 60 years + long-term smoking history
2. **Malignant imaging features**: Lobulation, spiculation
3. **Lymph node metastasis**: Ipsilateral hilar enlargement suggests regional nodal involvement

### Differential Diagnoses
- **Tuberculoma**: Predilection for apical posterior segment of upper lobe / dorsal segment of lower lobe; may show satellite lesions, calcification, and rim enhancement
- **Inflammatory pseudotumor**: Relatively smooth margins; possible history of infection
- **Lung abscess**: May show cavitation with air-fluid level; acute onset with clinical signs of infection

### Recommended Next Steps
1. Contrast-enhanced CT to further evaluate vascularity and mediastinal lymph node status
2. PET-CT for systemic staging
3. CT-guided percutaneous lung biopsy for pathological confirmation
```

#### 3. **Treatment Plan**

Question:
```bash
A patient presents with nausea, vomiting, right upper quadrant dull pain, and fever after TACE procedure. How should this be managed?
```

Answer:
```bash
## Management of Post-TACE Chemoembolization Syndrome

### Assessment
The symptoms above are consistent with **Post-TACE Chemoembolization Syndrome (CES)**:
- Nausea, vomiting — chemotherapy-induced gastrointestinal reaction
- Right upper quadrant dull pain — post-embolization hepatic ischemia and inflammatory response
- Fever — necrotic tissue absorption fever (typically 38–39°C / 100.4–102.2°F)

### Management Plan

| Symptom | Treatment | Notes |
|---------|-----------|-------|
| Fever | Antipyretics (acetaminophen/ibuprofen), physical cooling | If >39°C persists, rule out infection |
| Pain | WHO three-step analgesic ladder | Avoid NSAIDs in HCC patients (hepatic impairment risk) |
| Nausea/vomiting | 5-HT₃ receptor antagonists (ondansetron) | Correct fluid and electrolyte imbalance |
| Hepatoprotection | Glycyrrhizin preparations, reduced glutathione | Routine post-op liver function monitoring |

### Complications Requiring Urgent Investigation
- Severe, persistently worsening abdominal pain → rule out **liver abscess / cholecystitis / pancreatitis**
- Fever >39°C with chills → rule out **infectious complications**
- Increasing ascites, worsening jaundice → rule out **acute liver failure**

> **Typical course**: CES generally lasts 3–7 days and gradually resolves with symptomatic supportive care. If symptoms persist beyond 7 days or progressively worsen, further investigation for complications is warranted.
```

## About the Author

**Xiaolü (xllgreen)** ([https://xllgreen.github.io](https://xllgreen.github.io)) — Student at Jiujiang University School of Clinical Medicine · Tech Geek

## Technical Support
<br>
PDF2App Project: https://pdf2app.cn
<br>
Microsoft Visual Studio Code: https://code.visualstudio.com/
<br>
Claude Code for VS Code: https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API: https://platform.deepseek.com/
© 2026 Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd. All Rights Reserved
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API: https://platform.xiaomimimo.com/
Copyright © 2010 – 2026 Xiaomi. All Rights Reserved
<br>

## License

The content of this project is compiled based on the 9th Edition of *Medical Imaging* by People's Medical Publishing House and is intended for study and reference purposes only.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FMedical-Imaging-9thEdition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Imaging-9thEdition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Imaging-9thEdition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Medical-Imaging-9thEdition&type=date&legend=top-left" />
 </picture>
</a>
