# Clinical source notes

The application was built from two source materials supplied for the project:

1. **FEES Report Template** - supplied clinical report template containing encounter/procedure fields, anatomy and secretion findings, swallow physiology, PO trials, PAS, Yale residue, Murray secretion scoring, clinical impression, recommendations, and plan-of-care elements.
2. **DIGEST-FEES 2024 reference** - supplied DIGEST-FEES material describing FEES-specific safety/efficiency grading and the overall DIGEST interaction matrix.

## Implementation safeguards

- PAS and DIGEST-FEES are not treated as interchangeable measures.
- Yale vallecular/pyriform residue ratings are descriptive and are not automatically converted into DIGEST-FEES efficiency grades.
- DIGEST-FEES efficiency uses its own estimated percent pharyngeal residue method after the initial/primary swallow.
- Trials after clinician-cued strategies should not be used to derive DIGEST-FEES ratings.
- Overall DIGEST-FEES severity is derived from the selected Safety and Efficiency grades using the supplied interaction matrix.
- Generated prose should reflect only clinician-selected or entered findings and must be verified before use in the medical record.

## Source publications named in the supplied materials

- Starmer HM, Arrese L, Langmore S, et al. Adaptation and Validation of the Dynamic Imaging Grade of Swallowing Toxicity for Flexible Endoscopic Evaluation of Swallowing: DIGEST-FEES. *Journal of Speech, Language, and Hearing Research*. 2021;64(6):1802-1810.
- Rosenbek JC, Robbins JA, Roecker EB, Coyle JL, Wood JL. A penetration-aspiration scale. *Dysphagia*. 1996;11(2):93-98.
- Neubauer PD, Rademaker AW, Leder SB. The Yale Pharyngeal Residue Severity Rating Scale: An Anatomically Defined and Image-Based Tool. *Dysphagia*. 2015;30(5):521-528.

The full source manuals/PDFs are not included in this repository package.
