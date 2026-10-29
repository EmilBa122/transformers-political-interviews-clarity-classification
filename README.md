# transformers-political-interviews-clarity-classification

##  Assignment Description

Clarity classification of responses in political interviews (Clear Reply, Ambivalent, Clear Non-Reply) by fine tuning three pretrained transformer 
models (BERT, DistilBERT, DeBERTa-v3) from the Hugging Face Transformers library, trained with a custom PyTorch training loop, based on SemEval 
2026 Task 6 (CLARITY)

##  Notebooks inside this repo

| Notebook Name | Description |
|---|---|
| `bert-base-uncased.ipynb` | fine tuning of bert-base-uncased |
| `distilbert-base-uncased.ipynb` | fine tuning of distilbert-base-uncased |
| `microsoft-deberta-v3-base.ipynb` | fine tuning of microsoft/deberta-v3-base |

##  Dataset

The dataset used in this project is available on Hugging Face: [ailsntua/QEvasion](https://huggingface.co/datasets/ailsntua/QEvasion)

Backup copy of the dataset, in case the above original link is no longer available: [EmilBa122/QEvasion-backup](https://huggingface.co/datasets/EmilBa122/QEvasion-backup)
