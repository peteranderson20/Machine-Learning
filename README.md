# Machine-Learning
My machine learning projects so far. 

## DeepLearningProjectImprovement.ipynb
[link text]https://github.com/peteranderson20/Machine-Learning/blob/main/DeepLearningProjectImprovement.ipynb
- first project implementing a model with PyTorch, more of an exploration, with imputation as well

## Adult.ipynb
- In this project, I built an end-to-end PyTorch pipeline for a tabular classification task, including a custom dataset, categorical embeddings, a training loop with early stopping, and learning rate scheduling. I gained deeper understanding of logits vs. probabilities, device transfers, batch-level metrics, and debugging NaNs. Despite tuning, the neural network plateaued at ~0.307 validation loss, while XGBoost achieved slightly better performance (AUC 0.929, ACC 0.871), which aligns with its strength on tabular data. Key takeaways: preprocess carefully to avoid leakage, embeddings help compress categorical features, over-parameterization plus regularization often works better than under-parameterization, and tree-based models remain a strong baseline. Next steps would include trying larger MLPs with batch norm, OneCycleLR, or transformer-style tabular models (e.g., FT-Transformer) to push performance further.
