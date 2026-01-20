# causality-aware-retriever

<img width="4193" height="2122" alt="causal_retrieval" src="https://github.com/user-attachments/assets/0126c7f8-412d-4e23-abfd-52fbda635315" />



## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/00HS/causality-aware-retrieval.git
cd causality-aware-retrieval
```

### 2. Train the model
To train a model, select the appropriate command in `run_train.sh` by uncommenting it based on your desired model and task.
```bash 
bash run_train.sh
```

### 3. Evaluate the model

```bash 
bash run_eval.sh
```
You can compute Hits@k and MRR scores from the saved retrieval results by running score.py after evaluation.

