# ACL2026_DravidianLangTech
# Political Multiclass Sentiment Analysis
DravidianLangTech@ACL 2026 – Rank 2

## Results
Macro-F1: 0.3763  
Accuracy: 0.3364  

## Model
- XLM-RoBERTa-base
- LoRA (r=16, α=32)
- Optuna hyperparameter optimization

## Reproducibility
Best hyperparameters:
- Learning rate: 1.31e-4
- Weight decay: 0.098
- Batch size: 32
- Epochs: 10
