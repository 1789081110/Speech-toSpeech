# Speech-toSpeech
Using pre trained model whisper i have extracted the text from the audio then the text is translated using the facebook/mbart-large-50-one-to-many-mmt model from english to hindi.
the text is preprocessed using the nltk library in nlp.
using bark the translated text is converted to audio in mp2 format.(Similar to tacotron model text-to-speech where the text is converted into mel spectrogram then it is converted into audio using the vocoder).
This model can further be cloned with any voice we want using "sail-rvc/ElonMuskV1" model but currently this model not available so we can use any other model to clone the audio.
