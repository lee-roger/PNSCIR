# PNSCIR
### positive-negative spherical interpolation for zero-shot composed image retrieval
## Overview
<img width="1003" height="344" alt="image" src="https://github.com/user-attachments/assets/557ce174-e5ce-4ea1-8eea-0d71bd4965ab" />

### Abstract
Composed Image Retrieval (CIR) retrieves images matching a reference under textual modifications, aligning vision and language to capture user intent. Existing training-free zero-shot CIR (ZS-CIR) methods rely on simple captioning and text fusion, often failing to accurately model visual transformations.To address this, we propose PNSCIR: a framework that leverages pre-trained vision models to generate and validate an image caption, then uses LLMs to decompose the modification into positive (retain/add) and negative (remove) visual elements with intensity scores. Spherical interpolation in CLIP space refines the target description using these disentangled signals, enabling precise retrieval. PNSCIR achieves significant improvements over existing training-free approaches on a range of tasks, raising the mAP@10 score on CIRCO from 32.24 to 38.29 and setting a new state-of-the-art performance for training-free zero-shot composed image retrieval.
