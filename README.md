# HAIA-ArgumentFallacy
Repository for HAIA course: MM-ArgFallacy2025 Task (Multimodal Argumentative Fallacy Detection and Classification on Political Debates Shared Task): https://nlp-unibo.github.io/mm-argfallacy/2025/


------------
AFC - Classification
------------
**Text-only**:
- BERT
- RoBERTa
- SBERT
- ALBERT
- DeepSeek-R1

**Audio-only**
- BiLSTM
- TransformerEncoder

**Multimodal**
- 


------------
TEXT-ONLY
------------
1) AFC: CLASSIFICATION
	- BERT
	- RoBERTa
	- SBERT
	- ALBERT
	- DeepSeek-R1


2) AFD: DETECTION
	- BERT
	- RoBERTa
	- SBERT
	- ALBERT
	- DeepSeek-R1

------------
AUDIO-ONLY
------------
1) AFC: CLASSIFICATION
   - BiLSTM
   - TransformerEncoder

2) AFD: DETECTION
   - MFCC+CNN
   - Wav2Vec2
     
------------
MULTIMODAL
------------
1) AFC: CLASSIFICATION
   - No model
     
2) AFD: DETECTION
	- RoBERTa + Wav2vec2


	[Adriana]
	- SBERT
	- ALBERT
	- deepseek-ai/DeepSeek-R1-Distill-Llama-8B:
		PROMPT. You task is to detect the type of fallacy in the Text Snippet. The label can be [ESPECIFICAR AQUÍ LAS ETIQUETAS]
		▶ Text Snippet: [SAMPLE]
		▶ Label:

