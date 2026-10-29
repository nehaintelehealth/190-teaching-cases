
# Primary Care Patient Case Studies Dataset (India)

## Contents

- [Overview](#overview)
- [Purpose](#purpose)
- [Case Selection](#case-selection)
- [Dataset Composition](#dataset-composition)
- [Case Index](#case-index)
- [Sources](#sources)
- [Limitations](#limitations)
- [Licensing and Use](#licensing-and-use)
- [Studies Using This Dataset](#studies-using-this-dataset)
- [Citation](#citation)
- [Contact](#contact)

## Overview

This dataset contains 190 standardized patient case studies drawn from medical teaching textbooks. The cases represent patients presenting to a primary care clinic in India and span a range of medical specialties, levels of clinical complexity, and presentation types.

> [!NOTE]
> The cases are teaching cases, not records of real patients. They contain no protected health information.

---

## Purpose

The intended use is [e.g., evaluating clinical decision support tools, benchmarking diagnostic accuracy of AI models, or training health workers].

---

## Case Selection

Cases were selected to reflect the range of patients who present at primary care clinics in India, particularly in rural settings. The selection deliberately includes:

- **Commonly seen conditions** that make up the bulk of primary care visits.
- **Uncommonly seen conditions** that a primary care provider may encounter less often but should be able to recognize.
- **Atypical presentations of common illnesses**, where a frequent condition presents with unusual or misleading features.
- **Tertiary care conditions.** These patients would not usually be treated at a primary care facility and would instead be referred to a higher-level facility. They are included because, in rural areas, patients with advanced health issues often present first at a primary care clinic. Recognizing these cases and referring appropriately is a core primary care task.
- **Multiple medical specialties**, so that the dataset is not concentrated in a single clinical area.

The cases were purposively selected. The distribution of conditions in the dataset does not reflect their actual prevalence in Indian primary care populations.

---

## Dataset Composition

Cases are organized into files by specialty group. Dental, Miscellaneous, Geriatrics, Musculoskeletal, Ophthalmology (Eye and Vision), and ENT cases are combined in a single file.

| Specialty group | Case ID prefix | Number of cases |
|---|---|--:|
| Infectious Disease | `Infect` | 54 |
| Gastroenterology & Hepatology | `GI` | 28 |
| Other specialties (combined file) | `Misc`, `Muscle`, `Dental`, `Geri`, `Eye`, `Vision`, `ENT` | 22 |
| Cardiology | `Cardio` | 16 |
| Dermatology | `Derma` | 13 |
| Respiratory Medicine | `Resp` | 12 |
| Endocrinology | `Endoc` | 10 |
| Nephrology | `Renal` | 8 |
| Pediatrics | `Ped` | 8 |
| Neurology | `Neuro` | 7 |
| Obstetrics & Gynecology | `Obgyn` | 6 |
| Hematology | `Blood` | 6 |
| **Total** | | **190** |

The combined file contains:

| Specialty | Case ID prefix | Number of cases |
|---|---|--:|
| Miscellaneous | `Misc` | 10 |
| Musculoskeletal | `Muscle` | 5 |
| Dental | `Dental` | 2 |
| Geriatrics | `Geri` | 2 |
| Ophthalmology | `Eye`, `Vision` | 2 |
| ENT | `ENT` | 1 |
| **Total** | | **22** |

Specialty groups follow the case ID prefix. Case IDs are not consecutive within each group (for example, there is no `Renal3` or `Cardio6`).

Some conditions appear in more than one case, often with different presentations. Examples include urinary tract infection (5 cases), tuberculosis (4 cases, plus tuberculous pleural effusion, meningitis, and lymphadenitis), and malaria (4 cases, plus cerebral malaria).

The full list of cases is in the Case Index below.

---

## Case Index

Cases are listed by specialty group. The diagnosis shown is the reference diagnosis from the source. Click a group to expand it.

<details>
<summary><b>Infectious Disease (54)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Infect1` | Meningitis |
| `Infect2` | Ludwig's Angina |
| `Infect3` | Syphilis |
| `Infect4` | Pneumonia |
| `Infect5` | Typhoid |
| `Infect6` | Diarrhea (Bacterial Enteritis) |
| `Infect7` | Diarrhea (Bacterial Enteritis) |
| `Infect8` | Diarrhea |
| `Infect9` | Gallstones |
| `Infect10` | Sinusitis |
| `Infect11` | Urinary Tract Infection |
| `Infect12` | Scrub Typhus |
| `Infect14` | Giardiasis |
| `Infect15` | Dengue |
| `Infect16` | STD – Chancroid |
| `Infect17` | Typhoid |
| `Infect18` | Cholera |
| `Infect19` | Chickenpox |
| `Infect20` | Urinary Tract Infection |
| `Infect21` | Tuberculous Meningitis |
| `Infect23` | Mononucleosis |
| `Infect24` | Hepatitis E |
| `Infect25` | Pelvic Inflammatory Disease |
| `Infect26` | Herpes |
| `Infect27` | Pharyngitis |
| `Infect28` | Tuberculosis |
| `Infect29` | Influenza |
| `Infect30` | Malaria |
| `Infect31` | Malaria |
| `Infect32` | Pneumonia in HIV Positive Patient |
| `Infect33` | Kala Azar |
| `Infect34` | Amoebic Liver Abscess |
| `Infect35` | HIV |
| `Infect36` | Tuberculosis |
| `Infect37` | Leprosy |
| `Infect38` | Leprosy |
| `Infect39` | Leg Ulcer |
| `Infect40` | HIV |
| `Infect41` | HIV with Tuberculous Lymphadenitis |
| `Infect44` | Dengue |
| `Infect46` | Sinusitis |
| `Infect47` | Pharyngitis |
| `Infect49` | Dengue |
| `Infect50` | Leprosy |
| `Infect51` | Tuberculosis |
| `Infect52` | Pneumonia |
| `Infect53` | Acute Viral Hepatitis |
| `Infect54` | Urinary Tract Infection |
| `Infect55` | Appendicitis |
| `Infect58` | Tuberculosis |
| `Infect59` | Malaria |
| `Infect60` | Cerebral Malaria |
| `Infect61` | Malaria |
| `Infect62` | EB Virus Infection |

</details>

<details>
<summary><b>Gastroenterology & Hepatology (28)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `GI1` | Dyspepsia |
| `GI2` | Chronic Constipation |
| `GI3` | Esophageal Carcinoma |
| `GI4` | Cirrhosis |
| `GI5` | Peptic Ulcer |
| `GI7` | Gall Bladder Stones |
| `GI8` | Liver Cancer |
| `GI9` | Chronic Active Hepatitis |
| `GI10` | Hepatitis B |
| `GI11` | Obstructive Jaundice |
| `GI12` | Cirrhosis with Gallstones |
| `GI13` | Chronic Liver Disease |
| `GI14` | Chronic Duodenal Ulcer |
| `GI15` | Carcinoma of Stomach |
| `GI16` | Pancreatic Cancer |
| `GI17` | Inflammatory Bowel Disease |
| `GI18` | Gastrointestinal Tuberculosis |
| `GI19` | Obstructive Jaundice |
| `GI20` | Acute Viral Hepatitis |
| `GI21` | Cirrhosis |
| `GI22` | Liver Abscess |
| `GI23` | Primary Biliary Cirrhosis |
| `GI24` | Liver Cancer |
| `GI25` | Secondaries in the Liver |
| `GI26` | GERD |
| `GI27` | Gastrointestinal Bleed |
| `GI28` | Cholecystitis |
| `GI29` | Cholecystitis |

</details>

<details>
<summary><b>Other specialties (combined file) (22)</b></summary>

**Miscellaneous (10)**

| Case ID | Diagnosis |
|---|---|
| `Misc1` | Gout |
| `Misc2` | Rheumatoid Arthritis |
| `Misc3` | Psychogenic Erectile Dysfunction |
| `Misc4` | Cluster Headache |
| `Misc5` | Migraine |
| `Misc6` | Lead Poisoning |
| `Misc7` | Insomnia |
| `Misc8` | Smell Disorder |
| `Misc9` | Obesity |
| `Misc10` | Anorexia |

**Musculoskeletal (5)**

| Case ID | Diagnosis |
|---|---|
| `Muscle1` | Back Pain |
| `Muscle3` | Neck Pain (Cervical Spondylosis) |
| `Muscle4` | Heel Pain (Plantar Fasciitis) |
| `Muscle5` | Hip Pain |
| `Muscle6` | Shoulder Pain |

**Dental (2)**

| Case ID | Diagnosis |
|---|---|
| `Dental1` | Dry Mouth Due to Diabetes |
| `Dental2` | Tooth Pain (Pulpitis) |

**Geriatrics (2)**

| Case ID | Diagnosis |
|---|---|
| `Geri1` | Dementia |
| `Geri2` | Early Dementia |

**Ophthalmology (2)**

| Case ID | Diagnosis |
|---|---|
| `Eye1` | Glaucoma |
| `Vision1` | Double Vision in Diabetic |

**ENT (1)**

| Case ID | Diagnosis |
|---|---|
| `ENT1` | Presbyacusis (Hearing Loss) |

</details>

<details>
<summary><b>Cardiology (16)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Cardio1` | Congestive Heart Failure |
| `Cardio2` | Myocardial Infarction |
| `Cardio3` | Myocardial Infarction |
| `Cardio4` | Acute Heart Failure & Pulmonary Edema |
| `Cardio5` | Chronic Heart Failure |
| `Cardio7` | Mitral Regurgitation |
| `Cardio8` | Atrial Fibrillation |
| `Cardio9` | Rhythm Disorders |
| `Cardio10` | Pericardial Effusion |
| `Cardio12` | Mitral Stenosis |
| `Cardio13` | Hypertension |
| `Cardio14` | Acute Rheumatic Fever |
| `Cardio15` | Unstable Angina |
| `Cardio16` | Myocardial Infarction |
| `Cardio18` | Hypertension |
| `Cardio19` | Complete Heart Block |

</details>

<details>
<summary><b>Dermatology (13)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Derma1` | Arthropod Bites (Insect Bite) |
| `Derma2` | Tinea Pedis |
| `Derma3` | Cellulitis |
| `Derma4` | Breast Cancer |
| `Derma5` | Folliculitis |
| `Derma7` | Burns |
| `Derma8` | Psoriasis |
| `Derma9` | Drug Reaction |
| `Derma10` | Shingles |
| `Derma11` | Nevi |
| `Derma12` | Candidiasis (Fungal Infection) |
| `Derma13` | Squamous Cell |
| `Derma14` | Pemphigoid |

</details>

<details>
<summary><b>Respiratory Medicine (12)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Resp1` | COPD |
| `Resp2` | Bronchial Asthma |
| `Resp3` | Chronic Bronchitis |
| `Resp4` | COPD |
| `Resp5` | Chronic Bronchitis with Emphysema |
| `Resp6` | Chronic Bronchitis with Cor Pulmonale |
| `Resp7` | Bronchiectasis |
| `Resp8` | Pleural Effusion (Tuberculosis) |
| `Resp9` | Lung Abscess |
| `Resp10` | Consolidation |
| `Resp11` | Pneumothorax |
| `Resp12` | Collapse of Lung |

</details>

<details>
<summary><b>Endocrinology (10)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Endoc1` | Graves Disease |
| `Endoc2` | Diabetes Insipidus |
| `Endoc3` | Diabetes Mellitus |
| `Endoc4` | Graves Disease |
| `Endoc5` | Hypothyroidism Hyperthyroidism |
| `Endoc6` | Hypothyroidism – Myxedema |
| `Endoc7` | Hypothyroidism |
| `Endoc8` | Graves Disease (Hyperthyroidism) |
| `Endoc9` | Diabetes Mellitus with Neuropathy |
| `Endoc10` | Diabetic Ketoacidosis |

</details>

<details>
<summary><b>Nephrology (8)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Renal1` | Acute Renal Failure |
| `Renal2` | Gout |
| `Renal4` | Nephrotic Syndrome |
| `Renal5` | Renal Failure |
| `Renal6` | Urinary Tract Infection |
| `Renal7` | Hypertension with CKD |
| `Renal8` | Urinary Tract Infection |
| `Renal9` | Chronic Kidney Disease |

</details>

<details>
<summary><b>Pediatrics (8)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Ped1` | Neonatal Herpes Simplex Virus Infection |
| `Ped2` | Pneumonia |
| `Ped3` | Acute Otitis Media |
| `Ped4` | Appendicitis |
| `Ped5` | Acute Poststreptococcal Glomerulonephritis |
| `Ped6` | Acute Epstein-Barr Viral Infection (Infectious Mononucleosis) |
| `Ped7` | Malnourishment |
| `Ped8` | Tetralogy of Fallot (Congenital Heart Disease) |

</details>

<details>
<summary><b>Neurology (7)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Neuro1` | Stroke |
| `Neuro2` | Head Injury |
| `Neuro3` | Parkinsonism |
| `Neuro4` | Alzheimer's Disease |
| `Neuro5` | Pemphigus |
| `Neuro6` | Diabetic Neuropathy |
| `Neuro7` | Syncope |

</details>

<details>
<summary><b>Obstetrics & Gynecology (6)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Obgyn1` | Fibroid Uterus |
| `Obgyn2` | Pelvic Inflammatory Disease |
| `Obgyn3` | Polycystic Ovary |
| `Obgyn4` | Abnormal Uterine Bleeding |
| `Obgyn5` | Ectopic Pregnancy |
| `Obgyn6` | Pregnancy |

</details>

<details>
<summary><b>Hematology (6)</b></summary>

| Case ID | Diagnosis |
|---|---|
| `Blood1` | Lymphoma |
| `Blood2` | Anemia |
| `Blood3` | Anemia |
| `Blood4` | Hemophilia |
| `Blood5` | Anemia |
| `Blood6` | Iron Deficiency Anemia |

</details>

---

## Sources

Cases were taken from various medical textbooks. Each case is cited in its individual case file.

Adaptations made include removing any complex labs or imaging that may not be readily available in a primary health care context in a resource-limited setting.

---

## Limitations

- **Textbook cases are cleaner than real encounters.** They tend to be complete, well-organized, and written to illustrate a teaching point. Real primary care patients often give incomplete or inconsistent histories, and results from such cases may not transfer directly to clinical settings.
- **Not representative of disease prevalence.** Uncommon, atypical, and tertiary cases are over-represented relative to what a primary care clinic typically sees.
- **Source context.** The source textbooks are not India-specific. Cases were adapted so that presentations, available investigations, and management plans reflect Indian primary care practice. A single reviewer made these adaptations, so they may reflect that reviewer's judgment and could introduce bias.

---

## Licensing and Use

The cases are derived from copyrighted textbooks. Any use of the dataset should cite the original textbook source for each case used, as given in the individual case files.

---

## Studies Using This Dataset

Verma N, Buch B, Pandya RS, Taralekar R, Masand I, Rangparia H, Katira JM, Acharya S. **Evaluation and significance of a digital assistant for patient history-taking and physical examination in telemedicine.** *Oxford Open Digital Health*. 2024;2:oqae008. [https://doi.org/10.1093/oodh/oqae008](https://doi.org/10.1093/oodh/oqae008)

This study used the 190 cases to evaluate how much of each case's history and physical examination information Ayu, Intelehealth's history-taking digital assistant, could capture, and whether the resulting clinical note was enough to reach the correct diagnosis and triage decision.

---

## Citation

If you use this dataset, please cite:

```bibtex
@misc{[key],
  title  = {[Dataset Name]: Primary Care Patient Case Studies (India)},
  author = {{Intelehealth}},
  year   = {2024},
  url    = {https://github.com/nehaintelehealth/190-teaching-cases}
}
```

---

## Contact

Neha Verma, Intelehealth, [contact@intelehealth.org](mailto:contact@intelehealth.org)
