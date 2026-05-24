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
| EN to DZ Model | https://huggingface.co/aploslab/dzonglish-marian-en-dz |
| DZ to EN Model | https://huggingface.co/aploslab/dzonglish-marian-dz-en |

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

If you use this dataset, code, or model, please cite:

```text
Dendup, U., Gyeltshen, T., & Dorji, C. G. (2025). 
A Neural Machine Translation Approach for Bidirectional Translation between English and Roman Dzongkha. 
Gyalpozhing College of Information Technology, Royal University of Bhutan & Aplos Lab.
```

---

## BIOGRAPHIES OF AUTHORS

### Ugyen Dendup

**Ugyen Dendup** is a final-year Bachelor of Science in Computer Science student specializing in AI Development and Data Science at Gyalpozhing College of Information Technology, Royal University of Bhutan. He is the co-founder of NoMind, Bhutan's first AI startup, and co-founder of Aplos Lab, an AI research venture focused on low-resource Bhutanese language models. His research interests include neural machine translation, speech synthesis, and NLP for low-resource languages. He is an Entrepreneur First Bangalore alumnus, a contributor to the UNDP Human Development Report 2025, and a two-time winner of the Best Project of the Year award at GCIT. He can be contacted at email: ugyen@aploslab.com

### Chime Gyeltshen Dorji

**Chime Gyeltshen Dorji** is a final-year Bachelor of Science in Computer Science student specializing in AI Development and Data Science at Gyalpozhing College of Information Technology, Royal University of Bhutan. He is a co-founder of Aplos Lab, and his research interests include NLP, speech technology for low-resource Bhutanese languages, and agentic AI systems. He was awarded 1st Place at the AI4Tarayana Challenge 2026 and Top 6 at the Bhutan Startup Launchpad 2026. He can be contacted at email: chimegyeltshendorji2004@gmail.com

### Tshering Gyeltshen

**Tshering Gyeltshen** is a final-year Bachelor of Science in Computer Science student specializing in AI Development and Data Science at Gyalpozhing College of Information Technology, Royal University of Bhutan. He is an AI Researcher at Aplos Lab with research interests in neural machine translation, RAG systems, and low-resource language processing for Bhutanese dialects. He is a winner of the Tarayana Hackathon 2026, the Bhutan Startup Launchpad 2026, and the Best Project of the Year award at GCIT 2024. He can be contacted at email: tsheringgyeltshen31415@gmail.com
