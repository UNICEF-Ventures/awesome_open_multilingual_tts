# Awesome Open Multilingual Text-to-Speech
A repository with information about open multilingual TTS systems and how to use them.

## Overview
This repository provides a few helpful tools:
- A list of languages supported by each TTS system (`language_codes` directory)
- A crosswalk between the language codes of different open TTS systems so that you can see which systems/models are available for a given language (`model_lookups_by_iso.csv`)
- A high-level map of support by language (`model_support.csv`)

This repository is designed to process data in support of the HuggingFace Open TTS demo page: https://huggingface.co/spaces/khof312/tts_mockingbird

# Models supported
Currently, systems covered are:
- IMS Toucan
- Meta MMS
- espeak NG
- coqui
- piper

# To Do
> [!NOTE]
> In progress: 
> - Simple python scripts for running each TTS in a given language
> - Support for:
>  - African voices, Mimic, Meta Seamless M4T
