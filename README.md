# neuralMachineTranslation
This was a Machine Translation project task assigned to me in the CS224N(Stanford NLP for Deep Learning) course.
The aim is to convert a sentence in the source language(spanish) to target language(english). A seq2seq model architecture was used with a encoder and decoder. A Bi-LSTM was used to encode the source sentences and then the target sentence was predicted using an RNN also adding attention output from the encoder for better results.
model_embeddings.py and nmt_model.py can be looked at to get a good understanding of the project.
