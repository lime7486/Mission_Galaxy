# Mission Galaxy - Inference Results

## Column Description

- **Index** – Sequential number of each galaxy in the catalog.  
- **R.A.(deg)** – Right Ascension of the galaxy in degrees.  
- **Decl.(deg)** – Declination of the galaxy in degrees.  
- **2MASS ID** – Identifier of the galaxy in the 2MASS catalog.  
- **2MRS** – Morphological classification from the 2MASS Redshift Survey.  
- **SDSS** – Morphological classification from the SDSS catalog.  
- **DESI** – Morphological classification from the DESI survey.  

- **This study** – Morphological classification derived in this work using the citizen-science dataset.  

- **This study (AI) I** – Morphological classification predicted by the VGGNet_Single model trained on the Mission Galaxy dataset.  
- **This study (AI) II** – Morphological classification predicted by the ResNet_Single model trained on the Mission Galaxy dataset.  
- **This study (AI) III** – Morphological classification predicted by the VGGNet_Ensemble model trained on the Mission Galaxy dataset.  
- **This study (AI) IV** – Morphological classification predicted by the ResNet_Ensemble model trained on the Mission Galaxy dataset.  

---

# Morphological Feature Encoding Scheme

This table describes the notation system and byte positions used to encode galaxy morphological features.

| Byte Position | Morphological Feature        | Notation (Yes / No) |
|--------------|-----------------------------|---------------------|
| 1 | Elliptical galaxy | E / _ |
| 2 | Disk structure | D / _ |
| 3 | Spiral arms | S / _ |
| 4 | Irregular structure | I / _ |
| 5 | Ring structure | R / _ |
| 6 | Central bar structure | B / _ |
| 7 | Merger trace | M / _ |
| 8 | Tidal tail | T / _ |
| 9 | Other peculiar structure | U / _ |
