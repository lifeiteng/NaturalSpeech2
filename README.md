# NaturalSpeech2

# Progress
- [x] Align datasets
- [x] Implement modules
- [x] Training
- [x] End-To-End Synthesizer
- [x] Add Loss CE RVQ
- [x] Subjective Evaluation
- [x] Objective Evaluation
- [ ] Demo Page

# Objective Evaluation
* `LibriTTS test clean`
* ASR WER `whisper large-v2`
* Speaker Embedding [https://huggingface.co/docs/transformers/model_doc/wavlm#transformers.WavLMForXVector](https://huggingface.co/docs/transformers/model_doc/wavlm#transformers.WavLMForXVector)

| Prompt | WER | Speaker cosine Similarity  | UtteranceLevel Pitch Mean MAE |  UtteranceLevel Pitch Std MAE |  UtteranceLevel Duration Diff | 
| ---- | ---- | ---- | ---- | ---- | ---- | 
| Ground Truth | 0.86 | - | - | - | - |
| 2 Seconds |  |  |  |  |  |
| 4 Seconds |  |  |  |  |  |
| 6 Seconds |  |  |  |  |  |
| 8 Seconds |  |  |  |  |  |
| 4 Seconds(PrefixPrompt) |   |  |  |  | (avg utter duration）|

