# WM-811K-WGAN Model

This project uses a **Wasserstein Generative Adversarial Network (WGAN)** to address class imbalance in the **WM-811k** wafer map dataset. The dataset contains highly imbalanced classes, with normal wafers vastly outnumbering defective patterns.

WGAN is leveraged to generate realistic and diverse synthetic samples for underrepresented defect classes. By minimizing the **Wasserstein distance**, this model offers improved training stability and avoids mode collapse, which is common in traditional GANs.

## Highlights

* Input Resolution: **128×128**
* Achieved Accuracy: **98.4%**
* Model Parameters: **< 1.2 million**
* Balanced minority class performance without oversampling or complex augmentation
* Lightweight architecture suitable for deployment in resource-constrained environments

This approach significantly improves defect classification performance, especially for rare classes, while maintaining a compact model footprint.


![Demo](Donut.gif)
