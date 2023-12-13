# Neural-Machine-Translation
### LSTM based Neural Machine Translation
+ Source Language: English
+ Target Language: Hindi


Basic Info:
------------------------------------------------------
- Dataset Used: [Samanantar v0.3](https://www.kaggle.com/datasets/vinayakkuradia/samanantar-english-hindi-parallel-corpus) ([AI4Bharat](https://ai4bharat.iitm.ac.in/samanantar/)) - English-Hindi Corpus
- Used part: 50,000 lines
- Training data: 44,000
- Validation data: 5,000
- Test data: 1000
- Vocabulary Size - EN: 18839
- Vocabulary Size - HI: 24245


Training - Validation Loss Graph:
------------------------------------------------------
![Train-Validation-Loss-Graph](https://github.com/vinayakkuradia/Neural-Machine-Translation/assets/48391649/f12e0225-0580-4686-9d4c-47b515e28c94)


Hyperparameters:
------------------------------------------------------
- Units of LSTM: 640
- Model optimizer: Root Mean Squared Propagation (RMSProp)
- Loss: Categorical Crossentropy
- Batch Size = 64
- Max Epochs = 101
- Early stopping = YES
- Actual Epochs = 24
- Final Loss Value: 1.6718
- Final Validation Value: 4.1791


Metric scores:
------------------------------------------------------
### On Training data: 
- BLEU Score: 0.281
- Meteor Score: 0.440
- Rouge Score (rouge1):  0.0
- Word Error Rate:  0.593
- Translation Error Rate: 58.815
- Google BLEU Score: 0.311

### On Test data:
- BLEU Score:  0.084
- Meteor Score: 0.224
- Rouge Score (rouge1): 'rouge1': 0.0
- Word Error Rate:  0.844
- Translation Error Rate: 83.763
- Google BLEU Score: 0.133

### On Validation data:
- BLEU Score: 0.102
- Meteor Score: 0.232
- Rouge Score (rouge1): 0.0
- Word Error Rate:  0.828
- Translation Error Rate: 82.362
- Google BLEU Score: 0.144
