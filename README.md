## Non-Speech Sound Classification

This project focuses on classifying non-speech sounds into seven distinct categories using a Convolutional Neural Network (CNN). The dataset used consists of **7,000 audio samples**, and class imbalance was addressed as part of the preprocessing pipeline.

### Model Highlights:

* Implemented a custom **CNN architecture** for audio classification
* Applied techniques to **correct class imbalance**
* Evaluated on a held-out test set with the following performance:

| Metric        | Value  |
| ------------- | ------ |
| Test Loss     | 0.5746 |
| Test Accuracy | 82.48% |
| Precision     | 83.91% |
| Recall        | 82.48% |
| F1 Score      | 82.69% |

### Results:

![Model Performance](https://github.com/user-attachments/assets/440a291b-700d-4d5d-b4db-fb6cede5b480)

### Tools and Libraries:

* PyTorch
* SciPy

### References:

* [7K Non-Speech Sound Dataset Paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/sil2.12233#:~:text=There%20are%20some%20contributions%20in,sneeze%2C%20snore%2C%20and%20scream.)
* [Challenge Link](https://madhavlab.github.io/2025_summerproject.html)
* [Dataset on Zenodo](https://zenodo.org/records/6967442)

---

Let me know if you'd like a LaTeX version of this for a resume, report, or poster.
