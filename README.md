# Mission Galaxy - Cross Match Results

## Inference Result Directories

- **Mission_Galaxy_vgg_single**  
  → Inference results from the `VGGNet_Single` model

- **Mission_Galaxy_vgg_ensemble**  
  → Inference results from the `VGGNet_Ensemble` model

- **Mission_Galaxy_resnet_single**  
  → Inference results from the `ResNet_Single` model

- **Mission_Galaxy_resnet_ensemble**  
  → Inference results from the `ResNet_Ensemble` model


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

---
