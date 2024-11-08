# Awesome Open Multilingual Text-to-Speech
A repository with information about open multilingual TTS systems and how to use them.

Currently, systems covered are:
- **IMS Toucan**: Support for 7,233 languages
   - [github](https://github.com/DigitalPhonetics/IMS-Toucan)
   - [demo](https://huggingface.co/spaces/Flux9665/MassivelyMultilingualTTS)
   - [languages](
https://github.com/DigitalPhonetics/IMS-Toucan/blob/MassiveScaleToucan/Utility/language_list.md) 
- **Meta MMS**: Support for 1,108 languages; also capable of Automatic Speech Recognition (ASR) and language ID (LID) for over 4,000 languages
   - [github](https://github.com/facebookresearch/fairseq/tree/main/examples/mms)
   - [languages](https://dl.fbaipublicfiles.com/mms/misc/language_coverage_mms.html)
   - [paper](https://arxiv.org/abs/2305.13516)
   - [blog](https://ai.meta.com/blog/multilingual-model-speech-recognition/)
   - [docs](https://huggingface.co/docs/transformers/model_doc/mms) 
- **coqui**: Support for 37 languages where users can train and add their own models; also supports some multilingual models
   -  [github](https://github.com/coqui-ai/TTS)
   -  [demo](https://huggingface.co/spaces/coqui/CoquiTTS/blob/main/app.py)
   -  [languages](https://github.com/coqui-ai/TTS/blob/dev/TTS/.models.json)
   -  [docs](https://docs.coqui.ai/en/latest/#)
- **espeak NG**: Support for 112 languages
   - [github](https://github.com/espeak-ng/espeak-ng/)
   - [languages](https://github.com/espeak-ng/espeak-ng/blob/master/docs/languages.md) 
- **piper**: Support for 37 languages with multiple variants per language
   - [github](https://github.com/rhasspy/piper)
   - [demo](https://huggingface.co/spaces/k2-fsa/text-to-speech)
   - [languages](https://github.com/rhasspy/piper/blob/master/VOICES.md) 
  
## Overview
In addition to the list of systems, this repository provides a few helpful tools:
- A list of languages supported by each TTS system (`language_codes` directory)
- A crosswalk between the language codes of different open TTS systems so that you can see which systems/models are available for a given language (`model_lookups_by_iso.csv`)
- A high-level map of support by language (`model_support.csv`)

This repository is designed to process data in support of the HuggingFace Open TTS demo page: [https://huggingface.co/spaces/khof312/tts_mockingbird](https://huggingface.co/spaces/OOI-FrontierTech/tts_mockingbird)


# To Do
> [!NOTE]
> In progress: 
> - Simple python scripts for running each TTS in a given language
> - Support for:
>  - [African voices](https://github.com/neulab/AfricanVoices), Mimic, Meta Seamless M4T
>  - Handling coqui TTS models with multiple languages
