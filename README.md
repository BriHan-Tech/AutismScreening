# Autism Screening
This repository contains code and resources for an Autism screening project.

## Table of Contents
- [About](#about)
- [Results](#results)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [License](#license)

## About
The Autism Screening Project is an educational initiative aimed at exploring machine learning techniques for the screening of Autism Spectrum Disorder (ASD). It serves as a learning resource for individuals interested in machine learning, data analysis, and health-related data.

## Results
The project involved training machine learning models for the classification of Autism Spectrum Disorder (ASD) based on the provided dataset. Here are the key results and findings:

- AUPRC Score: 0.93
- AUROC Score: 0.98
- Accuracy Score: 97.87%
- Confusion Matrix:
```
  102   2
  1     36
```
- Classification Report:
```
                precision    recall  f1-score   support

             0       0.99      0.98      0.99       104
             1       0.95      0.97      0.96        37

      accuracy                           0.98       141
     macro avg       0.97      0.98      0.97       141
  weighted avg       0.98      0.98      0.98       141
```

## Getting Started

1. Clone this repository:
```
  git clone https://github.com/your-username/autism-screening.git
  cd autism-screening
```

2. Set up a virutal environment:
```
  python -m venv venv
  source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required dependencies:
```
  pip install -r requirements.txt
```

4. Open the notebook:
```
  jupyter lab
```

## Repository Structure
```
| data/: Directory containing the dataset used for training and testing.
| Autism Screening.ipynb: Jupyter Notebook containing the code and results.
| README.md: This documentation file.
| LICENSE: The license for this repo
| requirements.txt: The required dependencies required to run this repo.
```

## License
This project is provided under the MIT License.