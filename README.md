# BBBP Prediction Project
This project aims to predict Blood-Brain Barrier Penetration (BBBP) using machine learning models based on molecular structures and features.

## Project Objective
The BBBP Prediction Project focuses on leveraging machine learning models to predict the ability of chemical compounds to penetrate the blood-brain barrier (BBB). By analyzing molecular structures and features extracted from compounds, the project aims to develop accurate predictive models that classify compounds as either penetrators or non-penetrators of the BBB.

## Project Overview
The project revolves around a dataset comprising molecular features of chemical compounds, including their SMILES representation and names, alongside the binary classification of BBB penetration (1 for Penetrates, 0 for Doesn't Penetrate). Through comprehensive analysis and model development, the goal is to construct robust predictive models capable of accurately determining BBB penetration for new compounds.

## Key Columns:
- Smiles: SMILES representation of chemical compounds
- Name: Name of chemical compounds
- p_np: BBBP classification (1: Penetrates, 0: Doesn't Penetrate)


## Setup

1. Clone the repository.

```bash
git clone https://github.com/RobinMaheshwary/BBBP-PREDICTION
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

## Model Architecture

<!-- pic embed from ./models/model.png -->

![Model Architecture](./models/model.png)

## Future Improvements

- Hyperparameter tuning for models to enhance performance.
- Incorporate additional molecular descriptors for better predictive power.
- Explore deep learning architectures for improved accuracy.


## License
This project is licensed under [DBaJ-NC-CFL](./LICENCE.md). Refer to LICENSE for more details.