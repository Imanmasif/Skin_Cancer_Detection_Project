# Skin Cancer Detection Using Deep Learning

An undergraduate Final Year Project focused on binary skin lesion classification using transfer learning and comparative evaluation of deep learning models.

## Project Background

This project was originally developed as a Bachelor of Science in Computer Science Final Year Project in 2022 at Bahria University, Karachi Campus. The public repository has subsequently been reorganised and documented to improve accessibility and presentation of the original work. The original notebooks and reported experimental work remain the basis of this repository.

## Overview

The project investigates automated classification of skin lesions into two classes:

- Benign / non-melanoma
- Melanoma

The implementation compares multiple transfer-learning approaches and includes a fine-tuned MobileNetV2 experiment. The project also included a prototype Android application using a TensorFlow Lite model.

## Models Evaluated

The project report and repository document experiments with:

- MobileNetV2
- Fine-tuned MobileNetV2
- VGG16
- InceptionV3

The available notebooks are preserved as the original implementation artifacts.

## Reported Results

The FYP report describes the following headline results:

| Model / Experiment | Reported Accuracy |
| --- | ---: |
| MobileNetV2 | 96% |
| Fine-tuned MobileNetV2 | 99% |
| VGG16 | 83% |
| InceptionV3 | 90% |

Some tables and narrative sections in the original report present results from different runs and formats. For transparency, these figures are documented as reported in the original FYP and should not be interpreted as results reproduced after the 2022 project without re-running the experiments.

## Repository Contents

- `MobileNetV2.ipynb` - MobileNetV2 experiment
- `Updated MobileNetV2.ipynb` - updated/fine-tuning experiment
- `VGG16_(1) (1).ipynb` - VGG16 experiment
- `InceptionV3_(1).ipynb` - InceptionV3 experiment
- `docs/project-background.md` - project context and provenance
- `docs/methodology.md` - methodology summary based on the original report
- `docs/results.md` - reported experimental results and interpretation notes
- `docs/mobile-application.md` - Android and TensorFlow Lite component
- `requirements.txt` - environment guidance based on verified notebook imports

## Technical Approach

The project used TensorFlow/Keras-based transfer learning for binary classification. The documented workflow includes data preparation, image preprocessing and augmentation, model training, comparative evaluation, and MobileNetV2 fine-tuning. The report identifies TensorFlow 2.7.0 in the original implementation environment and describes Adam optimisation and sigmoid activation for binary classification.

## Dataset

The original project combined data from three publicly available datasets. The exact source links listed in the repository's original 2022 README were:

1. **SIIM-ISIC Melanoma Classification**  
   https://www.kaggle.com/c/siim-isic-melanoma-classification/data

2. **CNN for Skin Cancer Detection**  
   https://www.kaggle.com/fanconic/cnn-for-skin-cancer-detection/data

3. **Skin Cancer: 9 Classes ISIC**  
   https://www.kaggle.com/nodoubttome/skin-cancer9-classesisic

These links are retained from the original project documentation. Dataset availability, access requirements, and licensing terms may change, so users should review the terms on the original sources before downloading or redistributing any data.

Exact dataset counts in the original report contain inconsistencies, so this repository does not present unverified class totals as definitive.

## Reproducing the Work

The notebooks reflect the original 2022 environment and may require path and dependency updates before execution.

1. Create a Python environment.
2. Install dependencies from `requirements.txt`.
3. Obtain the datasets from the original sources listed above, subject to their terms.
4. Update local dataset paths in the notebooks.
5. Run the notebooks individually.

Example:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

On Windows, activate the environment with:

```bash
.venv\Scripts\activate
```

## Mobile Application Component

The original FYP also included a prototype Android application integrating a TensorFlow Lite model for image classification. The report documents Android Studio, Android Jetpack Navigation and ViewModel components, Firebase Cloud Storage, and TensorFlow Lite as part of this implementation.

## Important Research and Reproducibility Note

This repository documents an academic project originally completed in 2022. Documentation improvements made later do not represent newly conducted experiments. The reported results are preserved from the original FYP report and implementation records.

## Responsible Use

This project is intended for educational and research purposes. It is not a validated clinical decision-support system and must not be used as a substitute for professional medical diagnosis.

## Team Project

This was an undergraduate team Final Year Project. Repository documentation describes the project as a team effort and should not be interpreted as a claim that all components were implemented by a single contributor.

## Dataset Availability

This project was developed using the publicly available datasets listed above. The original dataset files are not included in this repository. Please refer to the original sources and review their respective terms of use and licensing requirements before downloading, using, or redistributing the data.

## Documentation

See the `docs/` directory for additional information on the project background, methodology, reported results, and mobile application component.
