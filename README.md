# Machine-Learning
My machine learning projects so far. 

## DeepLearningProjectImprovement.ipynb
https://github.com/peteranderson20/Machine-Learning/blob/main/DeepLearningProjectImprovement.ipynb

- first project implementing a model with PyTorch, more of an exploration, with imputation as well

## Adult.ipynb
https://github.com/peteranderson20/Machine-Learning/blob/main/Adult.ipynb

- This project gave me a full end-to-end PyTorch pipeline: preprocessing, custom Dataset/DataLoader, embeddings, training loop with early stopping, scheduler, and metrics tracking. I debugged NaN issues on Apple’s MPS backend, compared against XGBoost, and learned a lot about logits, BCEWithLogitsLoss, and model regularization. Validation loss plateaued at ~0.307, so I experimented with architectural tweaks, dropout/batch norm, Optuna tuning, and even SMOTE for balancing. These refinements didn’t beat XGBoost (which still shines on tabular data), but they gave me hands-on experience with error analysis, class imbalance handling, and hyperparameter search. The biggest win is a clean, reusable PyTorch training framework and a strong baseline I can build on for future projects.
