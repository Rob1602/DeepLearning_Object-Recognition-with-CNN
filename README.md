Overview
This project implements a multi-task convolutional neural network that simultaneously classifies the main object in an image and predicts its bounding-box coordinates. The three object classes are cucumber, eggplant, and mushroom.
Methodology
- Normalization of images and bounding-box coordinates.
- Data augmentation with rotations, translations, scaling, horizontal flips, and brightness variations.
- Shared CNN feature extractor with separate classification and localization outputs.
- Randomized hyperparameter search with early stopping and model checkpointing.
- Evaluation through classification and localization metrics.
The original dataset contains 186 images. Data augmentation increases it to 786 nearly balanced samples.
