# Audio Tokenization Comparison Side by Side

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bbanar2/Audio-Tokenization-Comparison/blob/main/Audio_Tokenizer_Comparison_Side-by-Side.ipynb)

This Colab Notebook compares the performance of various Audio Tokenizers:

- SoundStream (Not the original implementation, from this repo: https://github.com/haydenshively/SoundStream, model trained on 10k hours of speech)
- EnCodec (48kHz model, music only data)
- SNAC (44kHz model, music compatible)
- WavTokenizer (75 tokens music model, wavtokenizer_medium_music_audio_320_24k.ckpt (not v2 as it was slightly worse))
- SpeechTokenizer (both were speech models, speechtokenizer_snake one is used which is better for music (although not good))
- Wav2Vec2 (wav2vec2-large-960h-lv60-self, not a music model, nor suitable for reconstruction, but used just for experimentation and for token analysis)
