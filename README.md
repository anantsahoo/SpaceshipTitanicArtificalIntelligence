# Spaceship Titanic Challenge

This project addresses Kaggle’s **Spaceship Titanic** classification challenge, where the goal is to predict whether passengers were transported to an alternate dimension after a spacetime anomaly.

We started with Kaggle’s baseline Random Forest model and improved performance through better preprocessing and hyperparameter tuning.

## What We Did

- Reproduced Kaggle’s baseline Random Forest model
- Reimplemented the model using **Scikit-learn**
- Applied:
  - One-hot encoding for categorical features
  - Feature scaling for numerical features
  - Mean/mode imputation for missing values
- Used stratified train-test splitting and a fixed random seed
- Tuned hyperparameters using `RandomizedSearchCV`

## Results

- **Baseline accuracy:** 78.653%
- **Improved accuracy:** **79.752%**

## Files

- `baseline.ipynb` – Kaggle tutorial baseline model
- `improved.ipynb` – Improved model with preprocessing and tuning
- `group_2_project_report.pdf` – Full project report

## References

- Kaggle, *Spaceship Titanic Competition*.  
[Kaggle Spaceship Titanic Competition](https://www.kaggle.com/competitions/spaceship-titanic/overview)

## License

This repository’s original code is licensed under the MIT License. See the `LICENSE` file for details.

Any external datasets, libraries, lecture materials, papers, or third-party resources used in this repository are subject to their respective licenses and terms of use.

## Contact and Collaboration

I am open to feedback, questions, and collaboration related to this project.

For project-related messages, please include the repository name in the subject line so I can easily identify the context.

Suggested subject lines:

- `Question about [SpaceshipTitanicArtificalIntelligence]`
- `Collaboration Opportunity - [SpaceshipTitanicArtificalIntelligence]`
- `Bug Report or Feedback - [SpaceshipTitanicArtificalIntelligence]`

- GitHub: [@anantsahoo](https://github.com/anantsahoo)
- LinkedIn: [Anant Sahoo](https://www.linkedin.com/in/anant-j-sahoo/)
