This repository provides implementations for analyzing discourse coherence in conversational AI, featuring fine-tuned RoBERTa and BART models adapted for dialogue discourse tasks using the STAC corpus.

# Overview
This research investigates how large language models capture discourse structure in multi-party dialogues using the STAC corpus. This study evaluates RoBERTa and BART on:

- **Sentence Ordering**: Restoring original sequence order from shuffled utterances
- **Next Sentence Prediction**: Discriminating coherent vs incoherent utterance pairs

# Key Findings
- Fine-tuning significantly enhances discourse sensitivity in both models
- BART excels at sentence ordering, RoBERTa at NSP due to architectural differences
- Models handle surface-cued relations (Q-A pairs, Comments) well but struggle with pragmatic relations (Contrast, Correction)
- Performance improvements are statistically significant (p < 0.001) across both tasks

# Quick Start
## Installation
```bash
git clone https://github.com/Shuaiqidewo12345/Probing-Discourse-Structure-in-Dialogue.git
cd Probing-Discourse-Structure-in-Dialogue
pip install -r requirements.txt
