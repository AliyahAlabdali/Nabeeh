# Presentation figure sources

These SVGs are presentation assets. They do not change training, inference,
notebook outputs, or the original chart files.

| Figure | Evidence |
| --- | --- |
| `pipeline` | Notebook cells 7, 9, 11, 26, 33, 40, and 41. The input is an excerpt of the preprocessing example in cell 26; pink fields mark normalization, not predicted token importance. |
| `evaluation` | Saved test metrics in cell 44. The 507 correct and 10 incorrect predictions follow from the confusion matrix in cell 48. |
| `error-analysis` | Original `assets/confusion_matrix.png` and saved cells 44, 48, and 49. Rows: true labels. Columns: predicted labels. Class order: Legit, Scam. Counts: `[[450, 2], [8, 57]]`. |
| `dataset` | Saved dataset counts and split output in cells 24, 28, and 40. Class percentages are rounded to one decimal place. |
| `learning` | Four-decimal epoch logs saved in cells 41 and 52. Circled points mark the maximum validation macro-F1 in each run, not minimum validation loss. |

Each `-mobile.svg` contains the same evidence and labels in a narrower layout.
The Markdown chooses layouts with native `<picture>` media queries. Embedded
SVG color-scheme rules keep the figures readable when GitHub's manual theme
differs from the OS preference. No custom page CSS is required on GitHub.

`figure-data.json` records the underlying presentation values. Existing
notebook charts remain available as the original evaluation evidence.
