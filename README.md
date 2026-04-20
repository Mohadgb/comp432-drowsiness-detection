# COMP 432 — Driver Drowsiness Detection

**Student:** Mohamed Saidi (40248103)
**Course:** COMP 432 — Machine Learning for Computer Vision, Winter 2026
**Concordia University**

## What's here

- `COMP432_Drowsiness_Detection_FINAL.ipynb` — main notebook (self-contained)
- `checkpoints/` — pre-trained model weights (auto-downloaded by the notebook)

## How to run

1. Open `COMP432_Drowsiness_Detection_FINAL.ipynb` in Google Colab (T4 GPU).
2. Runtime → Run all.
3. The notebook auto-downloads checkpoints from this repo on first run.
4. Total runtime: ~5-10 min.

## Results (LightweightCNN on MRL held-out test subjects)

| Metric    | Value  |
|-----------|--------|
| Accuracy  | 0.9813 |
| Precision | 0.9796 |
| Recall    | 0.9871 |
| F1        | 0.9833 |
| ROC-AUC   | 0.9977 |

Subject-independent split, no data leakage.
