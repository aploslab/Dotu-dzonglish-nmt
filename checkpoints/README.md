# Model Checkpoints

## From-scratch models (.pt files)

Load with:

    import torch
    model.load_state_dict(torch.load('best_En_Seq2SeqAttention.pt', map_location='cpu'))

## MarianMT fine-tuned models

Load directly from HuggingFace:

    from transformers import MarianMTModel, MarianTokenizer

    tokenizer = MarianTokenizer.from_pretrained('ugyentech/dzonglish-marian-en-dz')
    model = MarianMTModel.from_pretrained('ugyentech/dzonglish-marian-en-dz')

HuggingFace links:

- EN to DZ: https://huggingface.co/ugyentech/dzonglish-marian-en-dz
- DZ to EN: https://huggingface.co/ugyentech/dzonglish-marian-dz-en
