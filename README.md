# Dzonglish NMT — Bidirectional English ↔ Roman Dzongkha Translation

First neural machine translation system for bidirectional translation 
between English and Romanized Dzongkha (Dzonglish).

**Paper:** A Neural Machine Translation Approach for Bidirectional 
Translation between English and Roman Dzongkha  
**Institution:** Gyalpozhing College of Information Technology, Royal University of Bhutan & Aplos Lab
**Course:** CSA402 Natural Language Processing  
**Authors:** Ugyen Dendup, Tshering Gyeltshen*, Chime Gyeltshen Dorji*

---

## Links

| Resource | URL |
|---|---|
| GitHub | https://github.com/aploslab/Dotu-dzonglish-nmt |
| Dataset (Kaggle) | https://www.kaggle.com/datasets/ugyentech00/dzonglish-parallel-corpus |
| EN to DZ Model | https://huggingface.co/ugyentech/dzonglish-marian-en-dz |
| DZ to EN Model | https://huggingface.co/ugyentech/dzonglish-marian-dz-en |

## Dataset

- 3,813 parallel English–Dzonglish sentence pairs
- Collected via crowdsourced web platform
- Covers everyday conversational domains
- Split: 70% train / 15% val / 15% test
- Located in `dataset/`

## Models Evaluated

| Model | EN→DZ BLEU | DZ→EN BLEU |
|---|---|---|
| Seq2Seq GRU | 0.00 | 0.00 |
| Seq2Seq + Teacher Forcing | 0.00 | 0.00 |
| Seq2Seq + Attention | 0.00 | 1.14 |
| Transformer | 0.00 | 0.00 |
| MarianMT (fine-tuned) | **5.24** | **3.59** |

## Quickstart

Open `notebooks/Dzonglish_NMT_Final.ipynb` in Google Colab.  
Set runtime to T4 GPU. Upload your CSV and run all cells.

## Citation

If you use this dataset or code, please cite:

Dendup, U., & Gyeltshen, T.*, Dorji, C. G.* (2025). A Neural Machine 
Translation Approach for Bidirectional Translation between English 
and Roman Dzongkha. Gyalpozhing College of Information Technology, Royal University of Bhutan & Aplos Lab
