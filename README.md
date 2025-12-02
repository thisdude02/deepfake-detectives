# Deepfake Detectives — CSC490 Project Overview

Welcome to **Deepfake Detectives**, a CSC490 project dedicated to addressing the growing challenge posed by increasingly realistic deepfakes. As manipulated video content becomes harder for humans to detect, the need for reliable and robust deepfake detection systems has never been greater. Existing detectors, while effective in controlled settings, remain vulnerable to adversarial attacks, leaving them unreliable in real-world scenarios.

Our project aims to develop a **video-based deepfake detection model** that not only achieves high accuracy on general deepfake videos but is also **resilient to adversarial perturbations**. To accomplish this, we build upon the **ResNeXt model** designed to capture both spatial and temporal cues in manipulated videos.

We utilize the **FaceForensics++ dataset**, focusing specifically on the *Deepfake* and *DeepFakeDetection* subsets to ensure diverse and challenging training examples.

---

## Repository Structure

```
.
├── notebooks/
│   └── (Based on original GitHub repo by abhijithjadhav)
|
├── Transfer-based Adversarial Training/
│   ├── Testing/
|   ├── Training/
|   |   ├── adversarially_enhanced_model/
|   |   └── baseline_model/
|   ├── Data/
|   |   ├── data_augmentation/
|   |   └── data_split/
|   |       ├── adversarial_splits/
|   |       └── baseline_splits/
|
├── Madry-style Adversarial Training/
|
```

---

## Getting Started

1. Clone the repository in Google Colab.
2. Download [FaceForensics++ dataset](https://github.com/ondyari/FaceForensics) or other deepfake datasets. Ensure deepfakes and adversarial examples are stored in a "manipulated", "deepfake", or "fake" folder.
3. Add paths to datasets in the data preprocessing notebooks.
4. Run the provided Jupyter notebooks for data preprocessing and model training.

---

## Contact & Contributions

For questions, suggestions, or contributions, feel free to open an issue or pull request. Feedback is always welcome!


## Credits/Acknowledgements

The videoDatset class, model architecture and parts of the training code are adapted from [Abhijith Jadhav's Deepfake Detection Using Deep Learning Github repository](https://github.com/abhijithjadhav/Deepfake_detection_using_deep_learning).

The training of the model also uses data from the [FaceForensics++ dataset](https://github.com/ondyari/FaceForensics).

## License Notice

This project uses code derived from a GPL-3.0 licensed repository. Please refer to the original repository for licensing details.
