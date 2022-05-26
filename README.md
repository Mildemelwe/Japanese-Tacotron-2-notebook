# Japanese Tacotron 2 notebook
Training notebook for Japanese TTS model with Tacotron 2
# Usage
This is just a basic implementation of Japanese in Tacotron 2, so if you've used Tacotron 2 before you should have no trouble. For a detailed, beginner-oriented guide, check usage.pdf.
- Transcription should use TALQu phonetics to comply with the pretrained model in use. You may use my g2p to convert from Japanese text: https://colab.research.google.com/drive/1RQGSlx2LWl0gfokup9r-nVTeI-oe-SGs?usp=sharing
- From my testing, around 15 minutes of audio is the minimum for proper speech. Less data may produce unwanted results such as gibberish phonemes. I did a test with 8 minutes, and many phonetic combinations could not be reproduced.
# Attributions
- Phonetic system from TALQu (https://booth.pm/ja/items/2755336)
- Pretrained model by Haruqa (https://github.com/Haruqa/tacotron2/releases)
- Some code formatting from the Uberduck Tacotron 2 training notebook (https://colab.research.google.com/drive/1WTilMdm9Vf7KE79gzkeeTBigAN6iv3Bg?usp=sharing)
- Tacotron 2 implementation by NVIDIA (https://github.com/NVIDIA/tacotron2)
