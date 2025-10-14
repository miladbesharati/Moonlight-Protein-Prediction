# Moonlight-Protein-Prediction
A systematic investigation into the impact of protein sequence representations and model architectures on the prediction of moonlighting proteins (MPs).

📖 Abstract
This repository contains the code and analysis for a study on the prediction of MPs. We conducted a systematic investigation into how different protein sequence representations—ranging from TF-IDF k-mers and curated biological features to advanced ESM embeddings—affect predictive performance. These representations were evaluated across a spectrum of machine learning architectures, from baseline classifiers (like Random Forest and Logistic Regression) to deep learning models like Multilayer Perceptrons (MLP) and Siamese Neural Networks (SNN). Our central finding is that the choice of representation plays a more pivotal role in predictive performance and generalization than model complexity alone, providing a guiding principle for future research in this domain.

Moonlight-Protein-Prediction/
├── data/
│   ├── MPfit/                    # Main training and testing dataset
│   ├── Shirafkan/                # Independent validation dataset 1
│   ├── DNA-binding/              # Independent validation dataset 2
│   └── Plant/                    # Independent validation dataset 3
└── notebooks/
    ├── 01_Data_Cleaning_and_Preprocessing.ipynb
    ├── 02_Feature_Engineering.ipynb
    ├── 03_Model_Training_and_Evaluation.ipynb
    └── 04_Visualization.ipynb


